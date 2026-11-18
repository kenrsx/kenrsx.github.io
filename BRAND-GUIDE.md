# KEN. — Brand Identity & Content Creation System
**Version 2.1 // Swiss Minimalism Architecture**  
**Core Palette:** Cobalt Grey (`#191C1D`) · Ivory White (`#F5EEE9`) · Pumpkin Orange (`#FD6002`)  
**Handles:** Instagram `@kenrsx` · GitHub `kenrsx` · LinkedIn `kenzieee`

**Scope:** This is a style guide: colour, type, layout, and components. It does not dictate what a page says. For any web page on any topic, build from **Section 9** and do not invent new components. The reference implementation of these components is `index.html`.

---

## 0. READ THIS FIRST (Hard Rules for Any AI or Designer)

If you read nothing else, follow these. Each rule is a yes/no check.

**ALWAYS**
1. Use exactly three brand colors plus white and neutral greys: `#191C1D` cobalt, `#F5EEE9` ivory, `#FD6002` pumpkin, `#FFFFFF` for raised panels. Nothing else.
2. Put Ivory `#F5EEE9` on the page background. Never pure white as the page background.
3. Use Inter for headings and prose. Use JetBrains Mono for labels, tags, index numbers, buttons, metadata.
4. Write headings in UPPERCASE, Inter 800/900, letter-spacing `-0.04em`, line-height about `0.95`.
5. Use `border-radius: 0`. Separate things with 1px or 2px solid hairlines, never soft shadows.
6. Number every section with a pumpkin mono index (`01`, `02`, `03`) and a `[ 01 ]` style index on list rows.
7. Write in first person, dry and plain. Indonesian for human asides, English for technical nouns.
8. Build pages from the components in Section 9 before writing any new CSS.
9. Keep functional text at 11px (`0.7rem`) or larger. Keep body copy at 14px or larger.
10. Give every interactive element a visible focus state and a hover state.

**NEVER**
1. No gradients, glassmorphism, blurred cards, neon, glow, or emoji.
2. No border-radius above `2px`. No pill buttons. No rounded cards.
3. No soft drop-shadows. The only allowed shadow is the hard block shadow `4px 4px 0 #191C1D`.
4. No new accent colors: no blue, purple, green, teal, or red. Error and success states use cobalt text plus a pumpkin or cobalt rule, not new hues.
5. No exclamation marks, no "revolutionary", "supercharge", "unlock", "game-changer", "leverage", "seamless", "cutting-edge".
6. No pumpkin text for paragraphs or small text on ivory or white (fails contrast).
7. No stock photos, 3D mockups, or AI-generated avatars.
8. Do not write the name as "Ken", "KEN", "Kenzie" or "kenzie" in brand spots. Write **`KEN.`** (wordmark) or **`Ken.`** (prose) with the period.
9. Do not claim anything without a receipt: a live link, repo, screenshot, or number.
10. No decorative fitness, tech, or finance clichés: no glossy icons, flame or lightning graphics, or hero stock photos. Let type, grid, and real data carry the page.

---

## 1. Brand Foundations & Manifesto

### 1.1 Brand Identity at a Glance
| Attribute | Specification |
|---|---|
| **Primary Wordmark** | **`KEN.`** (Always written with the solid period or square block) |
| **Full Legal / Byline** | **Ahmad Kenzie Aryasatya** |
| **Subtitle / Track** | **AI-Human Collaboration × Accounting** |
| **Core Pitch** | *Accounting student by day, wrestling with AI by night. Helping people collaborate better with AI in their daily life.* |
| **Positioning** | **Receipts over hype.** One person, first-person singular, authentic working experiments. Shipped code, real ledgers, transparent workflows. |
| **Personality** | Dry, unhurried, quietly confident, analytical, self-aware. Never hyped, never preachy. |
| **Core Philosophy** | **Form follows function.** AI handles the repetitive grunt work; the human holds the steering wheel, judgment, and ethical oversight. |

