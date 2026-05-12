# Fenix Gaming Color System v1.2

## Goal

Reduce the near-white colors in the Fenix Gaming system while keeping the light theme usable, readable, and distinct from generic white-background SaaS sludge. The light theme is now darker, more purple-gray, and less sterile.

## What changed from v1.1

| Previous color | Previous role | New color | New role |
|---|---|---|---|
| `#F5F1FF` / `#F2F1FF` | Dark theme near-white text | `#E7DCF5` | Softer primary text on dark backgrounds |
| `#F8F5FC` | Light theme background | `#E6DCEC` | Darker light background |
| `#FFFFFF` | Light theme surface | `#F0E8F6` | Tinted card/article surface |

## Dark Theme Palette

| Color name | Role | Hex | Use |
|---|---|---:|---|
| Void Plum | Background | `#120D18` | Main app/dashboard background |
| Night Ash | Surface | `#1C1428` | Cards, panels, tool modules |
| Deep Amethyst | Raised Surface | `#261A38` | Modals, dropdowns, elevated UI |
| Warden Plum | Border | `#3A2A4D` | Dividers, card outlines, table lines |
| Moonlit Lilac | Text | `#E7DCF5` | Primary text on dark surfaces |
| Dusty Wisteria | Muted Text | `#B8A9CC` | Secondary text, captions, helper text |
| Fenix Violet | Primary | `#4B2A7B` | Brand blocks, logo, identity moments |
| Arcane Purple | Interactive | `#7C3AED` | Buttons, links, selected states |
| Rift Lilac | Focus / Glow | `#A78BFA` | Focus rings, highlights, chart accents |
| Ember Gold | Accent | `#F59E0B` | Rare emphasis, alerts, premium callouts |

## Light Theme Palette

| Color name | Role | Hex | Use |
|---|---|---:|---|
| Ashen Lilac | Background | `#E6DCEC` | Main light theme page background |
| Pale Rune | Surface | `#F0E8F6` | Cards, guide blocks, article panels |
| Veil Lavender | Tinted Surface | `#D8CBE8` | Soft sections, callouts, table headers |
| Muted Amethyst | Border | `#C8B8DB` | Dividers, card outlines, table lines |
| Void Ink | Text | `#17111F` | Primary text on light surfaces |
| Grave Violet | Muted Text | `#5E536B` | Secondary text, captions, metadata |
| Fenix Violet | Primary | `#4B2A7B` | Brand blocks, logo, headings |
| Command Violet | Interactive | `#6D28D9` | Buttons, links, active states |
| Rift Violet | Focus | `#7C3AED` | Focus rings, selected UI, highlights |
| Burnished Ember | Accent | `#92400E` | Readable accent text, warnings, badges |

## Contrast Checks

These are the practical contrast checks for the revised colors.

| Foreground | Background | Ratio | Verdict |
|---|---|---:|---|
| Moonlit Lilac `#E7DCF5` | Void Plum `#120D18` | 14.55:1 | Strong for body text |
| Dusty Wisteria `#B8A9CC` | Void Plum `#120D18` | 8.74:1 | Strong for muted text |
| Void Ink `#17111F` | Ashen Lilac `#E6DCEC` | 13.92:1 | Strong for body text |
| Grave Violet `#5E536B` | Ashen Lilac `#E6DCEC` | 5.41:1 | Passes for muted text |
| Fenix Violet `#4B2A7B` | Ashen Lilac `#E6DCEC` | 8.25:1 | Strong for headings and brand text |
| Command Violet `#6D28D9` | Ashen Lilac `#E6DCEC` | 5.35:1 | Passes for links and CTAs |
| Burnished Ember `#92400E` | Ashen Lilac `#E6DCEC` | 5.34:1 | Passes for accent text |
| Void Ink `#17111F` | Pale Rune `#F0E8F6` | 15.47:1 | Strong for cards and article panels |
| Grave Violet `#5E536B` | Pale Rune `#F0E8F6` | 6.01:1 | Passes for muted text on cards |

## Usage Rules

1. Use **Void Plum** for dark app backgrounds.
2. Use **Ashen Lilac** for light guide and documentation backgrounds.
3. Use **Pale Rune** instead of pure white for cards, article bodies, forms, and tables.
4. Use **Fenix Violet** as the brand identity color, not as the only button color.
5. Use **Command Violet** for light-theme buttons and links.
6. Use **Arcane Purple** for dark-theme buttons and links.
7. Use **Ember Gold** and **Burnished Ember** sparingly. They are accents, not a second brand identity.
8. Never use `#FFFFFF` as a Fenix Gaming background. Humanity has suffered enough rectangles.

## CSS Tokens

```css
:root {
  --fenix-violet: #4B2A7B;
  --arcane-purple: #7C3AED;
  --command-violet: #6D28D9;
  --rift-lilac: #A78BFA;
  --ember-gold: #F59E0B;
  --burnished-ember: #92400E;
}

[data-theme="dark"] {
  --bg: #120D18;
  --surface: #1C1428;
  --surface-raised: #261A38;
  --border: #3A2A4D;

  --text: #E7DCF5;
  --text-muted: #B8A9CC;

  --primary: #4B2A7B;
  --interactive: #7C3AED;
  --interactive-hover: #8B5CF6;
  --focus: #A78BFA;
  --accent: #F59E0B;
}

[data-theme="light"] {
  --bg: #E6DCEC;
  --surface: #F0E8F6;
  --surface-tint: #D8CBE8;
  --border: #C8B8DB;

  --text: #17111F;
  --text-muted: #5E536B;

  --primary: #4B2A7B;
  --interactive: #6D28D9;
  --interactive-hover: #5B21B6;
  --focus: #7C3AED;
  --accent: #92400E;
}
```
