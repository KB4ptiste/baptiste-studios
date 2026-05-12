# Firefox Theme Public Listing Guide v1.4

This package contains four public-listing-ready Firefox static themes with brand-specific wording removed from the theme names, source folders, documentation, and listing metadata.

## Naming rule

Use literal color names in the public theme names. Do not use internal product, project, or lore names in AMO titles. Browser-theme users should understand the palette before clicking.

| Old role | Public theme name | Human-readable color signal |
|---|---|---|
| Core dark purple theme | Black Violet Purple | Dark purple base with purple accent |
| Core light purple theme | Smoked Lilac Purple | Light lilac base with purple accent |
| Dark magenta accent theme | Black Violet Magenta | Dark purple base with magenta accent |
| Dark orange accent theme | Black Violet Orange | Dark purple base with orange-gold accent |

## Package structure

```text
purple_firefox_theme_set_v1.4/
├── source/                         # Upload these ZIPs to AMO
├── themes/                         # Unzipped source folders
├── metadata/                       # AMO metadata JSON files
├── previews/                       # Public listing screenshots
├── icons/                          # Icon exports
├── xpi_unsigned_for_dev_only/       # Temporary testing only
├── purple_firefox_theme_public_listing_guide_v1.4.md
└── purple_firefox_theme_set_v1.4.md
```

## Files to upload to AMO

Upload one source ZIP per theme.

```text
source/black_violet_purple_source_v1.4.zip
source/smoked_lilac_purple_source_v1.4.zip
source/black_violet_magenta_source_v1.4.zip
source/black_violet_orange_source_v1.4.zip
```

## Public AMO submission steps

1. Sign in to the AMO Developer Hub.
2. Choose to submit a new add-on.
3. Choose public listing on AMO.
4. Upload one source ZIP from the `source/` folder.
5. Wait for AMO validation.
6. Enter the metadata listed below for that exact theme.
7. Add the matching screenshot from `previews/`.
8. Submit the version.
9. Repeat for the other three themes.

## Public listing metadata


### Black Violet Purple

| Field | Value |
|---|---|
| AMO display name | `Black Violet Purple` |
| Manifest name | `Black Violet Purple` |
| Version | `1.4` |
| Add-on URL slug | `black-violet-purple` |
| Source ZIP | `black_violet_purple_source_v1.4.zip` |
| Add-on ID | `black-violet-purple@purple-color-themes.local` |
| Category | `Solid` |
| Summary | Dark black-violet Firefox theme with purple active-tab accents and muted lilac text. |
| License | `CC-BY-NC-ND-3.0` |
| Experimental | `No` |
| Requires payment/non-free service/hardware | `No` |
| Privacy policy required | `No`, because this is a static theme with no scripts, permissions, remote resources, or data transmission. |
| Support email | `chatgpt@alias.asylum.ink` |
| Support website | Leave blank unless you create a real support page. |
| Developer name | Use your preferred publisher name. Suggested: `Purple Color Themes`. |
| Firefox category fallback | `Other`, if AMO rejects `Solid` for an API submission. |

**Description**

Black Violet Purple is a dark Firefox theme built around a visible purple-black browser frame, muted lilac interface text, and a clean purple active-tab line. It avoids neon glare while still reading clearly as a purple theme.

**Keywords / tags**

`purple`, `dark`, `black violet`, `lilac`, `solid theme`

**Reviewer notes**

```text
Static Firefox theme. Contains only manifest.json, local icon PNG files, and README.md. No scripts, no permissions, no remote resources, no tracking, no analytics, and no data collection or transmission.
```

**Suggested screenshot**

`previews/black-violet-purple_theme_preview_v1.4.png`

**AMO metadata JSON**

`metadata/black-violet-purple_amo_metadata_v1.4.json`


### Smoked Lilac Purple

| Field | Value |
|---|---|
| AMO display name | `Smoked Lilac Purple` |
| Manifest name | `Smoked Lilac Purple` |
| Version | `1.4` |
| Add-on URL slug | `smoked-lilac-purple` |
| Source ZIP | `smoked_lilac_purple_source_v1.4.zip` |
| Add-on ID | `smoked-lilac-purple@purple-color-themes.local` |
| Category | `Solid` |
| Summary | Light smoked-lilac Firefox theme with purple active-tab accents and dark plum text. |
| License | `CC-BY-NC-ND-3.0` |
| Experimental | `No` |
| Requires payment/non-free service/hardware | `No` |
| Privacy policy required | `No`, because this is a static theme with no scripts, permissions, remote resources, or data transmission. |
| Support email | `chatgpt@alias.asylum.ink` |
| Support website | Leave blank unless you create a real support page. |
| Developer name | Use your preferred publisher name. Suggested: `Purple Color Themes`. |
| Firefox category fallback | `Other`, if AMO rejects `Solid` for an API submission. |

**Description**

Smoked Lilac Purple is a light Firefox theme using a muted lilac browser frame, soft purple surfaces, dark plum text, and restrained violet accents. It is designed to feel purple without becoming pale, washed out, or painfully cute.

**Keywords / tags**

`purple`, `light`, `lilac`, `smoked lilac`, `solid theme`

