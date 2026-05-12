# Fenix Gaming Brand Kit Direction v1.3

## Version Summary

Version 1.3 updates the v1.2 brand system with two operational palette upgrades:

1. Expand **Option A Light** into a full light-mode design system.
2. Fold in the **Night Command** dark-mode upgrade.
3. Separate brand identity, buttons, links, focus rings, selected states, hover states, borders, and semantic statuses.
4. Keep Fenix Violet as brand identity instead of forcing it into every interactive role.
5. Preserve the Fenix Gaming positioning, typography direction, and core purple strategy-tool logic.

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
2. Dark gray-purple supports gaming UI without becoming black-and-neon cliche.
3. The brand needs enough contrast for dashboards, tables, links, and guide text.
4. The system needs distinct roles: identity, action, background, surface, text, borders, accent, state, and semantic status.

### v1.3 Color Correction

The v1.2 palette fixed the weakest light-mode problem by replacing overly pale lilacs with a smokier Option A direction. Version 1.3 keeps that direction and makes it operational.

The main v1.3 decision: **do not treat a palette as a design system**. A working UI needs more than `background`, `surface`, and `primary`. It needs readable surfaces, raised surfaces, sunken surfaces, selected states, hover states, strong borders, subtle borders, focus rings, links, buttons, and semantic status colors.

The dark theme also now separates buttons from links. Arcane Purple works well as a button fill, but Rift Lilac is better for readable dark-mode link text.

---

# Core Brand Colors

| Role | Name | Hex | Use |
|---|---|---:|---|
| Brand identity | Fenix Violet | `#4B2A7B` | Logo, brand blocks, headers, key visual identity |
| Dark-mode button purple | Arcane Purple | `#7C3AED` | Dark-mode button fills and selected-state borders |
| Light-mode button purple | Command Violet | `#6D28D9` | Light-mode CTAs and primary actions |
| Light-mode hover purple | Deep Command | `#5B21B6` | Light-mode links, hover, pressed, and high-contrast interactive states |
| Dark-mode link purple | Rift Lilac | `#A78BFA` | Dark-mode readable links, highlights, badges |
| Dark-mode focus purple | Moon Rift | `#C4B5FD` | Dark-mode focus rings and high-clarity hover states |
| Dark accent | Ember Gold | `#F59E0B` | Rare emphasis, premium callouts, warnings on dark surfaces |
| Light accent | Burnished Ember | `#92400E` | Accent text, warning labels, and badges on light surfaces |

---

# Dark Theme Palette: Night Command

## Base Tokens

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--bg` | Black Plum | `#100B15` | Main app background |
| `--surface` | Night Violet | `#1B1226` | Cards and panels |
| `--surface-raised` | Arcane Panel | `#27173A` | Modals, dropdowns, elevated panels |
| `--surface-sunken` | Void Well | `#0C0911` | Code blocks, tables, inset wells |
| `--surface-tint` | Rift Wash | `#21152F` | Nested panels, selected rows, hover backgrounds |
| `--border-subtle` | Shadow Plum | `#2E203D` | Internal dividers and quiet row lines |
| `--border` | Warden Violet | `#4B3764` | Visible card borders and section rules |

## Text Tokens

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--text` | Rune Lilac | `#D6C8EA` | Default primary text on dark surfaces |
| `--text-bright` | Moonlit Lilac | `#E7DCF5` | Hero text, key numbers, high-emphasis labels |
| `--text-muted` | Dust Wisteria | `#A99ABF` | Secondary text, captions, helper text |
| `--text-dim` | Ash Plum | `#847490` | Disabled and low-priority text |

## Interaction Tokens

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--primary` | Fenix Violet | `#4B2A7B` | Brand identity only |
| `--button` | Arcane Purple | `#7C3AED` | Primary action button background |
| `--button-hover` | Spell Violet | `#8B5CF6` | Hover and pressed button state |
| `--button-text` | White | `#FFFFFF` | Text on filled buttons |
| `--link` | Rift Lilac | `#A78BFA` | Readable inline links |
| `--link-hover` | Moon Rift | `#C4B5FD` | Link hover and high-emphasis interactive text |
| `--focus` | Moon Rift | `#C4B5FD` | Focus ring and keyboard navigation indicator |
| `--accent` | Ember Gold | `#F59E0B` | Rare emphasis and premium callouts |

## State Tokens

| Token | Hex | Use |
|---|---:|---|
| `--state-hover-bg` | `#21152F` | General hover background |
| `--state-active-bg` | `#2B1844` | Pressed or active panel background |
| `--state-selected-bg` | `#24143A` | Selected nav item or active row background |
| `--state-selected-border` | `#7C3AED` | Active indicator, selected outline |

