# Smoked Lilac Purple Safari macOS Tint Recipe v1.0

Safari on macOS does not support installable global browser chrome themes equivalent to Chrome or Firefox themes. Use this recipe only for websites, PWAs, or brand-controlled pages where Safari can tint the tab bar from the active webpage.

## Recommended site tint

```html
<meta name="theme-color" content="#DED2E8" media="(prefers-color-scheme: dark)">
<meta name="theme-color" content="#DED2E8" media="(prefers-color-scheme: light)">
```

## Web app manifest snippet

```json
{
  "name": "Smoked Lilac Purple",
  "theme_color": "#DED2E8",
  "background_color": "#DED2E8",
  "display": "standalone"
}
```

## Palette

| Role | Hex |
|---|---:|
| Frame / tint | `#DED2E8` |
| Surface | `#E9E0F1` |
| Field | `#FFFFFF` |
| Text | `#17111F` |
| Accent | `#6D28D9` |
