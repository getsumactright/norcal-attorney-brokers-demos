---
name: NorCal Legal Brokerage Dossier
colors:
  surface: '#f7f9fc'
  surface-dim: '#d8dadd'
  surface-bright: '#f7f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f7'
  surface-container: '#eceef1'
  surface-container-high: '#e6e8eb'
  surface-container-highest: '#e0e3e6'
  on-surface: '#191c1e'
  on-surface-variant: '#43474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f4'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#476080'
  primary: '#00152c'
  on-primary: '#ffffff'
  primary-container: '#0e2a47'
  on-primary-container: '#7992b4'
  inverse-primary: '#afc8ed'
  secondary: '#b51d04'
  on-secondary: '#ffffff'
  secondary-container: '#d9381e'
  on-secondary-container: '#fffbff'
  tertiary: '#091525'
  on-tertiary: '#ffffff'
  tertiary-container: '#1e293a'
  on-tertiary-container: '#8590a5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#afc8ed'
  on-primary-fixed: '#001c38'
  on-primary-fixed-variant: '#2f4867'
  secondary-fixed: '#ffdad3'
  secondary-fixed-dim: '#ffb4a6'
  on-secondary-fixed: '#3f0300'
  on-secondary-fixed-variant: '#8f1100'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7f9fc'
  on-background: '#191c1e'
  surface-variant: '#e0e3e6'
typography:
  headline-xl:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
  headline-xl-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  headline-lg:
    fontFamily: Syne
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
  headline-sm:
    fontFamily: Syne
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
  label-telemetry:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
spacing:
  gutter: 0px
  gutter-desktop: 0px
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system embodies the calculated precision of Northern California dual-licensed attorney-broker practice across Sacramento and Elk Grove. The visual voice fuses the rigorous discipline of Swiss architectural drafting with the uncompromising authority of judicial briefs and transactional escrow dossiers.

The aesthetic avoids decorative ornamentation in favor of structural clarity, high information density, exposed construction grids, and clinical typographic order. Visual authority stems from meticulous alignment, deliberate tabular formatting, and razor-sharp contrast between drafting paper surfaces, judicial cobalt anchors, and signal vermilion functional interventions. The interface evokes unassailable legal competence, institutional credibility, and transaction confidence.

## Colors
The palette operates with strict functional hierarchy derived from technical blueprints and legal proceedings:

- **Judicial Cobalt Navy (`#0E2A47`)**: Primary authority color. Applied to critical mastheads, section headers, active primary controls, and institutional anchoring blocks.
- **Signal Vermilion (`#D9381E`)**: High-contrast action color. Reserved strictly for vital statutory alerts, urgent dossier triage toggles, closing deadline timestamps, and active conversion buttons.
- **Slate Ink (`#4A5568`)**: Functional tertiary neutral. Designated for body prose, explanatory legal footnotes, and secondary telemetry metadata.
- **Crisp Architectural Paper (`#F4F6F9`)**: Canvas base neutral. Provides a cool, tinted drafting surface that prevents screen glare while grounding layout modules.
- **Pure White (`#FFFFFF`)**: Dossier cell fills, document cards, and focused input canvas backgrounds.
- **Hairline Rule (`#CFD6E0`)**: Structural frame line color used uniformly for all 1px architectural grid divisions and data cells.

## Typography
Typography is structured around three distinct type roles:

1. **Display & Section Anchors (Syne)**: Structural, geometric, and unapologetic. Syne brings sculptural weight to judicial hero statements and architectural sector headings, emphasizing modern NorCal development and firm prestige.
2. **Body & Case Text (Inter)**: Utilitarian and legible. Optimized for reading transactional agreements, statutory summaries, property conveyance notes, and client intake guidance.
3. **Statutory & Telemetry Notation (JetBrains Mono)**: Mechanical, monospaced accuracy. Used for CalDRE license IDs, State Bar member serials, APN coordinates, escrow file markers, micro indices, and timestamped intake logs. Always rendered with crisp kerning and optical alignment.

## Layout & Spacing
The layout follows a modular Swiss grid model utilizing collapsing borders. Rather than conventional floating cards separated by gutters, components lock flush against one another sharing a unified `1px solid #CFD6E0` frame line.