### 1.2 Hierarchy of Precedence (When Rules Conflict)
1. **Clarity & Accessibility:** Contrast must pass WCAG AA standards. Content must be effortlessly readable.
2. **Swiss Grid & Structural Honesty:** Visible layout boundaries, geometric alignment, and deliberate whitespace.
3. **The 3-Color Discipline:** Restrained distribution (Ivory canvas, Cobalt structure, Pumpkin punctum).
4. **Voice & Plain Language:** No marketing jargon or unproven hype.

---

## 2. The Color System (The Tri-Color Rule)

The brand is anchored strictly by three colors. No third accent color (no purple, cyan, blue, or green) is permitted for brand identity.

```
┌────────────────────────────────────────────────────────────────────────┐
│                                                                        │
│   IVORY WHITE           COBALT GREY              PUMPKIN ORANGE        │
│   #F5EEE9               #191C1D                  #FD6002               │
│   Primary Canvas        Typography & Rules       Signature Punctum     │
│   RGB: 245, 238, 233    RGB: 25, 28, 29          RGB: 253, 96, 2       │
│   CMYK: 0, 3, 5, 4      CMYK: 14, 3, 0, 89       CMYK: 0, 62, 99, 1    │
│   Pantone: Warm Gray 1C Pantone: Black 6C        Pantone: 1585 C       │
│                                                                        │
└────────────────────────────────────────────────────────────────────────┘
```

### 2.1 Color Tokens & Roles

| Token | Hex | Role & Application | Usage Ratio |
|---|---|---|---|
| **Ivory White** | `#F5EEE9` | **The Canvas:** Page background, slide canvases, carousel backgrounds, document paper stock. It replaces sterile digital `#ffffff` with a warm, tactile editorial feel. | **~70%** |
| **Cobalt Grey** | `#191C1D` | **Structure & Text:** Inky black-slate used for all primary headlines, body text, 1px/2px hairline borders, frames, and dark pill tags. | **~22%** |
| **Pumpkin Orange** | `#FD6002` | **The Punctum (Accent):** The brand dot, focal buttons, index numbers (`[ 01 ]`), key emphasis words, hover highlights, and diagram decision nodes. | **~5–8%** |
| **Surface White** | `#FFFFFF` | **Elevated Panels Only:** Inset cards, form inputs, or code box backgrounds that sit on top of the Ivory canvas. | Secondary |

### 2.1a Supporting Tokens (Used by the Site, Allowed)
These are tints and states of the three brand colors, not new colors.

| Token | Value | Use |
|---|---|---|
| `--c-pumpkin-dark` | `#d84e00` | Pumpkin text on hover over ivory or white (better contrast than `#FD6002`) |
| Pumpkin hover fill | `#ff6e1a` | Button hover background only |
| Row hover wash | `#fff9f5` | Background of a hovered list row |
| `--c-border` | `rgba(25, 28, 29, 0.16)` | Light hairlines between rows |
| Body grey | `#434b4f`, `#3b4245` | Secondary prose on white or ivory |
| Ivory-on-cobalt greys | `#d1cbc5`, `#e4ddd6`, `#a49c95` | Secondary text on cobalt backgrounds |

### 2.2 The Pumpkin Orange Budget
Pumpkin Orange is high-voltage visual energy. If everything is orange, nothing is.
* **Max 1–2 focal elements per screen / carousel slide / slide deck layout.**
* Examples of proper usage: One button, or one oversized index numeral (`01`), or one key highlight box.
* **Exempt from the count (structural markers):** the small mono index numbers on section headers and list rows (`02`, `[ 01 ]`), the brand dot, and link text on cobalt backgrounds. They are small and repeated by design.
* Never use Pumpkin Orange for long-form body copy (fails reading contrast).
* Pumpkin text on ivory or white is only for large or bold mono index numbers (about 17px bold and up). For smaller text on light backgrounds use cobalt, or `#d84e00` on hover. On cobalt backgrounds, pumpkin text is fine at any size.

