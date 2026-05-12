# Fenix Firefox Theme Refinement v1.1

## Decision

Replace the dark Firefox frame background `#100B15` with:

```text
#150A24  Black Violet
```

This is a browser-theme refinement of the brand-kit dark background. It keeps the theme dark, but it reads as purple rather than near-black.

## Why not use a lighter purple?

Firefox chrome has fewer layers than the app UI. If the frame gets too close to `#1B1226` / Night Violet, the browser loses separation between frame, toolbar, selected tabs, and popup layers.

## Replacement table

| Old role | Old hex | New hex | New name | Reason |
|---|---:|---:|---|---|
| Dark browser frame | `#100B15` | `#150A24` | Black Violet | More visibly purple while preserving dark contrast |
| Inactive/sunken browser chrome | `#0C0911` where used as Firefox chrome | `#12091C` | Violet Well | Prevents the URL field and inactive frame from becoming pure black holes |

## Contrast checks

| Pair | Contrast |
|---|---:|
| Rune Lilac `#D6C8EA` on Black Violet `#150A24` | 12.09:1 |
| Dust Wisteria `#A99ABF` on Black Violet `#150A24` | 7.32:1 |
| Rift Lilac `#A78BFA` on Black Violet `#150A24` | 7.01:1 |
| Black Violet `#150A24` vs Night Violet toolbar `#1B1226` | 1.05:1 |

## Included themes

Only the three preferred themes are included:

1. Fenix Night Command v1.1
2. Fenix Smoked Command v1.1
3. Fenix Astral Rare v1.1

The discarded variants were intentionally removed. They were not doing useful work.

## Firefox testing

1. Open Firefox.
2. Go to `about:debugging#/runtime/this-firefox`.
3. Select **Load Temporary Add-on...**.
4. Open one theme folder.
5. Select `manifest.json`.
6. Compare the frame, toolbar, tab, URL field, and popup colors.

