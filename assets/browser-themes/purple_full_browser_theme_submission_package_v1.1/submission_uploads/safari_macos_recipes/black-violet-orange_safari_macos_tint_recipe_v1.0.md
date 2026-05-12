# Black Violet Orange Safari macOS Tint Recipe v1.0

Safari on macOS does not support installable global browser chrome themes equivalent to Chrome or Firefox themes. Use this recipe only for websites, PWAs, or brand-controlled pages where Safari can tint the tab bar from the active webpage.

## Recommended site tint

```html
<meta name="theme-color" content="#150A24" media="(prefers-color-scheme: dark)">
<meta name="theme-color" content="#DED2E8" media="(prefers-color-scheme: light)">
```

## Web app manifest snippet

```json
{
  "name": "Black Violet Orange",
  "theme_color": "#150A24",
  "background_color": "#150A24",
  "display": "standalone"
}
```

## Palette

| Role | Hex |
|---|---:|
| Frame / tint | `#150A24` |
| Surface | `#1B1226` |
| Field | `#2B2110` |
| Text | `#D6C8EA` |
| Accent | `#F59E0B` |
