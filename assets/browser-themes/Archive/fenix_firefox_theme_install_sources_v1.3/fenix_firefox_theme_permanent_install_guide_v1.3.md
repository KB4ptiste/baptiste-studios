# Fenix Firefox Theme Permanent Installation Guide v1.3

## Goal

Make the Fenix Firefox themes install permanently instead of loading them as temporary extensions.

The practical answer: **normal Firefox requires Mozilla-signed themes for permanent installation**. Temporary loading through `about:debugging` is only for testing. For a personal/private theme, use **AMO unlisted signing**. That gets you a signed `.xpi` without publishing the theme publicly.

## Themes Included

| Theme | Add-on ID |
|---|---|
| Fenix Night Command | `fenix-night-command@fenix-gaming.local` |
| Fenix Smoked Command | `fenix-smoked-command@fenix-gaming.local` |
| Fenix Astral Rare | `fenix-astral-rare@fenix-gaming.local` |
| Fenix Ember Rare | `fenix-ember-rare@fenix-gaming.local` |

## Package Contents

```text
fenix_firefox_theme_install_sources_v1.3/
├── source/
│   ├── fenix_night_command_source_v1.3/
│   │   └── manifest.json
│   ├── fenix_night_command_source_v1.3.zip
│   ├── fenix_smoked_command_source_v1.3/
│   │   └── manifest.json
│   ├── fenix_smoked_command_source_v1.3.zip
│   ├── fenix_astral_rare_source_v1.3/
│   │   └── manifest.json
│   ├── fenix_astral_rare_source_v1.3.zip
│   ├── fenix_ember_rare_source_v1.3/
│   │   └── manifest.json
│   └── fenix_ember_rare_source_v1.3.zip
└── xpi_unsigned_for_dev_only/
    ├── fenix_night_command_unsigned_dev_only_v1.3.xpi
    ├── fenix_smoked_command_unsigned_dev_only_v1.3.xpi
    ├── fenix_astral_rare_unsigned_dev_only_v1.3.xpi
    └── fenix_ember_rare_unsigned_dev_only_v1.3.xpi
```

## Option A: Recommended, private permanent install with AMO unlisted signing

Use this if you want the theme permanently installed in regular Firefox without making it public.

### 1. Prepare the source ZIP

Use one of the files in the `source/` folder:

```text
fenix_night_command_source_v1.3.zip
fenix_smoked_command_source_v1.3.zip
fenix_astral_rare_source_v1.3.zip
fenix_ember_rare_source_v1.3.zip
```

Each ZIP contains a root-level `manifest.json` with a stable `browser_specific_settings.gecko.id` value.

### 2. Submit it to Mozilla for unlisted signing

Go to the Mozilla Add-ons Developer Hub and submit the ZIP as an **unlisted** add-on/theme.

Recommended settings:

| Field | Value |
|---|---|
| Distribution | Unlisted / self-distribution |
| Category | Other or Abstract |
| Listed publicly | No |
| Source code | Not needed unless AMO asks; this is a static manifest-only theme |

### 3. Download the signed `.xpi`

After AMO signs it, download the signed `.xpi`. This is the real installable file.

Expected result:

```text
fenix-night-command-1.3.xpi
```

The exact filename may vary. Firefox cares about the signature, not your emotional attachment to filenames.

### 4. Install the signed file in Firefox

1. Open Firefox.
2. Open **Add-ons and themes**.
3. Click the settings cog.
4. Choose **Install Add-on From File...**.
5. Select the signed `.xpi`.
6. Click **Add**.

Expected result:

```text
The theme appears under Add-ons and themes and stays installed after restart.
```

### 5. Switch between themes

1. Open **Add-ons and themes**.
2. Go to **Themes**.
3. Enable the Fenix theme you want.

Only one Firefox theme can be active at a time. Apparently browsers are monogamous now.

## Option B: Public AMO listing

Use this if you want others to find and install the themes from addons.mozilla.org.

Process:

1. Submit each source ZIP to AMO.
2. Choose public/listed distribution.
3. Add a summary, category, license, support contact, and screenshots.
4. Wait for review.
5. Install from the public listing.

Pros:

- Easiest install flow later.
- Automatic updates through AMO.
- Shareable link.

Cons:

- Public listing requires more metadata.
- Review and presentation standards matter.
- Four separate theme listings may be annoying to maintain.

## Option C: Developer Edition / Nightly / ESR unsigned install

Use this only for development. Do not use this as the main daily-driver path unless you enjoy weakening browser protections for aesthetic purposes, which is very on-brand for humanity but still bad security.

### 1. Use Firefox Developer Edition, Nightly, or ESR

Regular release Firefox will not permanently install unsigned themes.

### 2. Add a stable ID

Already done in these v1.3 manifests:

```json
"browser_specific_settings": {
  "gecko": {
    "id": "fenix-night-command@fenix-gaming.local"
  }
}
```

### 3. Disable signature enforcement

1. Open `about:config`.
2. Search for:

```text
xpinstall.signatures.required
```

3. Set it to:

```text
false
```

### 4. Install the unsigned XPI

Use the files in:

```text
xpi_unsigned_for_dev_only/
```

Install from:

```text
Add-ons and themes → settings cog → Install Add-on From File...
```

Expected result:

```text
Theme installs and persists in the dev-capable Firefox build.
```

Common failure:

```text
This add-on could not be installed because it has not been verified.
```

Meaning:

You are using regular Firefox, or signature enforcement is still active. Firefox is not confused. It is just being irritatingly correct.

## Option D: Firefox Color

Firefox Color is useful for visual tweaking, but it is not the cleanest path for these themes because the Fenix themes already use coded `manifest.json` color keys. Use it for experimentation, not final packaging.

## Recommended Workflow

1. Keep using temporary loading for visual testing.
2. When the colors are final, submit each `source/*.zip` to AMO as **unlisted**.
3. Download each signed `.xpi`.
4. Install each signed `.xpi` through **Add-ons and themes → Install Add-on From File...**.
5. Keep the `source/` folder as the editable source of truth.

## Update Workflow

When you change a theme:

1. Edit `manifest.json`.
2. Increment the version number.
3. Re-zip the source with `manifest.json` at the root.
4. Submit the new version to AMO under the same add-on.
5. Install the new signed `.xpi`.

Do not change the `browser_specific_settings.gecko.id` after the first submission. That ID is the continuity anchor for updates.

## Optional: Build with web-ext

Install `web-ext`:

```bash
npm install --global web-ext
```

Check the install:

```bash
web-ext --version
```

Expected output:

```text
8.x.x
```

Build a ZIP:

```bash
cd fenix_firefox_theme_install_sources_v1.3/source/fenix_night_command_source_v1.3
web-ext build --artifacts-dir ../../artifacts
```

Expected output:

```text
Your web extension is ready: ../../artifacts/fenix_night_command-1.3.zip
```

Sign for private self-distribution:

```bash
web-ext sign --channel=unlisted \
  --api-key="$AMO_JWT_ISSUER" \
  --api-secret="$AMO_JWT_SECRET"
```

Expected output:

```text
Your extension has been submitted for validation.
Your signed file is ready: ./web-ext-artifacts/*.xpi
```

Common failure:

```text
Error: You must provide an API key and secret
```

Fix:

Get AMO API credentials from the Mozilla Add-ons Developer Hub and export them first:

```bash
export AMO_JWT_ISSUER="user:12345:67"
export AMO_JWT_SECRET="your-secret-here"
```

Never commit API credentials to Git. The internet is already a landfill; do not feed it secrets.