**Reviewer notes**

```text
Static Firefox theme. Contains only manifest.json, local icon PNG files, and README.md. No scripts, no permissions, no remote resources, no tracking, no analytics, and no data collection or transmission.
```

**Suggested screenshot**

`previews/smoked-lilac-purple_theme_preview_v1.4.png`

**AMO metadata JSON**

`metadata/smoked-lilac-purple_amo_metadata_v1.4.json`


### Black Violet Magenta

| Field | Value |
|---|---|
| AMO display name | `Black Violet Magenta` |
| Manifest name | `Black Violet Magenta` |
| Version | `1.4` |
| Add-on URL slug | `black-violet-magenta` |
| Source ZIP | `black_violet_magenta_source_v1.4.zip` |
| Add-on ID | `black-violet-magenta@purple-color-themes.local` |
| Category | `Solid` |
| Summary | Dark black-violet Firefox theme with magenta active-tab and focus accents. |
| License | `CC-BY-NC-ND-3.0` |
| Experimental | `No` |
| Requires payment/non-free service/hardware | `No` |
| Privacy policy required | `No`, because this is a static theme with no scripts, permissions, remote resources, or data transmission. |
| Support email | `chatgpt@alias.asylum.ink` |
| Support website | Leave blank unless you create a real support page. |
| Developer name | Use your preferred publisher name. Suggested: `Purple Color Themes`. |
| Firefox category fallback | `Other`, if AMO rejects `Solid` for an API submission. |

**Description**

Black Violet Magenta is a dark Firefox theme with a purple-black browser frame and vivid magenta accents for active tabs, focused fields, and attention states. It keeps the browser dark while making the accent color obvious to normal humans, a rare courtesy.

**Keywords / tags**

`purple`, `dark`, `magenta`, `black violet`, `solid theme`

**Reviewer notes**

```text
Static Firefox theme. Contains only manifest.json, local icon PNG files, and README.md. No scripts, no permissions, no remote resources, no tracking, no analytics, and no data collection or transmission.
```

**Suggested screenshot**

`previews/black-violet-magenta_theme_preview_v1.4.png`

**AMO metadata JSON**

`metadata/black-violet-magenta_amo_metadata_v1.4.json`


### Black Violet Orange

| Field | Value |
|---|---|
| AMO display name | `Black Violet Orange` |
| Manifest name | `Black Violet Orange` |
| Version | `1.4` |
| Add-on URL slug | `black-violet-orange` |
| Source ZIP | `black_violet_orange_source_v1.4.zip` |
| Add-on ID | `black-violet-orange@purple-color-themes.local` |
| Category | `Solid` |
| Summary | Dark black-violet Firefox theme with orange-gold active-tab and focus accents. |
| License | `CC-BY-NC-ND-3.0` |
| Experimental | `No` |
| Requires payment/non-free service/hardware | `No` |
| Privacy policy required | `No`, because this is a static theme with no scripts, permissions, remote resources, or data transmission. |
| Support email | `chatgpt@alias.asylum.ink` |
| Support website | Leave blank unless you create a real support page. |
| Developer name | Use your preferred publisher name. Suggested: `Purple Color Themes`. |
| Firefox category fallback | `Other`, if AMO rejects `Solid` for an API submission. |

**Description**

Black Violet Orange is a dark Firefox theme with black-violet browser chrome and orange-gold accents on active tabs, focused fields, and attention states. It has the same dark structure as Black Violet Magenta, but swaps the accent to Ember Gold for a warmer premium signal.

**Keywords / tags**

`purple`, `dark`, `orange`, `black violet`, `solid theme`

**Reviewer notes**

```text
Static Firefox theme. Contains only manifest.json, local icon PNG files, and README.md. No scripts, no permissions, no remote resources, no tracking, no analytics, and no data collection or transmission.
```

**Suggested screenshot**

`previews/black-violet-orange_theme_preview_v1.4.png`

**AMO metadata JSON**

`metadata/black-violet-orange_amo_metadata_v1.4.json`


## web-ext command template

Use this only if you want CLI submission rather than the web form.

```bash
web-ext sign \
  --channel=listed \
  --source-dir="themes/black_violet_purple_v1.4" \
  --amo-metadata="metadata/black-violet-purple_amo_metadata_v1.4.json" \
  --api-key="$WEB_EXT_API_KEY" \
  --api-secret="$WEB_EXT_API_SECRET"
```

Change the `--source-dir` and `--amo-metadata` paths for each theme.

## Privacy statement for listings

Use this language if AMO asks for a privacy explanation:

```text
This static Firefox theme does not collect, store, transmit, sell, or share personal data. It contains no scripts, no analytics, no tracking pixels, no remote resources, and no permissions. It only changes Firefox interface colors and uses local icon files included in the theme package.
```

## Version notes

v1.4 changes:

1. Removed brand-specific naming from theme names, documentation, filenames, package folders, and metadata.
2. Renamed all themes using visible color language.
3. Kept the approved v1.1 Black Violet base `#150A24` for dark themes.
4. Kept all four approved themes from the v1.2 set.
5. Added public AMO listing metadata for every theme.
6. Added AMO metadata JSON files for CLI submission.