## Semantic Tokens

| Token | Hex | Use |
|---|---:|---|
| `--success` | `#34D399` | Positive state, valid build, completed task |
| `--success-bg` | `#12281F` | Success badge or alert background |
| `--warning` | `#FBBF24` | Risk, timing issue, resource warning |
| `--warning-bg` | `#2B2110` | Warning badge or alert background |
| `--danger` | `#F87171` | Failure, blocker, destructive action |
| `--danger-bg` | `#2D151A` | Danger badge or alert background |
| `--info` | `#A78BFA` | Neutral tactical note or recommendation |
| `--info-bg` | `#211A34` | Info badge or alert background |

---

# Light Theme Palette: Option A Smoked Command

## Base Tokens

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--bg` | Smoked Lilac | `#DED2E8` | Default page background |
| `--surface` | Rune Mist | `#E9E0F1` | Cards, guide blocks, article panels |
| `--surface-readable` | White | `#FFFFFF` | Long guides, forms, dense tables |
| `--surface-raised` | High Rune | `#F3EEF8` | Popovers, dropdowns, floating cards |
| `--surface-tint` | Veil Amethyst | `#D2C2E2` | Callouts, selected panels, table headers |
| `--surface-sunken` | Inset Lilac | `#C8B6DB` | Filter wells, code blocks, inset panels |
| `--border-subtle` | Soft Amethyst | `#CAB8DC` | Internal dividers and table rows |
| `--border` | Worn Amethyst | `#BCA8D0` | Cards, fields, default outlines |
| `--border-strong` | Iron Amethyst | `#9F86B8` | Selected cards, important containers |

## Text Tokens

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--text` | Void Ink | `#17111F` | Primary text on light surfaces |
| `--text-muted` | Grave Plum | `#554A60` | Captions, helper text, metadata |
| `--text-dim` | Weathered Plum | `#7A6D86` | Placeholder and disabled-adjacent text |
| `--text-inverse` | Moon Ink | `#F5F1FF` | Text on dark brand blocks and filled purple buttons |

## Interaction Tokens

| Token | Name | Hex | Use |
|---|---|---:|---|
| `--primary` | Fenix Violet | `#4B2A7B` | Brand identity, logo, headings, brand blocks |
| `--button` | Command Violet | `#6D28D9` | Primary action button background |
| `--button-hover` | Deep Command | `#5B21B6` | Hover and pressed button state |
| `--button-text` | White | `#FFFFFF` | Text on filled buttons |
| `--link` | Deep Command | `#5B21B6` | Readable inline links |
| `--link-hover` | Fenix Violet | `#4B2A7B` | Link hover and brand-heavy text states |
| `--focus` | Arcane Purple | `#7C3AED` | Focus ring and keyboard navigation indicator |
| `--accent` | Burnished Ember | `#92400E` | Accent text, warning labels, badges |

## State Tokens

| Token | Hex | Use |
|---|---:|---|
| `--state-hover-bg` | `#D8C9E6` | General hover background |
| `--state-active-bg` | `#CDB9DF` | Pressed state or active panel background |
| `--state-selected-bg` | `#D2C2E2` | Selected nav item or active row background |
| `--state-selected-border` | `#6D28D9` | Active indicator, selected outline |

## Semantic Tokens

| Token | Hex | Use |
|---|---:|---|
| `--success` | `#047857` | Positive state, valid build, completed task |
| `--success-bg` | `#D1FAE5` | Success badge or alert background |
| `--warning` | `#92400E` | Risk, timing issue, resource warning |
| `--warning-bg` | `#FEF3C7` | Warning badge or alert background |
| `--danger` | `#B91C1C` | Failure, blocker, destructive action |
| `--danger-bg` | `#FEE2E2` | Danger badge or alert background |
| `--info` | `#5B21B6` | Neutral tactical note or recommendation |
| `--info-bg` | `#EDE9FE` | Info badge or alert background |

---

# Contrast Notes

Approximate contrast ratios for the main readability pairs.

