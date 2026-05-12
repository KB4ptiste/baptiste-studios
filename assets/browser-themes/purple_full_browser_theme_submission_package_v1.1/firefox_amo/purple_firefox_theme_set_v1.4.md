# Firefox Theme Set v1.4

This is the v1.4 public-ready Firefox theme set. All public theme names use visible color language instead of internal brand names.

## Theme inventory

| Theme | Mode | Frame | Toolbar | Selected tab | Accent | Text | Source ZIP |
|---|---|---:|---:|---:|---:|---:|---|
| Black Violet Purple | Dark | `#150A24` | `#1B1226` | `#27173A` | `#7C3AED` | `#D6C8EA` | `black_violet_purple_source_v1.4.zip` |
| Smoked Lilac Purple | Light | `#DED2E8` | `#E9E0F1` | `#F3EEF8` | `#6D28D9` | `#17111F` | `smoked_lilac_purple_source_v1.4.zip` |
| Black Violet Magenta | Dark | `#150A24` | `#1B1226` | `#27173A` | `#E879F9` | `#D6C8EA` | `black_violet_magenta_source_v1.4.zip` |
| Black Violet Orange | Dark | `#150A24` | `#1B1226` | `#27173A` | `#F59E0B` | `#D6C8EA` | `black_violet_orange_source_v1.4.zip` |

## Recommended publication order

1. Black Violet Purple
2. Smoked Lilac Purple
3. Black Violet Orange
4. Black Violet Magenta

Reason: publish the clearest dark/light pair first, then add the two accent variants. That gives users a sane choice instead of a four-theme identity crisis.

## Color discipline

The dark themes keep `#150A24` as the browser frame. That color is visibly purple while remaining dark enough to preserve toolbar and tab hierarchy.

The light theme keeps `#DED2E8` as the smoked lilac frame and `#E9E0F1` as the toolbar surface. White is reserved for the URL field, not used as the whole browser chrome.

## Installation testing

Temporary testing:

```text
about:debugging#/runtime/this-firefox → Load Temporary Add-on... → select manifest.json
```

Permanent public distribution requires AMO submission and signing.
