---
name: Alamia AdmissionsOS
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2151da'
  primary: '#0037b0'
  on-primary: '#ffffff'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#565d79'
  on-secondary: '#ffffff'
  secondary-container: '#d8deff'
  on-secondary-container: '#5a627e'
  tertiary: '#004f35'
  on-tertiary: '#ffffff'
  tertiary-container: '#006a48'
  on-tertiary-container: '#60eeb1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#bec5e5'
  on-secondary-fixed: '#131a33'
  on-secondary-fixed-variant: '#3e4660'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-dense: 0.5rem
  margin: 1.5rem
  margin-compact: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system establishes a high-precision, dense operational environment for institutional admissions offices, enrollment managers, and document evaluators. Rooted in Modern Enterprise Minimalism with structural influences from developer-grade platforms like Linear and Stripe, the aesthetic conveys uncompromised institutional trust, forensic auditability, and effortless operational velocity.

The interface addresses high cognitive load through rigorous visual hierarchy, micro-surfaces, subtle hairline dividers, and deliberate high-information density. The emotional tone balances administrative gravitas with rapid, keyboard-first tactical speed. Deep slate chrome grounds the shell while illuminated, surgical white workspaces isolate active candidate dossiers, analytical queues, and verification ledgers.

## Colors

The palette leverages a high-contrast relationship between foundational slate infrastructure, neutral workspace layers, and saturated status signals:

- **Chrome & Structural Shell**: `#0B132B` (Deep Navy) drives root headers and primary operational navigation; `#1C2541` (Dark Slate) provides context boundaries, flyout headers, and pinned command rails.
- **Canvas & Layering**: `#F8FAFC` forms the global application substrate, layered with `#F1F5F9` for secondary audit panels, metadata drawers, and inactive split-views. `#FFFFFF` is reserved strictly for primary interactive cards, document viewport canvases, and active data tables.
- **Action & Primary Accents**: `#1D4ED8` serves as the primary actionable anchor for commits, batch reviews, and definitive status updates, supported by `#2563EB` on interactive hover and `#3B82F6` for focus indicators and multi-selection boundaries.
- **Status & Forensic Verification**:
  - *Verified / Cleared*: `#10B981` (tinted text/border: `#059669`, surface background: `#ECFDF5`).
  - *Awaiting Confirmation / Caution*: `#F59E0B` (tinted text/border: `#D97706`, surface background: `#FFFBEB`).
  - *Blocked / Discrepancy Exception*: `#EF4444` (tinted text/border: `#DC2626`, surface background: `#FEF2F2`).
- **Hairlines & Dividers**: Internal table borders and micro-separators use explicit `#E2E8F0`, avoiding fuzzy drop boundaries.

## Typography

The typography pairs `Plus Jakarta Sans` for section anchors, record headers, and application metrics with `Inter` for hyper-dense operational scanning across tables, audit trails, and document forms. Monospaced identifiers (SIS IDs, transcript hashes, application reference numbers) render in `JetBrains Mono` to eliminate character ambiguity.

Data tables utilize a strict 13px baseline (`body-md`) with tabular figures enabled (`font-variant-numeric: tabular-nums`) to align currency, test percentiles, GPA figures, and submission timestamps across scanning columns.

## Layout & Spacing

The layout is built on a 12-column adaptive workspace system supporting simultaneous multi-pane triage:
- **Application Shell**: Pinned 64px or 240px collapsible navigation rail anchored to the dark chrome `#0B132B`.
- **Master-Detail Workspace**: 40% list view paired with a 60% verification canvas on medium monitors (1280px–1599px); transitions to a three-tier split (navigation, records queue, contextual side drawer) on wide monitors (1600px+).
- **Side Drawers**: Fixed 440px to 640px overlay panel sliding from the right edge, hosting verification steps, transcript scans, and activity audits without breaking primary table context.
- **Rhythm & Metrics**: Built on a 4px baseline grid. Compact padding (`space-xs` and `space-sm`) enforces a dense, productive data grid where vertical screen real estate is optimized for row visibility.

## Elevation & Depth

This system avoids heavy, blurred drop shadows in favor of precise hairline containment, tonal layering, and subtle ambient boundaries:

- **Level 0 (Floor)**: `#F8FAFC` base application background.
- **Level 1 (Panels & Cards)**: Crisp `#FFFFFF` surfaces bounded by a 1px border of `#E2E8F0`. Zero elevation shadow while static; an ultra-soft offset (`0 1px 3px rgba(11, 19, 43, 0.05)`) applies on active focus or row selection.
- **Level 2 (Popovers, Filter Menus, Context Action Menus)**: `#FFFFFF` surface, 1px border of `#CBD5E1`, shadow `0 4px 12px -2px rgba(11, 19, 43, 0.08), 0 2px 6px -1px rgba(11, 19, 43, 0.04)`.
- **Level 3 (Side Drawers & Inspection Sheets)**: `#FFFFFF` container with a dark backdrop dimming overlay (`rgba(11, 19, 43, 0.35)`), bordered on the left by `#CBD5E1`, shadow `-4px 0 24px rgba(11, 19, 43, 0.10)`.
- **Level 4 (Critical Modal Decisions / Escalation Dialogs)**: Centered container with 1px border of `#CBD5E1` and shadow `0 20px 25px -5px rgba(11, 19, 43, 0.12), 0 8px 10px -6px rgba(11, 19, 43, 0.06)`.

## Shapes

The geometric architecture is crisp and functional (`roundedness: 1`), keeping elements structured and compact:
- Standard interactive elements (inputs, standard buttons, table cell wrappers): `rounded` (4px / 0.25rem).
- Surface containers, summary cards, and slide-in drawer headers: `rounded-lg` (8px / 0.5rem).
- Micro-badges, tag markers, and status indicators: Semi-rounded `rounded` (4px / 0.25rem) to ensure legible internal alignment with 11px uppercase and monospaced text.
- Fully circular avatars and state icons: `rounded-full` reserved solely for applicant profile thumbnails and icon node indicators on the case timeline.

## Components

### Buttons
- **Primary**: Solid `#1D4ED8` background, `#FFFFFF` text, 4px border radius. Hover: `#2563EB`. Active: `#1E40AF`. Height: 32px (compact) or 36px (default). Padding: 8px 12px.
- **Secondary / Ghost**: Transparent or `#FFFFFF` background, 1px `#E2E8F0` border, `#1E293B` text. Hover: `#F1F5F9`.
- **Destructive**: `#FEF2F2` background, 1px `#FCA5A5` border, `#DC2626` text. Hover: `#EF4444` background with `#FFFFFF` text.

### Verification Badges & Micro-Pills
Compact 20px height tokens featuring a 6px status dot, 11px semi-bold label, and 1px matching hairline border:
- **Verified**: `#ECFDF5` background, `#059669` text, `#A7F3D0` border. Dot: `#10B981`.
- **Unverified / Blocked**: `#FEF2F2` background, `#DC2626` text, `#FECACA` border. Dot: `#EF4444`.
- **Awaiting Confirmation**: `#FFFBEB` background, `#D97706` text, `#FDE68A` border. Dot: `#F59E0B`.

### Form Controls & Inputs
- **Text Inputs**: Height 32px, `#FFFFFF` background, 1px `#CBD5E1` border, 4px radius, 13px `Inter` body text. Focused state uses `#1D4ED8` border with a 2px outer ring in `rgba(59, 130, 246, 0.2)`.
- **Checkboxes & Radios**: 14px × 14px square/round controls, `#E2E8F0` border. When selected: solid `#1D4ED8` fill with crisp white check mark or dot.

### Data Tables & List Views
- Row height: 36px for dense audit mode; 44px for default review mode.
- Header: `#F8FAFC` background, 11px uppercase `#64748B` typography, bottom border 1px `#E2E8F0`.
- Hover state: Row-level `#F8FAFC` highlighting with pinned quick-action controls revealed at the right boundary.

### Case Timelines & Audit Feeds
- Vertical 1px spine in `#E2E8F0`.
- Milestone nodes: 16px circular badge containing an icon or verification state dot.
- Content block: Compact card housing event actor, source citation link (e.g., *Common App Sync*, *Parchment API*), timestamp (`code-sm` font in `#64748B`), and verified payload snapshot.

### Contextual Side Drawers
- Sliding right sheet containing dossier details, dual-page PDF/transcript viewports, and evaluator scorecards.
- Header: `#1C2541` (Dark Slate) with `#FFFFFF` headline text and breadcrumb context; drawer body transitions back to `#FFFFFF` with `#F8FAFC` split panes for dense comparative analysis.