| Pair | Approx. Contrast Ratio | Verdict | Role |
|---|---:|---|---|
| `#17111F` on `#DED2E8` | 12.75:1 | Excellent | Primary text on light page background |
| `#17111F` on `#E9E0F1` | 14.43:1 | Excellent | Primary text on light cards |
| `#554A60` on `#DED2E8` | 5.72:1 | Passes normal text | Muted text on light page background |
| `#7A6D86` on `#DED2E8` | 3.32:1 | Large/UI only | Dim text; avoid critical information |
| `#4B2A7B` on `#DED2E8` | 7.56:1 | Excellent | Brand text on light background |
| `#6D28D9` on `#DED2E8` | 4.90:1 | Passes normal text | Purple text if needed; stronger as button fill |
| `#5B21B6` on `#DED2E8` | 6.20:1 | Passes normal text | Default readable link text |
| `#92400E` on `#DED2E8` | 4.89:1 | Passes normal text | Accent text on light background |
| `#D6C8EA` on `#100B15` | 12.31:1 | Excellent | Primary text on dark page background |
| `#D6C8EA` on `#1B1226` | 11.46:1 | Excellent | Primary text on dark cards |
| `#A99ABF` on `#100B15` | 7.46:1 | Excellent | Muted text on dark background |
| `#A78BFA` on `#100B15` | 7.14:1 | Excellent | Readable dark-mode link text |
| `#7C3AED` on `#100B15` | 3.41:1 | Large/UI only | Button fill; not ideal for small text |
| `#F59E0B` on `#100B15` | 9.05:1 | Excellent | Dark-mode accent |

---

# CSS Tokens

## Dark Theme

```css
:root[data-theme="dark"] {
  /* Base */
  --bg: #100B15;
  --surface: #1B1226;
  --surface-raised: #27173A;
  --surface-sunken: #0C0911;
  --surface-tint: #21152F;

  /* Borders */
  --border-subtle: #2E203D;
  --border: #4B3764;

  /* Text */
  --text: #D6C8EA;
  --text-bright: #E7DCF5;
  --text-muted: #A99ABF;
  --text-dim: #847490;

  /* Brand */
  --primary: #4B2A7B;

  /* Interaction */
  --button: #7C3AED;
  --button-hover: #8B5CF6;
  --button-text: #FFFFFF;

  --link: #A78BFA;
  --link-hover: #C4B5FD;
  --focus: #C4B5FD;

  /* States */
  --state-hover-bg: #21152F;
  --state-active-bg: #2B1844;
  --state-selected-bg: #24143A;
  --state-selected-border: #7C3AED;

  /* Accent */
  --accent: #F59E0B;

  /* Semantic */
  --success: #34D399;
  --success-bg: #12281F;

  --warning: #FBBF24;
  --warning-bg: #2B2110;

  --danger: #F87171;
  --danger-bg: #2D151A;

  --info: #A78BFA;
  --info-bg: #211A34;
}
```

## Light Theme

```css
:root[data-theme="light"] {
  /* Base */
  --bg: #DED2E8;
  --surface: #E9E0F1;
  --surface-readable: #FFFFFF;
  --surface-raised: #F3EEF8;
  --surface-tint: #D2C2E2;
  --surface-sunken: #C8B6DB;

  /* Borders */
  --border-subtle: #CAB8DC;
  --border: #BCA8D0;
  --border-strong: #9F86B8;

  /* Text */
  --text: #17111F;
  --text-muted: #554A60;
  --text-dim: #7A6D86;
  --text-inverse: #F5F1FF;

  /* Brand */
  --primary: #4B2A7B;

  /* Interaction */
  --button: #6D28D9;
  --button-hover: #5B21B6;
  --button-text: #FFFFFF;

  --link: #5B21B6;
  --link-hover: #4B2A7B;
  --focus: #7C3AED;

  /* States */
  --state-hover-bg: #D8C9E6;
  --state-active-bg: #CDB9DF;
  --state-selected-bg: #D2C2E2;
  --state-selected-border: #6D28D9;

  /* Accent */
  --accent: #92400E;

  /* Semantic */
  --success: #047857;
  --success-bg: #D1FAE5;

  --warning: #92400E;
  --warning-bg: #FEF3C7;

  --danger: #B91C1C;
  --danger-bg: #FEE2E2;

  --info: #5B21B6;
  --info-bg: #EDE9FE;
}
```

---

# Component Usage Guidance

## Buttons

Use separate button tokens. Do not use `--primary` for every click target.

```css
.button-primary {
  background: var(--button);
  color: var(--button-text);
  border: 1px solid transparent;
}

.button-primary:hover {
  background: var(--button-hover);
}
```

## Links

Use link tokens, not button tokens.

```css
a {
  color: var(--link);
  text-decoration-thickness: 1px;
  text-underline-offset: 0.18em;
}

a:hover {
  color: var(--link-hover);
}
```

## Cards

