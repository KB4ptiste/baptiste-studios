# Fenix Gaming Brand Kit Direction v1.2

## Version Summary

Version 1.2 updates the color system from v1.1 with a stronger light theme and a repaired dark-theme text hierarchy.

Primary changes:

1. Replace the overly pale light-theme background and tint colors with deeper gray-lilac tones.
2. Keep the light theme readable for guides, documentation, SEO pages, and long-form strategy content.
3. Demote Moonlit Lilac from default dark-mode primary text to bright/emphasis text.
4. Add Rune Lilac as the default dark-mode primary text to reduce glare on dark surfaces.
5. Preserve the original Fenix Gaming positioning, typography direction, and core brand logic.

## Positioning

For PC and Mac strategy gamers, Fenix Gaming helps players master complex strategy games with focused companion web apps and practical strategy guides, unlike wikis and fan pages that bury useful decisions under trivia.

## Brand Line

Sharper tools for deeper strategy.

## Brand Personality

- Elegant
- Bold
- Playful
- Edgy

## Color Logic

The color system starts from a tactical dark-mode gaming interface, then builds a light-mode companion system for guides, documentation, SEO pages, and readable long-form content.

The primary purple recommendation is not a random favorite-color pick. It comes from four constraints:

1. Purple supports strategy, mystery, depth, and premium tone.
2. Dark gray-purple supports gaming UI without becoming black-and-neon cliché.
3. The brand needs enough contrast for dashboards, tables, links, and guide text.
4. The system needs distinct roles: identity, action, background, surface, text, borders, and accent.

### v1.2 Color Correction

The v1.1 light theme was usable but too pale. Ashen Lilac, Pale Rune, and similar near-white lilacs softened the brand too much. They worked for readability, but they pushed the light mode toward a gentle fantasy-documentation tone instead of a tactical strategy-tool tone.

The v1.2 correction keeps the light mode readable while making it more grounded, smokier, and more consistent with the dark theme.

The dark theme also receives a text correction. Moonlit Lilac is too bright for default primary text on dark surfaces. It remains useful for hero text and emphasis, but default body and UI text should use a slightly dimmer lilac to avoid glare during long sessions.

## Core Brand Colors

| Role | Name | Hex | Use |
|---|---|---:|---|
| Brand identity | Fenix Violet | `#4B2A7B` | Logo, brand blocks, headers, key visual identity |
| Interactive purple | Arcane Purple | `#7C3AED` | Buttons, links, selected states, active nav |
| Light-mode active purple | Command Violet | `#6D28D9` | CTAs and links on light backgrounds |
| Light-mode hover purple | Deep Command | `#5B21B6` | Hover, pressed, and high-contrast interactive states |
| Highlight purple | Rift Lilac | `#A78BFA` | Focus rings, badges, glows, chart highlights |
| Accent | Ember Gold | `#F59E0B` | Rare emphasis, warnings, premium callouts on dark surfaces |
| Light accent | Burnished Ember | `#92400E` | Accent text, warning labels, and badges on light surfaces |

## Dark Theme Palette

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--bg` | Abyss Plum | `#120D18` | App background |
| `--surface` | Night Violet | `#1C1428` | Cards and panels |
| `--surface-raised` | Deep Arcana | `#261A38` | Modals, dropdowns, elevated panels |
| `--border` | Warden Plum | `#3A2A4D` | Dividers and card borders |
| `--text` | Rune Lilac | `#CFC0E3` | Default primary text on dark surfaces |
| `--text-bright` | Moonlit Lilac | `#E7DCF5` | Hero text, high-emphasis labels, reverse text |
| `--text-muted` | Dusty Wisteria | `#B8A9CC` | Secondary text, captions, helper text, metadata |
| `--primary` | Fenix Violet | `#4B2A7B` | Brand identity blocks |
| `--interactive` | Arcane Purple | `#7C3AED` | Buttons, links, active states |
| `--interactive-hover` | Spell Violet | `#8B5CF6` | Hover state |
| `--focus` | Rift Lilac | `#A78BFA` | Focus ring |
| `--accent` | Ember Gold | `#F59E0B` | Sparing highlight |

