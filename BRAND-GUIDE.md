# KEN. — Brand Identity & Content Creation System
**Version 2.0 // Swiss Minimalism Architecture**  
**Core Palette:** Cobalt Grey (`#191C1D`) · Ivory White (`#F5EEE9`) · Pumpkin Orange (`#FD6002`)  
**Handles:** Instagram `@kenrsx` · GitHub `kenrsx` · LinkedIn `kenzieee`

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

### 2.2 The Pumpkin Orange Budget
Pumpkin Orange is high-voltage visual energy. If everything is orange, nothing is.
* **Max 1–2 focal elements per screen / carousel slide / slide deck layout.**
* Examples of proper usage: One button, or one oversized index numeral (`01`), or one key highlight box.
* Never use Pumpkin Orange for long-form body copy (fails reading contrast).

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
  * Clear next step: `[ 02 / COLLABORATE HERE ]`
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
