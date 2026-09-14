# FORTUNA SIGNAL — Lovable build prompt

## Project directive

Create an **unpublished Lovable project** that reproduces the accepted FORTUNA-001 homepage design baseline. This is a polished, responsive editorial microsite preview for **FORTUNA SIGNAL**, not a live market product. Preserve LUNA’s accepted contribution: a standalone ivory evidence section that explains the analytical chain **Observation → Interpretation → Invalidation**.

Do not publish, connect a paid service, fabricate market activity, or add a live-data claim. Do not add an email signup in this version.

## Brand foundation

FORTUNA is the parent brand; SIGNAL is a descriptor. The visual character is an “emerald observatory”: composed, analytical, materially rich, and restrained.

Use these exact tokens:

```css
:root {
  --obsidian: #07120F;
  --deep-emerald: #073D32;
  --forest-surface: #0D241D;
  --antique-gold: #C6A76A;
  --warm-ivory: #F2EEE5;
  --sage: #A7BBB0;
  --signal-mint: #80DDB2;
  --amber: #F0C27A;
  --rose: #F2A39D;
  --focus: #B7DAD0;
  --font-display: Georgia, "Times New Roman", serif;
  --font-body: Arial, Helvetica, sans-serif;
  --font-data: ui-monospace, SFMono-Regular, Consolas, monospace;
  --radius-card: 8px;
  --radius-button: 6px;
}
```

Use an inferred supporting rule color of `#36584B` only for quiet borders and dividers. Keep the maximum content width at `1200px`.

Upload and use these supplied brand-kit files:

- `assets/fortuna-wordmark-ivory.svg` — masthead and footer wordmark
- `assets/fortuna-symbol-gold.svg` — optional small brand accent only
- `assets/emerald-mineral.svg` — hero texture
- `assets/favicon.svg` — browser icon
- `assets/social-card.svg` — social preview asset
- `assets/fortuna-tokens.css` — canonical CSS tokens
- `assets/tokens.json` — token reference

Do not redraw the wordmark as plain text. Display the supplied outlined ivory wordmark and set **SIGNAL** beside it in small uppercase gold monospace type.

## Visual rules

- Base page: obsidian background, warm-ivory text.
- Hero: deep emerald with `emerald-mineral.svg`, dark left-to-right overlay, restrained texture.
- Reading cards: solid forest surfaces with quiet borders; no glass effects.
- Gold: calls to action, small labels, and key dividers only.
- Ivory: one full-width evidence section and selected reading surfaces.
- Headlines: Georgia, regular weight, tight tracking.
- Body: Arial, 16–18px, generous line height.
- Metadata and labels: system monospace, uppercase, wide tracking.
- No glows, animated tickers, decorative coins, fabricated charts, flashing alerts, or unsupported performance claims.
- Motion, if any, must be subtle and nonessential. Honor reduced-motion preferences.

---

## Page structure and copy

### 1. Utility masthead

A compact top bar on obsidian with a thin antique-gold divider.

- Left: `DIGITAL MARKET INTELLIGENCE`
- Right navigation: `Signals`, `Narratives`, `Archive`, `About`
- All navigation items anchor to real page sections.
- Keep link targets at least 44px high on touch devices.

### 2. Hero

Use a two-column desktop composition over the mineral texture. The left column is editorial; the right column presents the method.

**Brand lockup**

- Supplied outlined ivory FORTUNA wordmark
- `SIGNAL` in small antique-gold monospace type

**Headline**

> A clearer view of emerging markets.

**Support**

> Sourced crypto news, emerging narratives, and a public record of what we’re watching—and how it develops.

**Actions**

- Primary: `Explore the signals` → `#signals`
- Secondary: `Read the latest brief` → `#featured`

**Method panel**

> A signal is a record, not a verdict.

1. Observe the change
2. Separate evidence from interpretation
3. Return when the evidence changes

Add a high-visibility gold strip immediately below the hero:

> HOMEPAGE PREVIEW · DEMO EDITORIAL CONCEPTS · NO LIVE MARKET DATA

### 3. Signal feed

Section ID: `signals`

- Kicker: `SIGNAL FEED / PREVIEW`
- Heading: `What we would investigate.`
- Intro: `A homepage concept for evidence-led reporting. Every item below is a design fixture—not published news, investment advice, or a live signal.`

Add keyboard-accessible filter buttons with clear pressed states:

- All concepts
- Infrastructure
- Tokenization
- Attention

The filter changes only the visible demo cards. Do not simulate loading or market updates.


Use a feature grid: one large lead card and two stacked supporting cards.

**Lead card — `#featured`**