---

## 3. Typography & Typesetting

The typographic system blends aggressive Swiss grotesque sans-serif with technical monospaced documentation.

### 3.1 Primary Typeface: Inter
Used for all display headings, subheadings, and body prose.
* **Weights:** `900` (Black), `800` (Extra Bold), `700` (Bold), `500` (Medium), `400` (Regular).
* **Display Headlines:** Uppercase, weight `800` or `900`, tight tracking (`-0.035em` to `-0.05em`), line-height `0.92–1.0`.
* **Sub-headlines:** Sentence case, weight `500`, tracking `-0.015em`, line-height `1.35–1.45`.
* **Body Copy:** Sentence case, weight `400`, max column width ~580px, line-height `1.55–1.65`.

### 3.2 Technical Typeface: JetBrains Mono
Used for structural labels, index tags, dates, coordinates, code receipts, and diagram annotations.
* **Weights:** `700` (Bold), `500` (Medium), `400` (Regular).
* **Format:** Monospace, uppercase micro-labels (`FIG 01.0 // MANIFESTO`, `[ 01 / 08 ]`, `SOURCE: GITHUB`).
* **Minimum size:** `0.7rem` (11.2px) for any text a person reads or clicks. Never go below this.

### 3.3 System Fallbacks
* Sans Fallback: `Helvetica Neue, Arial, -apple-system, sans-serif`
* Mono Fallback: `SFMono-Regular, Consolas, Monaco, monospace`

---

## 4. Swiss Minimalist Graphic Grammar

Every visual artifact created under the Ken. brand must obey these geometric rules:

1. **The Structural Hairline:** Sections, containers, and blocks are separated by razor-sharp `1px` or `2px` solid hairlines (`#191C1D` or `rgba(25, 28, 29, 0.16)`). Never use blurred drop-shadow cards to create separation.
2. **Zero or Minimal Border Radius:** Sharp right angles (`0px` border radius) are preferred for architectural purity. Buttons and cards use a maximum border-radius of `0px` to `2px`.
3. **Tactile Block Shadows:** If elevation is needed on interactive elements (e.g., buttons, key callout frames), use a hard 1-bit drop shadow:
   ```css
   box-shadow: 4px 4px 0px #191C1D;
   ```
4. **Index Markers & Micro-Coordinates:** Every section or slide gets an index tag:
   * `[ 01 / INTRODUCTION ]`
   * `FIG 02.1 // ACCOUNTING AUTOMATION WORKFLOW`
   * `STATUS // SHIPPED & VERIFIED`
5. **No AI-Slop Graphics:**
   * **FORBIDDEN:** Floating neon gradient orbs, cyan-purple cyberpunk mesh, generic 3D glossy icons, glassmorphism blur cards, stock photos of smiling people pointing at holographic charts.
   * **REQUIRED:** Clear typography, raw terminal/code snippets, actual spreadsheet screenshots with tight 1px borders, candid low-saturation photography, and minimal 2D vector diagrams.

---

## 5. Multi-Channel Content Creation Guide

Use this section to create content for platforms beyond the website.

```
┌────────────────────────────────────────────────────────────────────────┐
│                        CONTENT CREATION MATRIX                         │
├─────────────────────┬───────────────────┬──────────────────────────────┤
│ Channel / Format    │ Canvas Background │ Typography & Focal Accent    │
├─────────────────────┼───────────────────┼──────────────────────────────┤
│ IG Carousel (4:5)   │ Ivory (#F5EEE9)   │ Inter 900 + Pumpkin tag      │
│ IG Reel / Short     │ Ivory or Dark     │ Raw screen capture + 2px box │
│ Slide Deck (16:9)   │ Ivory (#F5EEE9)   │ Large Pumpkin numerals 01-05 │
│ LinkedIn Post       │ Pure Text / Doc   │ Numbered list + code receipt │
│ GitHub / Tech Docs  │ Markdown / Dark   │ Plain Inter + JetBrains Mono │
│ Print / Workshop    │ Uncoated Offwhite │ Screen-printed Pumpkin #FD60 │
└─────────────────────┴───────────────────┴──────────────────────────────┘
```