### Dark Theme Text Rules

Use `--text` for normal reading and UI text. Use `--text-bright` sparingly.

| Text Token | Use | Avoid |
|---|---|---|
| `--text` / Rune Lilac | Body copy, table text, card titles, form labels, nav text | Huge hero moments that need stronger contrast |
| `--text-bright` / Moonlit Lilac | Hero headings, key numbers, selected-state labels, short callouts | Long paragraphs, dense tables, default UI text |
| `--text-muted` / Dusty Wisteria | Metadata, helper text, captions, disabled-adjacent text | Anything critical to decision-making |

## Light Theme Palette

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--bg` | Smoked Lilac | `#DED2E8` | Page background |
| `--surface` | Rune Mist | `#E9E0F1` | Cards, guide blocks, article panels |
| `--surface-tint` | Veil Amethyst | `#D2C2E2` | Soft sections, callouts, table headers |
| `--border` | Worn Amethyst | `#BCA8D0` | Dividers, card outlines, table lines |
| `--text` | Void Ink | `#17111F` | Primary text on light surfaces |
| `--text-muted` | Grave Plum | `#554A60` | Secondary text, captions, metadata |
| `--primary` | Fenix Violet | `#4B2A7B` | Brand identity blocks, headings, logo |
| `--interactive` | Command Violet | `#6D28D9` | Buttons, links, active states |
| `--interactive-hover` | Deep Command | `#5B21B6` | Hover and pressed states |
| `--focus` | Arcane Purple | `#7C3AED` | Focus rings, selected UI, highlights |
| `--accent` | Burnished Ember | `#92400E` | Accent text, warning labels, badges |

### Light Theme Color Rules

1. Use Smoked Lilac as the default page background instead of near-white lavender.
2. Use Rune Mist for cards and article surfaces. Do not default every content block to pure white.
3. Reserve white only for dense reading areas that need maximum clarity, such as long guide articles or forms.
4. Use Veil Amethyst for table headers, guide callouts, selected panels, and low-emphasis content wells.
5. Use Worn Amethyst for borders. Avoid borders lighter than `#BCA8D0`; they disappear too easily.
6. Use Deep Command for hover states and any link treatment that needs extra contrast.
7. Use Burnished Ember for light-mode accent text. The brighter Ember Gold works better on dark surfaces.

## Deprecated or Demoted Colors

| Color | Previous Role | v1.2 Decision | Reason |
|---|---|---|---|
| Ashen Lilac | Light background or surface candidate | Deprecated for core palette | Too pale and too soft for the tactical brand tone |
| Pale Rune | Light surface candidate | Deprecated for core palette | Too close to white; lacks enough brand character |
| Moonlit Lilac `#E7DCF5` | Dark-mode primary text candidate | Demoted to `--text-bright` | Strong contrast but too bright for default long-session reading |
| White `#FFFFFF` | Light-theme surface | Demoted to optional reading/form surface | Useful, but too generic as the main surface color |

## Contrast Notes

Approximate contrast ratios are listed for the main color pairs that affect readability.

| Pair | Approx. Contrast Ratio | Verdict |
|---|---:|---|
| `#17111F` on `#DED2E8` | 12.75:1 | Excellent primary text on light background |
| `#17111F` on `#E9E0F1` | 14.43:1 | Excellent primary text on light surface |
| `#554A60` on `#DED2E8` | 5.72:1 | Good muted text on light background |
| `#554A60` on `#E9E0F1` | 6.47:1 | Strong muted text on light surface |
| `#4B2A7B` on `#DED2E8` | 7.56:1 | Strong brand text on light background |
| `#6D28D9` on `#DED2E8` | 4.90:1 | Passes normal interactive text |
| `#5B21B6` on `#DED2E8` | 6.20:1 | Strong hover/link contrast |
| `#92400E` on `#DED2E8` | 4.89:1 | Passes accent text |
| `#CFC0E3` on `#120D18` | 11.22:1 | Excellent dark-mode primary text |
| `#CFC0E3` on `#1C1428` | 10.42:1 | Excellent dark-mode primary text on cards |
| `#E7DCF5` on `#120D18` | 14.55:1 | Very bright; best for emphasis only |
| `#B8A9CC` on `#120D18` | 8.74:1 | Strong secondary text |
| `#A78BFA` on `#120D18` | 7.04:1 | Strong focus/highlight |
| `#F59E0B` on `#120D18` | 8.92:1 | Strong dark-mode accent |

