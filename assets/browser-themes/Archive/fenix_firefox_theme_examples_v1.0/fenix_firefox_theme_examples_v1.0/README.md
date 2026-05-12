# Fenix Gaming Firefox Theme Examples v1.0

Six color-only Firefox static-theme examples based on the Fenix Gaming Brand Kit v1.4.

## Themes

| Theme | Variant | Intent |
|---|---|---|
| Fenix Night Command | Dark | Default daily-driver dark theme. Strong brand fit, low visual noise. |
| Fenix Rift Scout | Dark | Analytical, map-reading, scouting-heavy vibe. Cyan is used as a chrome accent, not the whole personality. |
| Fenix Threat Meta | Dark | Sharper, more aggressive dark theme. Good for PvP/meta content without becoming discount gamer-red sludge. |
| Fenix Smoked Command | Light | Readable light theme that keeps the tactical purple tone. Not another washed-out lavender spreadsheet injury. |
| Fenix Tactical Map | Light | Best light alternative when the browser should feel more technical and less ornamental. |
| Fenix Astral Rare | Dark | More magical/lore-forward while staying inside the Fenix brand system instead of sprinting into synthwave chaos. |

## Test locally in Firefox

1. Open `about:debugging#/runtime/this-firefox`.
2. Click **Load Temporary Add-on...**.
3. Open one theme folder and select its `manifest.json`.
4. Firefox applies the theme until restart. Repeat with another folder to compare.

## Build notes

- These are static color-only themes. No content permissions. No scripts. No surveillance goblin nonsense.
- Use `tab_line`, `tab_loading`, `icons_attention`, and `toolbar_field_border_focus` for accent personality.
- Keep large chrome areas on brand base/surface colors. Do not flood the toolbar with accent colors.
- Package one theme folder at a time if submitting to addons.mozilla.org.

## Recommended winner

Start with **Fenix Night Command** as the default dark theme and **Fenix Smoked Command** as the default light theme. Use the accent variants as optional seasonal or category-flavored themes.