---

### 5.1 Instagram Carousels (1080 × 1350 px — 4:5 Ratio)

Carousels are the primary educational vehicle. They must read like an editorial Swiss design booklet.

#### Slide Anatomy
* **Margins:** 80px safe zone on all edges.
* **Top Header Strip:**
  * Left: `KEN.` or `KEN | AI & ACCOUNTING`
  * Right: Slide coordinate e.g. `[ 01 / 07 ]` in JetBrains Mono.
* **Top/Bottom Hairlines:** 1px Cobalt Grey rule line framing the content.
* **Slide 1 (The Hook):**
  * Massive typography (80–110pt): Inter 900 uppercase.
  * One punchy statement. Highlight 1–2 words with a solid Pumpkin Orange tag box.
  * Subtitle in 24pt Inter Medium (max 2 lines).
  * Bottom indicator: `SWIPE FOR RECEIPTS →`
* **Slides 2–6 (The Value & Receipts):**
  * Maximum 35–50 words per slide. Generous white space.
  * Numbered points: `01.`, `02.`, `03.` set in JetBrains Mono Bold with Pumpkin Orange color.
  * Real screenshots: When showing an Excel sheet, Python script, or AI output, crop tight with a 2px Cobalt Grey border. Never add artificial drop shadows or fake 3D perspective tilts.
* **Slide 7 (The Action / Colophon):**
  * Clear next step: `[ 03 / COLLABORATE HERE ]`
  * Bio sign-off: *"Mahasiswa akuntansi by day, wrestling with AI by night."*
  * Handle: `@kenrsx` with direct CTA: *"Tulis idemu di link bio / DM."*

---

### 5.2 Short-Form Video & Reels (1080 × 1920 px — 9:16 Ratio)

* **Hook Style (0–3 seconds):** Direct to camera or direct to screen showing the finished working outcome (the receipt). No slow cinematic intros, no spinning logo animations.
* **On-Screen Text & Captions:**
  * Background pill: Solid Ivory White (`#F5EEE9`) with 2px Cobalt Grey border.
  * Text: Inter 800 uppercase in Cobalt Grey (`#191C1D`).
  * Keywords highlighted in Pumpkin Orange background tags.
* **Code & Spreadsheet Display:**
  * Screen-recordings should be clean, high-contrast, at 100% zoom.
  * Terminal theme: Cobalt Dark (`#191C1D`) background with Ivory text and Pumpkin Orange prompt cursor.

---

### 5.3 Presentation Decks & Workshops (1920 × 1080 px — 16:9 Ratio)

* **Canvas:** Solid Ivory White (`#F5EEE9`). No gradient fills.
* **Title Slide:**
  * Large display typography: `AI-HUMAN COLLABORATION` (Inter 900).
  * Presenter line: `KEN. // AHMAD KENZIE ARYASATYA`
  * Corner metadata: Date, edition, and version tag in mono.
* **Section Dividers:**
  * Solid Cobalt Grey (`#191C1D`) background slide.
  * Massive numeral: `01`, `02`, `03` in Pumpkin Orange (`#FD6002`).
  * Section title in Ivory White.
* **Data & Table Slides:**
  * Use strict tabular layouts with horizontal hairlines.
  * Highlight key metrics (e.g. time saved, error rates, reconciliation accuracy) with Pumpkin Orange bold text.

---

### 5.4 LinkedIn, X / Threads & Technical Writing

* **Formatting Text:**
  * Use square brackets for categories: `[ AI × ACCOUNTING ]`, `[ EXPERIMENT 04 ]`.
  * Break paragraphs every 1–2 sentences. Dense walls of text violate the principle of generous whitespace.
