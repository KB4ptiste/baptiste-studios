# Purple Full Browser Theme Submission Guide v1.1

This package combines the Firefox AMO-ready themes with the cross-browser port package for Chrome, Microsoft Edge, Opera GX, DuckDuckGo, and Safari macOS.

## What changed from the previous cross-browser package

- Added `firefox_amo/` with the public AMO-ready Firefox theme set.
- Added `submission_uploads/` so every upload-ready source ZIP is in one place.
- Added `all_previews/` so screenshots/previews are grouped for easier review.
- Kept the existing theme names: Black Violet Purple, Smoked Lilac Purple, Black Violet Magenta, and Black Violet Orange.

## Theme set

| Theme | Mode | Accent | Recommended launch priority |
|---|---|---|---:|
| Black Violet Purple | Dark | Purple | 1 |
| Smoked Lilac Purple | Light | Purple | 2 |
| Black Violet Orange | Dark | Orange-gold | 3 |
| Black Violet Magenta | Dark | Magenta | 4 |

## Browser support matrix

| Browser / Store | Folder | Public upload package? | Provided here |
|---|---|---|---|
| Firefox AMO | `firefox_amo/` | Yes | Source ZIPs, metadata, previews, icons, unsigned dev-only XPIs |
| Chrome Web Store | `chrome_web_store/` | Yes | Source ZIPs, metadata, previews, store assets |
| Microsoft Edge Add-ons | `microsoft_edge_addons/` | Yes | Source ZIPs, metadata, previews, store assets |
| Opera GX / GX.store | `opera_gx_mods/` | Yes, as GX Mods | GX Mod ZIPs, metadata, previews, store assets |
| DuckDuckGo Browser | `duckduckgo/` | No public installable browser-theme package in this kit | Appearance recipes only |
| Safari macOS | `safari_macos/` | No global browser-chrome theme package in this kit | Site tint / PWA recipes only |

## Fast upload path

Use the consolidated upload folder first:

```text
submission_uploads/
```

### Firefox AMO

```text
submission_uploads/firefox_amo/
```

Upload individually:

```text
black_violet_purple_source_v1.4.zip
smoked_lilac_purple_source_v1.4.zip
black_violet_magenta_source_v1.4.zip
black_violet_orange_source_v1.4.zip
```

Firefox-specific metadata is in:

```text
firefox_amo/metadata/
```

Firefox listing guide:

```text
firefox_amo/purple_firefox_theme_public_listing_guide_v1.4.md
```

### Chrome Web Store

```text
submission_uploads/chrome_web_store/
```

Upload individually:

```text
black-violet-purple_chrome_source_v1.0.zip
smoked-lilac-purple_chrome_source_v1.0.zip
black-violet-magenta_chrome_source_v1.0.zip
black-violet-orange_chrome_source_v1.0.zip
```

Metadata and screenshots:

```text
chrome_web_store/metadata/
chrome_web_store/store_assets/
```

### Microsoft Edge Add-ons

```text
submission_uploads/microsoft_edge_addons/
```

Upload individually:

```text
black-violet-purple_edge_source_v1.0.zip
smoked-lilac-purple_edge_source_v1.0.zip
black-violet-magenta_edge_source_v1.0.zip
black-violet-orange_edge_source_v1.0.zip
```

Metadata and screenshots:

```text
microsoft_edge_addons/metadata/
microsoft_edge_addons/store_assets/
```

### Opera GX / GX.store

```text
submission_uploads/opera_gx_mods/
```

Upload individually:

```text
black-violet-purple_opera_gx_mod_source_v1.0.zip
smoked-lilac-purple_opera_gx_mod_source_v1.0.zip
black-violet-magenta_opera_gx_mod_source_v1.0.zip
black-violet-orange_opera_gx_mod_source_v1.0.zip
```

Metadata and assets:

```text
opera_gx_mods/metadata/
opera_gx_mods/store_assets/
```

### DuckDuckGo recipes

```text
submission_uploads/duckduckgo_recipes/
```

These are color recipes, not uploadable browser theme packages.

### Safari macOS recipes

```text
submission_uploads/safari_macos_recipes/
```

These are site tint and web-app recipes, not installable global browser chrome themes.

## Local testing folders

| Browser | Test folder |
|---|---|
| Firefox | `firefox_amo/themes/` |
| Chrome | `chrome_web_store/build/` |
| Edge | `microsoft_edge_addons/build/` |
| Opera GX | `opera_gx_mods/build/` |

## Recommended submission order

1. Black Violet Purple
2. Smoked Lilac Purple
3. Black Violet Orange
4. Black Violet Magenta

Submit the main dark and light pair first. Submit Orange before Magenta because orange-gold has broader utility; magenta is the sharper niche variant.

## Final preflight checklist

1. Replace placeholder homepage/support/privacy URLs in metadata before public listing.
2. Verify each source ZIP has its manifest at the package root.
3. Use the matching metadata JSON for each platform listing.
4. Use screenshots from the matching platform folder, not a random cousin from another browser.
5. Keep theme names identical across browsers unless a store requires a uniqueness change.
6. Archive signed Firefox XPIs after AMO approval in a separate release folder.