```css
.card {
  background: var(--surface);
  color: var(--text);
  border: 1px solid var(--border);
}

.card-raised {
  background: var(--surface-raised);
}

.card-sunken {
  background: var(--surface-sunken);
  border-color: var(--border-subtle);
}
```

## Guide Articles

Use `--surface` for normal branded guide blocks. Use `--surface-readable` for dense reading, forms, and long articles.

```css
.article {
  background: var(--surface);
  color: var(--text);
}

.article-readable {
  background: var(--surface-readable);
  color: var(--text);
}
```

## Tables

```css
.table {
  background: var(--surface-readable, var(--surface));
  color: var(--text);
  border-color: var(--border);
}

.table th {
  background: var(--surface-tint);
  color: var(--primary);
}

.table td {
  border-color: var(--border-subtle);
}
```

## Navigation

```css
.nav-item:hover {
  background: var(--state-hover-bg);
}

.nav-item:active {
  background: var(--state-active-bg);
}

.nav-item[aria-current="page"] {
  background: var(--state-selected-bg);
  border-left: 3px solid var(--state-selected-border);
  color: var(--primary);
}
```

## Focus States

Use the focus token consistently. Do not invent one-off neon outlines.

```css
:focus-visible {
  outline: 2px solid var(--focus);
  outline-offset: 2px;
}
```

## Alerts and Badges

```css
.badge-success {
  color: var(--success);
  background: var(--success-bg);
}

.badge-warning {
  color: var(--warning);
  background: var(--warning-bg);
}

.badge-danger {
  color: var(--danger);
  background: var(--danger-bg);
}

.badge-info {
  color: var(--info);
  background: var(--info-bg);
}
```

---

# Color Rules

## Light Theme Rules

1. Use Smoked Lilac as the default page background.
2. Use Rune Mist for standard cards and guide blocks.
3. Reserve white for dense reading, forms, data-heavy tables, and high-clarity content.
4. Use Veil Amethyst for table headers, guide callouts, selected panels, and low-emphasis content wells.
5. Use Inset Lilac for sunken panels, filters, and code-like areas.
6. Use Deep Command for links, not Arcane Purple.
7. Use Command Violet for button fills.
8. Use Burnished Ember sparingly for accent text and warning-adjacent labels.
9. Do not return to near-white lavender as the default background. It weakens the tactical tone.

## Dark Theme Rules

1. Use Black Plum as the app background.
2. Use Night Violet for default cards and Arcane Panel for raised layers.
3. Use Rune Lilac for normal text and Moonlit Lilac only for hero or high-emphasis moments.
4. Use Arcane Purple for button fills.
5. Use Rift Lilac for readable links.
6. Use Moon Rift for focus and link hover.
7. Use Fenix Violet for identity blocks, not small active UI.
8. Use Ember Gold rarely. If everything is accented, nothing is accented.

---

# Deprecated or Demoted Colors

| Color | Previous Role | v1.3 Decision | Reason |
|---|---|---|---|
| Ashen Lilac | Light background or surface candidate | Deprecated for core palette | Too pale and too soft for the tactical brand tone |
| Pale Rune | Light surface candidate | Deprecated for core palette | Too close to white; lacks enough brand character |
| Moonlit Lilac `#E7DCF5` | Dark-mode primary text candidate | Demoted to `--text-bright` | Strong contrast but too bright for default long-session reading |
| White `#FFFFFF` | Light-theme default surface candidate | Restricted to `--surface-readable` | Useful for dense reading, too generic as the main surface |
| Fenix Violet `#4B2A7B` | General interactive purple candidate | Restricted to identity and brand-heavy states | Too dark for some active UI roles and too valuable as brand color |

---

# Typography Direction

## Recommended System

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

## Final Typography Recommendation

Use this as the v1.3 brand system:

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

---

# Implementation Checklist

1. Replace old light tokens with the Option A Smoked Command system.
2. Add `--surface-readable`, `--surface-raised`, and `--surface-sunken`.
3. Add `--border-subtle` and `--border-strong`.
4. Split button tokens from link tokens.
5. Add selected, hover, and active state tokens.
6. Add semantic tokens for success, warning, danger, and info.
7. Replace dark v1.2 tokens with Night Command dark tokens.
8. Audit every component that uses `#FFFFFF` as a light surface.
9. Reserve white for high-density reading, forms, and tables.
10. Test guide pages, tables, nav, cards, modals, tooltips, selected states, and disabled states in both themes.
11. Re-export palette swatches after component testing.
12. Revisit the logo mark only after the color system is stable.

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