* **Quote / Code Cards:**
  * Use monospace code blocks for prompts and scripts.
  * Frame diagrams with ASCII or clean 2D vector flowchart boxes.

---

## 6. Voice, Tone & Copywriting Engine

### 6.1 The Bilingual Rule (Indonesian & English Code-Switching)
Ken writes and speaks the way Indonesian tech/finance practitioners naturally communicate:
* **Indonesian for human connection, empathy, and relatable asides:**
  * *"Saya uji coba sendiri jam dua pagi..."*
  * *"AI bukan buat gantiin otak kita, tapi buat buang kerjaan kuli-nya."*
  * *"Kalau kodenya mau diintip, link-nya ada di bawah."*
* **English for technical nouns, tools, and industry terms:**
  * Use `prompt chaining`, `reconciliation`, `ledger`, `fine-tuning`, `zero-shot`, `pipeline`, `receipts`.
  * Do not force awkward Indonesian translations for standard industry terms (e.g. avoid *"rantai bisikan"* for prompt chain).

### 6.2 Tone Spectrum
| Tone Attribute | What It Sounds Like | What It NEVER Sounds Like |
|---|---|---|
| **Dry & Pragmatic** | *"It works. Mostly. Di data 1,000 baris masih ada 3 error, ini cara saya fix."* | *"Solusi revolusioner 100% tanpa cela!"* |
| **Receipts-Backed** | *"Ini kodenya, ini screenshot Google Sheets-nya, ini prompt-nya."* | *"Rahasia sukses para ahli AI yang disembunyikan!"* |
| **Quietly Confident** | *"Kalau butuh alur automasi seperti ini, saya bisa bantu buatkan."* | *"SIAP MELEDAKKAN OMZET ANDA SEKARANG JUGA!!!"* |
| **Humble Yet Skilled** | *"Masih belajar akuntansi, tapi malamnya suka ngulik model AI."* | *"Top 1% AI Visionary Thought Leader."* |

### 6.3 Copywriting Formula for Posts & Articles
Every content piece should follow the **4-Step Swiss Structural Sequence**:
1. **The Friction:** Identify an everyday annoying, manual task (e.g., *"Input 80 faktur pajak manual itu buang waktu 3 jam."*).
2. **The Mechanism:** Show the exact tool or prompt workflow used to tackle it (without gatekeeping).
3. **The Receipt:** Share the code snippet, accuracy metric, or actual before/after.
4. **The Invitation:** A clean, un-hyped CTA (e.g., *"Ada alur kerja serupa di kantormu? Titip permintaan di bio / DM."*).

---

## 7. Imagery & Photography Art Direction

* **Profile & Portrait Photos:**
  * Natural lighting, relaxed but focused posture.
  * Desaturated color grading with realistic skin tones.
  * Framed in a solid 2px Cobalt Grey box with an Ivory White 4px inner border.
  * Never use hyper-stylized AI face avatars, airbrushed studio glamor, or corporate stock smiles.
* **Screenshots & Deliverables:**
  * Always crisp 1:1 pixel rendering.
  * Framed with a 1px solid hairline (`#e6ded7` or `#191C1D`).
  * Never place screenshots inside generic 3D floating laptop/phone mockups. Show the raw software interface honestly.

---

## 8. Summary Checklist Before Publishing Content

Before hitting publish on a website page, Instagram post, presentation slide, or technical document, verify:

- [ ] **Palette Check:** Are you using ONLY Cobalt Grey (`#191C1D`), Ivory White (`#F5EEE9`), and Pumpkin Orange (`#FD6002`)?
- [ ] **Orange Budget:** Is Pumpkin Orange restricted to 1–2 focal elements, occupying less than 8% of the surface?
- [ ] **Typography Check:** Is the headline bold Inter uppercase? Are metadata and tags set in JetBrains Mono?
- [ ] **Structural Honesty:** Are section dividers clean hairlines? Did you remove all rounded floating drop-shadow cards?
- [ ] **Voice Check:** Is it written in first-person? Did you remove exclamation points, buzzwords, and marketing fluff?
- [ ] **The Receipt Test:** Does the content deliver real value or actionable code/methods, rather than just abstract opinion?
- [ ] **Website only:** Did you build from the Section 9 components, number each section, and give every control hover and focus states?

---

## 9. Web Style Kit (Layout, Elements, Components)

A reusable kit for building any web page in this style, whatever the topic (portfolio, sports, tools, shop). It describes how things look and are built, never what a page should say. Stack: static HTML and modern CSS, vanilla JS only where needed. No UI framework, no CSS library. Icons are optional and small (Bootstrap Icons for arrows and tiny badges only).

### 9.1 Tokens (put these in `:root` first)
```css
:root {
  --c-cobalt: #191C1D;  --c-ivory: #F5EEE9;  --c-pumpkin: #FD6002;
  --c-pumpkin-dark: #d84e00;
  --c-border: rgba(25, 28, 29, 0.16);
  --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mono: 'JetBrains Mono', ui-monospace, SFMono-Regular, monospace;
  --grid-max: 1240px;
  --ease: cubic-bezier(0.16, 1, 0.3, 1);
}
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html, body { background: var(--c-ivory); color: var(--c-cobalt); }
body { font-family: var(--font-sans); font-size: 16px; line-height: 1.5; -webkit-font-smoothing: antialiased; }
h1, h2, h3, h4 { font-weight: 800; letter-spacing: -0.04em; line-height: 0.95; text-transform: uppercase; }
```
Fonts: Inter 400–900 and JetBrains Mono 400–700 from Google Fonts.

### 9.2 Layout system
* **Container:** `max-width: 1240px; margin: 0 auto; padding-inline: clamp(1rem, 4vw, 2.5rem);`
* **Vertical rhythm:** section top padding `clamp(3rem, 6vw, 4.5rem)`, bottom padding `clamp(3rem, 6vw, 5rem)`. Gaps inside blocks: `1rem`, `1.5rem`, `2rem`, `3rem`.
* **Grid, not floats:** use CSS Grid with visible borders as the structure. Cells are divided by 2px cobalt rules (major) or 1px `--c-border` rules (minor).
* **Mobile first.** One column by default. Breakpoints: `600px` (two-col form fields), `768px` (3-up blocks, footer columns), `860px` (list rows go multi-column), `960px` (hero and split panels).
* **Section rhythm:** each section is a header row, then one bordered block (table, grid, or panel). Sections stack with no decorative dividers other than the header rule.
* **Hero pattern:** a 2px cobalt bottom rule, a mono meta bar above (1px hairline under it), a huge uppercase headline on the left (`clamp(3rem, 7.5vw, 6.2rem)`, weight 900, line-height 0.92), supporting sidebar frame on the right from 960px.
* **Section index:** every section opens with a header row: a pumpkin mono numeral (`clamp(2rem, 4vw, 3rem)`, weight 900), the section title (`clamp(1.8rem, 3.5vw, 2.75rem)`), and a mono micro-label pushed to the right. A 2px cobalt rule closes the row. Numbers run `01`, `02`, `03` in page order.

### 9.3 Element specs
**Borders and surfaces**
* Major frame: `2px solid #191C1D`, background `#FFFFFF`, radius `0`.
* Inner divider: `1px solid rgba(25,28,29,0.16)` between rows, `1px solid #191C1D` between tightly packed cells.
* Dark block: background `#191C1D`, text `#F5EEE9`, secondary text `#d1cbc5`, headings ivory, links pumpkin mono bold.
* Allowed shadow: `4px 4px 0 #191C1D` on buttons and focused inputs only.