- Labels: `DEMO · NO LIVE DATA` and `OBSERVATION FRAMEWORK`
- Headline: `When attention returns to a dormant narrative`
- Copy: `A research card separates an observed change from the explanation being tested—and states what would weaken the view.`
- Metadata: `Source required before publication`
- Link: `View signal anatomy →` → `#ledger`

**Supporting card 1**

- Labels: `DEMO` and `TOKENIZATION`
- Headline: `What would count as real-world adoption?`
- Copy: `A reporting brief would compare claims, settlement activity, access, and the limits of available evidence.`
- Metadata: `Status · Concept only`

**Supporting card 2**

- Labels: `DEMO` and `AI INFRASTRUCTURE`
- Headline: `Separating usage from narrative momentum`
- Copy: `A research path for testing whether attention is accompanied by measurable infrastructure demand.`
- Metadata: `Status · Concept only`

Every fixture card must visibly include a demo label. No card may imply that it is current, sourced, or actionable.

### 4. Standalone ivory evidence section — LUNA contribution

Section ID: `ledger`

This is a **standalone full-width section**, not a rail inside each signal card. Use a warm-ivory background with obsidian text and darker, accessible muted text.

- Kicker: `DISTINCTIVE IMPROVEMENT / EVIDENCE RAIL`
- Heading: `See how the view was formed.`
- Intro: `The evidence rail makes the analytical chain visible at a glance, so the reader can inspect a signal before accepting its interpretation.`

Use three equal columns on desktop and one stacked column on mobile:

1. `01 / OBSERVATION`
   - Heading: `What changed?`
   - Copy: `The published version names the source, unit, time range, and observation timestamp.`
2. `02 / INTERPRETATION`
   - Heading: `What might it mean?`
   - Copy: `Commentary stays distinct from sourced fact and includes the rationale behind confidence.`
3. `03 / INVALIDATION`
   - Heading: `What changes the view?`
   - Copy: `A clear condition tells readers when the thesis weakens, expires, or requires revision.`

Do not repeat this three-stage evidence rail inside the cards.

### 5. Narrative radar

Section ID: `narratives`

- Kicker: `NARRATIVE RADAR / DEMO`
- Heading: `Questions worth following.`
- Intro: `Themes are framed as open investigations, not predictions. Published collections would link every factual claim to its source.`

Create three equal solid cards on desktop and stack them on mobile:

1. `AI systems meet decentralized infrastructure`
   - `Which capabilities are operational—and which remain roadmap language?`
2. `Tokenization beyond the announcement cycle`
   - `Follow the gap between product launches, accessibility, and verifiable use.`
3. `Market structure under changing liquidity`
   - `Investigate the conditions that alter participation, concentration, and risk.`

Each card includes `DEMO TOPIC`, then a status row: `RESEARCH STATE` / `UNASSESSED`.

### 6. Signal archive

Section ID: `archive`

- Kicker: `SIGNAL ARCHIVE`
- Statement: `A public memory for what changed—and what did not.`

Add three ruled rows:

- `Observed` / `Original evidence remains visible` / `Recorded`
- `Revisited` / `Material changes receive a dated revision` / `Updated`
- `Resolved` / `Expired and invalidated views stay in the record` / `Preserved`

This communicates expected archive behavior only; it is not a live archive.


### 7. About

Section ID: `about`

- Kicker: `ABOUT`
- Heading: `Composed analysis for a fast-moving field.`
- Body: `FORTUNA is an AI-assisted publication examining the forces shaping digital markets. It connects market observations with technological and economic context, identifies what remains uncertain, and revisits ideas as evidence changes.`

Show three principles:

1. `Confident in the observation. Explicit about the uncertainty.`
2. `Sources, relevant disclosures, and revisions accompany each publication.`
3. `Signals are research observations—not promises of profitable trades.`

### 8. Footer

Use the supplied outlined ivory FORTUNA wordmark.

- Copy: `AI-assisted research and commentary. Sources, relevant disclosures, and revisions accompany each publication.`
- Signature: `AD ASTRA.`

Do not include an email field, newsletter module, signup CTA, or nonfunctional form anywhere in this version.

---

## Interaction behavior

- Smooth-scroll to anchors unless reduced motion is preferred.
- Filter controls use native buttons and update `aria-pressed`.
- Selected filter: warm-ivory fill with obsidian text.
- Every link and button has a visible keyboard focus outline using `#B7DAD0`.
- Hover states must remain restrained and preserve contrast.
- No external data fetch, authentication, backend, payments, analytics, or newsletter integration.
- No article-detail implementation is required in this homepage task.

## Responsive requirements

**Desktop, 1200px container**

- Page gutters: 48px minimum.
- Hero: editorial content at roughly 70%; method panel at 30%.
- Signal area: lead card at roughly 62%; supporting stack at 38%.
- Evidence section: three equal columns.
- Narratives: three equal cards.
- Archive and About: balanced two-column layouts.