- **Grid Architecture**: 12-column desktop framework anchored inside a max-width bounds of 1440px. Grid cells touch with `0px` gutter gaps, defining separation purely via internal padding and hairline borders.
- **Density**: High-density dossier composition. Information is arranged in contiguous rows, ledger tables, and tabular matrix units.
- **Responsive Adaptations**:
  - **Desktop (>=1024px)**: Full multi-column matrix with split matter-triage views, side-by-side attorney-broker credential ledgers, and property conveyance indices.
  - **Tablet (768px - 1023px)**: Reflow to 6 columns; side dossiers stack below primary case overviews while retaining identical hairline containment borders.
  - **Mobile (<768px)**: Single-column linear dossiers; tabular indices gain horizontal overflow scrolling with fixed identifier labels.

## Elevation & Depth
This design system rejects dropshadows, diffused blurs, and pseudo-skeuomorphic layering. Depth is communicated strictly through planar borders, tonal contrast, and optical nesting:

- **Surface Tiers**:
  - `Base`: Architectural Paper (`#F4F6F9`) forms the canvas substrate.
  - `Cell / Panel`: Pure White (`#FFFFFF`) surfaces rise through flat contrast against the substrate.
  - `Anchor`: Judicial Cobalt Navy (`#0E2A47`) solid blocks produce visual gravity for index headers and primary terminal points.
- **Separation Technique**: All structural division is established by `1px solid #CFD6E0` hairlines. When elements receive focus or an active selection state, the border transforms to `1px solid #0E2A47` or `1px solid #D9381E` without shifting dimensions.
- **No Cast Shadows**: No `box-shadow` styles are permitted, maintaining the flat integrity of an architectural schematic or official legal pleading.

## Shapes
The shape language is strictly architectural and squared (`roundedness: 0`). Elements operate with right angles, flush edge alignments, and crisp planar containment.

- Standard buttons, input envelopes, data badges, and content blocks possess `0px` border-radius to reinforce the blueprint and legal dossier motif.
- Sub-elements requiring tactile distinction (e.g., interactive chips or specialized micro-pills) must not exceed `2px` corner softening, preserving structural geometry throughout.

## Components

### Buttons & Action Controls
- **Primary CTA**: Solid Judicial Cobalt Navy (`#0E2A47`) background, Pure White text, `0px` radius, uppercase tracking, monospaced prefix indicators (e.g., `[EXECUTE]`). Hover swaps background to Signal Vermilion (`#D9381E`).
- **Urgent / Matter Filing CTA**: Signal Vermilion (`#D9381E`) background, Pure White text, `0px` radius, JetBrains Mono typography for high-stakes filings and urgent consultation requests.
- **Secondary Grid Button**: Pure White background, `1px solid #CFD6E0` border, Judicial Cobalt Navy text. Hover applies `#F4F6F9` fill with an interior `1px solid #0E2A47` border lock.

### Dossier Data Tables & Index Lists
- Hairline-separated cells with no gaps.
- Table headers use Judicial Cobalt Navy (`#0E2A47`) or Paper (`#F4F6F9`) with monospaced metadata identifiers in `label-telemetry`.
- Numerical values, APN identifiers, case reference codes, and legal statues align strictly right in JetBrains Mono.

### Interactive Matter Triage Desk
- Segmented matrix panels allowing clients to categorize their case between Brokerage Acquisition, Escrow Dispute, Probate Real Estate, or Zoning Advocacy.
- Unselected states use Pure White cards with `#CFD6E0` outer borders; selected states trigger a solid `2px solid #0E2A47` inner outline and a Signal Vermilion corner notch.

### Input Fields & Legal Forms
- Pure White background framed in `1px solid #CFD6E0`.
- Top-aligned micro-labels in JetBrains Mono (`label-telemetry`) styled with Slate Ink (`#4A5568`).
- Active focus state: border shifts to `1px solid #0E2A47` with zero halo or glow effects.

### Status Indicators & Credential Badges
- Squared tags with `1px solid #CFD6E0` border, white or paper background, containing monospaced state tags (e.g., `CALDRE #02194821 // CA BAR #312984`).
- Critical urgency badges feature a Signal Vermilion dot indicator with no blur.