**Buttons**
```css
.btn {
  display: inline-flex; align-items: center; justify-content: center; gap: 10px;
  background: var(--c-pumpkin); color: var(--c-cobalt);
  border: 2px solid var(--c-cobalt);
  font: 800 0.95rem var(--font-mono); letter-spacing: 0.05em; text-transform: uppercase;
  padding: 14px 28px; box-shadow: 4px 4px 0 var(--c-cobalt); cursor: pointer;
  transition: all 0.12s var(--ease);
}
.btn:hover  { transform: translate(-2px, -2px); box-shadow: 6px 6px 0 var(--c-cobalt); background: #ff6e1a; }
.btn:active { transform: translate(2px, 2px);   box-shadow: 2px 2px 0 var(--c-cobalt); }
```
Button labels are mono, uppercase, at least 16px bold-ish (0.95rem minimum), and end with an arrow when they navigate (`LABEL →`). One primary button per view. A secondary action is a plain mono text link in brackets: `[ LABEL → ]`.

**Tags and badges:** mono, `0.7rem` minimum, uppercase, 0.06em tracking, `padding: 3px 8px`, `1px solid cobalt`, transparent background. Variants: pumpkin fill (cobalt text) and cobalt fill (ivory text). Radius 0.

**Labels and metadata:** mono `0.75rem`, weight 600, uppercase, 0.08em tracking. Bracket pattern for categories and indexes: `[ 01 ]`, `[ CATEGORY ]`, `FIG 02 // TITLE`, `STATUS // VALUE`.

**Form fields**
* Label: mono `0.75rem`, weight 800, uppercase, 0.08em tracking, 6px above the field.
* Input, select, textarea: full width, white background, `2px solid cobalt`, radius 0, mono `0.95rem`, padding `12px 14px`, no default outline.
* Focus: border turns pumpkin and adds `4px 4px 0 cobalt`. Never use a glow ring.
* Field rows have `1.5rem` bottom margin. Two fields share a row from 600px.

**Navigation bar:** sticky top, 64px tall, ivory at 94% opacity with `backdrop-filter: blur(12px)`, 2px cobalt bottom rule. Three zones in a grid (`auto 1fr auto`): wordmark block, mono meta text (hidden on small screens), actions. This is the only place a blur is allowed.

**Wordmark:** cobalt block, pumpkin or ivory text, mono or Inter 900, ending in the square brand dot.

**Segmented switch (2 to 3 options, like a language or view toggle):** a 2px cobalt bordered strip of mono `0.75rem` buttons, active one filled cobalt with ivory text.

**Icon strip (links to socials or channels):** a 3-column grid inside a 2px cobalt border with white background, 1px cobalt dividers, each cell has a tiny mono number on top and a mono uppercase label under it. Hover fills the cell pumpkin.

### 9.4 Component patterns

**Index list (the main list pattern)**
A bordered table where every item is one full-width row link. Use it for any list of things: items, results, workouts, products, articles.
* Container: `2px solid cobalt`, white background, flex column.
* Row: grid, padding `1.5rem 1.75rem`, `1px solid var(--c-border)` bottom, cobalt text, no underline. From 860px the columns are `80px 1.4fr 1.6fr 160px` with `1.5rem` gap and centered alignment. Under 860px it is a single column.
* Column 1: index `[ 01 ]` in pumpkin mono 800, 1.1rem, zero-padded.
* Column 2: name (1.15rem, 800, `-0.02em`) with an optional small arrow icon, and a tag under it.
* Column 3: one plain sentence, `0.925rem`, colour `#434b4f`, line-height 1.45.
* Column 4: mono `0.78rem` facts, right-aligned on desktop, wrapping with 12px gaps.
* Hover (built in, do not alter): background `#fff9f5`, 6px pumpkin left border (subtract 6px from the left padding so text does not shift), name colour `#d84e00`.
* Footer bar under the list: cobalt background, ivory mono `0.75rem` uppercase text, 0.05em tracking, padding `12px 1.75rem`. Left side states the source or note. Right side is one pumpkin bold link in `[ BRACKETS → ]`.

