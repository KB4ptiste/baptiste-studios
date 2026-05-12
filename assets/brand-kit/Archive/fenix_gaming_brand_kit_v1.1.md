# Fenix Gaming Brand Kit Direction v1.1

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

## Core Brand Color

| Role | Name | Hex | Use |
|---|---|---:|---|
| Brand identity | Fenix Violet | `#4B2A7B` | Logo, brand blocks, headers, key visual identity |
| Interactive purple | Arcane Purple | `#7C3AED` | Buttons, links, selected states, active nav |
| Light-mode active purple | Command Violet | `#6D28D9` | CTAs on light backgrounds |
| Highlight purple | Rift Lilac | `#A78BFA` | Focus rings, badges, glows, chart highlights |
| Accent | Ember Gold | `#F59E0B` | Rare emphasis, warnings, premium callouts |

## Dark Theme Palette

| Token | Hex | Use |
|---|---:|---|
| `--bg` | `#120D18` | App background |
| `--surface` | `#1C1428` | Cards and panels |
| `--surface-raised` | `#261A38` | Modals, dropdowns, elevated panels |
| `--border` | `#3A2A4D` | Dividers and card borders |
| `--text` | `#F5F1FF` | Primary text |
| `--text-muted` | `#B8A9CC` | Secondary text |
| `--primary` | `#4B2A7B` | Brand identity blocks |
| `--interactive` | `#7C3AED` | Buttons, links, active states |
| `--interactive-hover` | `#8B5CF6` | Hover state |
| `--focus` | `#A78BFA` | Focus ring |
| `--accent` | `#F59E0B` | Sparing highlight |

## Light Theme Palette

| Token | Hex | Use |
|---|---:|---|
| `--bg` | `#F8F5FC` | Page background |
| `--surface` | `#FFFFFF` | Cards and content blocks |
| `--surface-tint` | `#EEE7F7` | Soft sections, guide callouts |
| `--border` | `#D8CBE8` | Dividers and card borders |
| `--text` | `#17111F` | Primary text |
| `--text-muted` | `#5E536B` | Secondary text |
| `--primary` | `#4B2A7B` | Brand identity blocks |
| `--interactive` | `#6D28D9` | Buttons, links, active states |
| `--interactive-hover` | `#5B21B6` | Hover state |
| `--focus` | `#7C3AED` | Focus ring |
| `--accent` | `#B45309` | Light-mode accent text or badges |

## Contrast Notes

| Pair | Approx. Contrast Ratio | Verdict |
|---|---:|---|
| `#4B2A7B` on white | 10.96:1 | Strong |
| `#7C3AED` on white | 5.70:1 | Passes normal text |
| `#6D28D9` on white | 7.10:1 | Strong for light-mode CTAs |
| `#A78BFA` on `#17111F` | 6.79:1 | Strong on dark UI |
| `#F5F1FF` on `#17111F` | 16.64:1 | Excellent body contrast |
| `#5E536B` on `#F8F5FC` | 6.65:1 | Good muted text |

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
Best body/UI candidate from your list.

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

Use this as the v1 brand system:

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
6. Do not use Marmelad in the core kit unless you decide the brand should feel softer and more whimsical.

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