**Tablet, below 860px**

- Page gutters: 24px.
- Hero, section heads, signal feature, archive, and About become single-column.
- Narrative cards may use two columns when space permits.
- Method panel moves below hero copy.

**Mobile, verify at 390px**

- Exactly 24px left and right gutters.
- No horizontal overflow.
- Wordmark lockup scales without clipping.
- Hero actions stack full width.
- All cards and narratives stack to one column.
- Evidence section stacks Observation, Interpretation, Invalidation in that order.
- Archive rows remain legible without horizontal scrolling.
- Minimum touch target: 44px.
- Body type: 16–18px; hero headline may use about 48px with a compact line height.

## Accessibility and semantic requirements

- Use semantic `header`, `nav`, `main`, `section`, `article`, and `footer` landmarks.
- Maintain one `h1`; use a logical heading hierarchy afterward.
- Add descriptive `alt` text to the FORTUNA wordmark. Treat mineral texture as decorative.
- Do not encode status or meaning by color alone.
- Keep all text at WCAG AA contrast or better on the rendered backgrounds.
- Provide keyboard operability for navigation and filters.
- Preserve visible focus, reduced-motion behavior, and readable zoomed layouts.
- Distinguish missing data from zero if data components are added later.

## Truth and demo-labeling rules

- All market-oriented content is fixture copy.
- Use `DEMO · NO LIVE DATA` on the lead signal and a persistent page-level demo strip.
- Use `DEMO` or `DEMO TOPIC` on every other market-content card.
- Do not invent prices, percentages, timestamps, source names, contract addresses, confidence scores, returns, or charts.
- Do not use urgency language, trade recommendations, or claims such as “smart money confirmed.”
- The archive, statuses, and filters are interface demonstrations only.
- Keep “record status” separate from future “freshness” metadata.

## Completion criteria

Before handing back the Lovable preview, confirm:

- The project remains unpublished.
- The supplied outlined wordmark appears in the masthead and footer.
- The emerald-mineral asset appears only as restrained hero texture.
- The ivory evidence rail is a standalone section, not embedded in cards.
- No email signup exists.
- Every market fixture is visibly demo-labeled.
- All navigation anchors, CTAs, and filters work.
- Desktop and 390px layouts have been visually checked.
- There is no horizontal overflow at 390px.
- Keyboard focus is visible, headings are semantic, and reduced motion is honored.
- No fabricated live signal, source, timestamp, metric, or performance claim appears.


---

## Compact layout specification

### Page map

| Order | Section | Desktop structure | Mobile structure |
|---:|---|---|---|
| 1 | Utility bar | Descriptor + nav | Wrapped compact nav |
| 2 | Hero | Copy 70% + method 30% | Single column |
| 3 | Demo strip | Full width | Full width |
| 4 | Signals | Feature + card stack | All stacked |
| 5 | Evidence rail | 3 ivory columns | 3 stacked rows |
| 6 | Narratives | 3 cards | 1 card per row |
| 7 | Archive | Statement + records | Single column |
| 8 | About | Heading + copy | Single column |
| 9 | Footer | Wordmark + signature | Stacked |

### Component rules

- **Container**: maximum 1200px; 48px desktop gutters; 24px mobile gutters.
- **Section spacing**: approximately 88px vertical desktop; 64px mobile.
- **Cards**: `#0D241D`, 1px quiet green border, 8px radius, no transparency.
- **Buttons**: 6px radius; gold primary, outlined-gold secondary; 44px minimum height.
- **Hero**: `#073D32` plus mineral SVG and dark overlay; no text-animation effects.
- **Evidence rail**: `#F2EEE5` surface, `#07120F` text, subtle ruled dividers.
- **Type scale**: hero 46–86px fluid; section headings 36–56px; card headings 24–52px by hierarchy; body 16–18px.
- **Metadata**: monospace, 10–12px, uppercase, wide tracking.
- **Borders**: low-emphasis green; antique gold only for emphasis.

### State model

- Filter states: default, hover, focus-visible, selected (`aria-pressed="true"`).
- Demo states: page-level demo strip plus per-card demo badge.
- Signal status examples: Concept only, Unassessed.
- Archive behavior examples: Recorded, Updated, Preserved.
- No loading, error, stale, or empty states are needed because this version has no live backend.

### Accepted baseline notes

- The **ivory evidence rail is one standalone section** between Signals and Narratives; it is not attached to each card.
- This version contains **no email signup**.
- Preserve the accepted emerald identity, outlined wordmark, filter interaction, editorial framing, and explicit demo disclosures.
- Keep the project unpublished until FORTUNA reviews the Lovable implementation.