**Three-up statement block (pillars)**
One frame (`2px` cobalt, white) split into 3 equal columns from 768px, stacked below it. Columns are divided by 2px cobalt rules. Each cell has padding `2rem 1.75rem`: pumpkin mono numeral (1.25rem, 800), uppercase title (1.2rem, 800), body copy `0.95rem` in `#3b4245`.

**Framed panel with header strip**
A white frame with `2px` cobalt border. On top, a cobalt strip (`padding: 6px 12px`, ivory mono `0.7rem`, bold) holding a label. Body padding is generous (about 1.25rem). Use it for profile cards, summaries, spec sheets, stat boxes.

**Split panel (dark side + white side)**
A 2px cobalt bordered grid, `1fr 1.5fr` from 960px. Left is a dark block with a large ivory uppercase heading (2rem), muted paragraph, and optionally a quote box. Right is a white block with a form or content. They share a 2px rule between them.

**Quote or callout box:** `border-left: 3px solid pumpkin; padding-left: 1rem;` mono `0.85rem`, light text on a dark block. This 3px bar is a callout style. Do not use it as a general card accent.

**Strip of info on dark:** `1px` ivory-at-25% border, 1rem padding, ivory-at-4% background, pumpkin mono links.

**Data table:** header row in mono uppercase on a cobalt strip, body rows with 1px `--c-border` rules, numbers in mono and right-aligned, key figures in bold (pumpkin only for the single most important number, at large size).

**Footer (colophon):** cobalt background, `3.5rem` top and `2.5rem` bottom padding, 3 columns from 768px (`1.4fr 1fr 1fr`). Column headings are pumpkin mono `0.8rem`, uppercase, 0.1em tracking. Links and text are `#d1cbc5`. A bottom bar sits under a 1px ivory-at-16% rule with mono `0.75rem` text in `#a49c95`.

### 9.5 States and feedback
* **Hover:** buttons lift (translate -2px, shadow grows). Rows and cells get a wash or pumpkin fill. Never scale, glow, or fade.
* **Active:** buttons press in (translate +2px, shadow shrinks).
* **Focus-visible:** every interactive element needs a visible focus state. Use a 2px pumpkin outline with 2px offset on links and buttons, and the field focus style above on inputs.
* **Empty, loading, error:** a bordered row with a mono label (`[ NO DATA ]`, `[ LOADING ]`, `[ ERROR ]`) and one plain sentence. No spinners with colour, no red.
* **Disabled:** 40% opacity, no shadow, `not-allowed` cursor.

### 9.6 Motion
Short and functional. Hover and press transitions run `0.12s` to `0.15s`. No scroll-triggered animation, parallax, autoplay, bouncing, or looping decoration. Respect `prefers-reduced-motion` by removing transforms.

### 9.7 Accessibility baseline
* Contrast passes WCAG AA: 4.5:1 for body, 3:1 for large text. Pumpkin text only on cobalt, or as large bold numerals on light backgrounds.
* Text floor: 11.2px (`0.7rem`) for anything functional, 14px or more for reading copy.
* Semantic landmarks (`header`, `nav`, `main`, `section`, `footer`), logical heading order, keyboard-reachable controls, visible focus.
* `rel="noopener"` on every `target="_blank"` link. Set `lang` on `<html>`.

### 9.8 Building a new page, checklist
1. Start with the tokens and base rules in 9.1.
2. Lay out with the container, section header row, and one bordered block per section (9.2).
3. Build every element from the specs in 9.3 and 9.4. Reuse these patterns before making a new one.
4. If you must invent a component, it follows Section 4: hairlines, radius 0, hard shadow only, mono labels, tokens only.
5. Check states (9.5), motion (9.6), accessibility (9.7).
6. Run the Section 8 checklist.