## CSS Tokens

```css
:root[data-theme="dark"] {
  --bg: #120D18;
  --surface: #1C1428;
  --surface-raised: #261A38;
  --border: #3A2A4D;

  --text: #CFC0E3;
  --text-bright: #E7DCF5;
  --text-muted: #B8A9CC;

  --primary: #4B2A7B;
  --interactive: #7C3AED;
  --interactive-hover: #8B5CF6;
  --focus: #A78BFA;
  --accent: #F59E0B;
}

:root[data-theme="light"] {
  --bg: #DED2E8;
  --surface: #E9E0F1;
  --surface-tint: #D2C2E2;
  --border: #BCA8D0;

  --text: #17111F;
  --text-muted: #554A60;

  --primary: #4B2A7B;
  --interactive: #6D28D9;
  --interactive-hover: #5B21B6;
  --focus: #7C3AED;
  --accent: #92400E;
}
```

## Component Usage Guidance

### Buttons

Primary action buttons should use interactive purple, not the darker brand purple.

```css
.button-primary {
  background: var(--interactive);
  color: #FFFFFF;
  border: 1px solid transparent;
}

.button-primary:hover {
  background: var(--interactive-hover);
}
```

Use `--primary` for identity-heavy blocks, not every click target.

### Cards

```css
.card {
  background: var(--surface);
  color: var(--text);
  border: 1px solid var(--border);
}
```

Use `--surface-tint` for nested panels, table headers, callouts, and selected-but-not-active states.

### Guide Articles

For long guide articles in light mode, either use `--surface` or white depending on density.

Recommended default:

```css
.article {
  background: var(--surface);
  color: var(--text);
}
```

Use white only when readability needs to beat brand atmosphere:

```css
.article-readable {
  background: #FFFFFF;
  color: var(--text);
}
```

### Tables

```css
.table {
  background: var(--surface);
  color: var(--text);
  border-color: var(--border);
}

.table th {
  background: var(--surface-tint);
  color: var(--primary);
}

.table td {
  border-color: var(--border);
}
```

### Focus States

Use the focus token consistently. Do not invent one-off neon outlines.

```css
:focus-visible {
  outline: 2px solid var(--focus);
  outline-offset: 2px;
}
```

## Typography Direction

### Recommended System

| Role | Font | Weight / Style | Use |
|---|---|---|---|
| Display / logo / hero | Wak | Bold, Extra Bold, Black | Logo, hero titles, campaign headlines |
| Display secondary | Wak | Light, Book | Large section titles, elegant UI labels, not body copy |
| Body / UI / guides | Ubuntu | Regular, Medium, Bold | Main app UI, guide pages, navigation, form labels |
| Utility condensed | Ubuntu Condensed | Regular | Nav labels, tags, stat labels, compact UI moments |
| Data / stats / tables | Ubuntu Mono | Regular, Bold | Tables, build codes, resource values, stat cards |

## Font Evaluation

### Wak Light

Use for large display moments only. It can make the brand feel elegant, but it is too fragile for dense guide text and UI states.

Best uses:

- Hero subheads
- Section intros
- Large editorial quotes
- Premium-looking labels

Avoid:

- Long paragraphs
- Small UI labels
- Tables
- Button text below 16px

### Ubuntu

Best body/UI candidate from the reviewed list.

Why it works:

- It has enough weights for hierarchy.
- It feels technical but approachable.
- It supports the PC/Mac gamer tool vibe.
- It can pair with Ubuntu Mono and Ubuntu Condensed for a coherent system.

Risk:

- It has a recognizable open-source/Linux flavor. For Fenix Gaming, that is probably an advantage, not a problem.

### Ubuntu Condensed

Use as a utility face, not body text.

Best uses:

- Navigation
- Filters
- Badges
- Compact labels
- Strategy tags
- Sidebar category names

Avoid:

- Paragraphs
- Long guides
- Dense table cells

### Marmelad

Useful as a softer editorial or card-heading option, but not the strongest system font.

Best uses:

- Friendly guide headings
- Intro cards
- Small landing pages

Risk:

- Limited family depth. One-weight fonts create hierarchy problems fast.

### Bellefair

Good for elegant lore/editorial flavor, weak as a primary UI/body face.

Best uses:

- Pull quotes
- Lore-style headings
- Special campaign pages
- Occasional editorial accents

Risk:

- It competes with Wak as another display personality. Too many display voices turn the brand into a typography garage sale.

### Ubuntu Mono

Best data font for this brand.

Why:

- It connects naturally to Ubuntu.
- It is readable in tables.
- It feels technical without becoming overly stylized.

### Space Mono

Useful as a more stylized display mono.

Best uses:

- Stat cards
- Short codes
- Hero overlays
- Decorative tactical labels

Avoid:

- Dense tables
- Long code-like blocks
- Heavy guide content

## Recommended Typography Stack

### Option A: Most Cohesive

- Display: Wak
- Body/UI: Ubuntu
- Condensed utility: Ubuntu Condensed
- Data: Ubuntu Mono

Verdict: Best match for Fenix Gaming.

### Option B: More Futuristic

- Display: Wak
- Body/UI: Ubuntu
- Data: Space Mono

Verdict: Stronger visual flavor, weaker table readability.

### Option C: More Elegant

- Display: Wak
- Editorial accent: Bellefair
- Body/UI: Ubuntu
- Data: Ubuntu Mono

Verdict: Useful for lore-heavy strategy games, but harder to control.

## Final Recommendation

Use this as the v1.2 brand system:

```css
--display-font: "Wak", sans-serif;
--body-font: "Ubuntu", system-ui, sans-serif;
--condensed-font: "Ubuntu Condensed", "Arial Narrow", sans-serif;
--mono-font: "Ubuntu Mono", "Space Mono", monospace;
```

Typography rules:

1. Use Wak for recognition.
2. Use Ubuntu for usability.
3. Use Ubuntu Condensed for tactical compression.
4. Use Ubuntu Mono for data.
5. Use Bellefair only as a rare editorial accent.
6. Do not use Marmelad in the core kit unless the brand intentionally shifts softer and more whimsical.

## Implementation Checklist

1. Replace light theme tokens with the v1.2 Smoked Lilac system.
2. Replace dark `--text` with Rune Lilac `#CFC0E3`.
3. Add `--text-bright` as Moonlit Lilac `#E7DCF5`.
4. Audit every component that uses `#FFFFFF` as a light surface.
5. Reserve white for high-density reading or form-heavy screens.
6. Update button hover states to use Deep Command `#5B21B6` in light mode.
7. Use Burnished Ember `#92400E` for light-mode accent text instead of Ember Gold.
8. Test guide pages, tables, nav, cards, modals, tooltips, and selected states in both themes.
9. Re-export palette swatches after component testing.
10. Revisit the logo mark only after the color system is stable. Do not let the logo redesign drag the entire kit back into color indecision purgatory.

## Minimum Kit To Build Next

1. Logo wordmark using Wak Bold or Black.
2. Small phoenix/tactical grid icon.
3. Dark and light color tokens.
4. Button styles.
5. Card styles.
6. Table styles.
7. Guide article template.
8. Icon rules.
9. Social avatar.
10. Brand voice examples.
