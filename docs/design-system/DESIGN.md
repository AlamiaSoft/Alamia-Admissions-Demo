---
name: Alamia AdmissionsOS
colors:
  surface: '#f8fafc'
  surface-dim: '#f1f5f9'
  surface-bright: '#ffffff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8fafc'
  surface-container: '#f1f5f9'
  surface-container-high: '#e2e8f0'
  surface-container-highest: '#cbd5e1'
  on-surface: '#0f172a'
  on-surface-variant: '#475569'
  inverse-surface: '#0f172a'
  inverse-on-surface: '#f8fafc'
  outline: '#cbd5e1'
  outline-variant: '#e2e8f0'
  primary: '#2563eb'
  primary-hover: '#1d4ed8'
  primary-subtle: '#eff6ff'
  on-primary: '#ffffff'
  secondary: '#475569'
  secondary-subtle: '#f1f5f9'
  on-secondary: '#ffffff'
  tertiary: '#0f766e'
  on-tertiary: '#ffffff'
  error: '#dc2626'
  error-subtle: '#fef2f2'
  warning: '#d97706'
  warning-subtle: '#fffbeb'
  success: '#16a34a'
  success-subtle: '#f0fdf4'
  background: '#f8fafc'
  on-background: '#0f172a'
typography:
  page-title:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  section-heading:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  card-heading:
    fontFamily: Inter
    fontSize: 14px
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
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.375rem
  md: 0.5rem
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

## Brand & Style Direction

This design system establishes a high-precision, calm, and readable SaaS operational workspace for institutional admissions offices, regional advisory hubs, and document verification ledgers. Influenced by the restrained design discipline of platforms like **Linear**, **Stripe**, and **Attio**, the aesthetic prioritizes uncompromised institutional trust, fast visual scanning, and clarity of workflow status.

The main workspace balances operational data density with sufficient whitespace, subtle hairlines, and restrained indicators. The dark navy enterprise sidebar (`#0F172A`, `w-72`) serves as the permanent, protected navigational anchor.

## Protected Sidebar Region

> [!IMPORTANT]
> The Adviser Console dark navy sidebar (`#0F172A`, 288px width, `w-72`) is explicitly protected from redesign. All typography refinements, white surfaces, and layout changes apply strictly to the right-hand main content workspace (`pl-72`).

## Canonical Colors

- **Global Substrate**: `#F8FAFC` (Slate-50) forms the calm application canvas.
- **Card & Workspace Surfaces**: `#FFFFFF` (Pure White) bounded by crisp `#E2E8F0` (Slate-200) 1px borders with subtle hover feedback (`#CBD5E1`).
- **Primary Text**: `#0F172A` (Slate-900) provides high-contrast, accessible typography for headings, student names, and primary metrics.
- **Secondary & Meta Text**: `#475569` (Slate-600) for body descriptions, and `#64748B` (Slate-500) for metadata, labels, and supplementary notes.
- **Action & Interactive Anchors**: `#2563EB` (Blue-600) serves as primary button fill and active selection stroke, with `#1D4ED8` (Blue-700) on hover.
- **Restrained Status Accents**:
  - *Student Action Needed / Pending*: `#F43F5E` (Rose-500) dot indicator, `#FFF1F2` (Rose-50) pill with `#FECDD3` border.
  - *Adviser Action Needed*: `#F59E0B` (Amber-500) dot indicator, `#FFFBEB` (Amber-50) pill with `#FDE68A` border.
  - *Awaiting Institution / Transit*: `#2563EB` (Blue-600) dot indicator, `#EFF6FF` (Blue-50) pill with `#BFDBFE` border.
  - *Internal Review*: `#64748B` (Slate-500) dot indicator, `#F1F5F9` (Slate-100) pill with `#E2E8F0` border.
  - *Blocked / Prerequisite Exception*: `#E11D48` (Rose-600) dot indicator.

## Typography System

- **Primary Interface Font**: **Inter** is the canonical font across all headings, body copy, form controls, table cells, buttons, and queue tabs. `Plus Jakarta Sans` is retired from ordinary workspace elements.
- **Technical Codes & Identifiers**: **JetBrains Mono** is strictly confined to genuine technical tokens (e.g. `DEMO-STD-001`, `#TAY-88219`, `CORRIDOR: PK → MY`).
- **Timestamps, Counts & Numerical Values**: Use **Inter** with tabular numerals enabled (`tabular-nums` / `.tabular`). Ordinary timestamps (`14:00 – 14:45`, `11:42 AM`) and counts (`03`, `12`) are never styled in monospace.

## Spacing & Component Standards

- **Spacing Scale**: 4px baseline rhythm (`space-xs: 4px`, `space-sm: 8px`, `space-md: 12px`, `space-lg: 16px`, `space-xl: 24px`, `32px` major section gaps).
- **Surfaces**: Crisp 1px `#E2E8F0` borders, `rounded-lg` (8px radius), and minimal ambient shadow (`shadow-2xs` / `shadow-xs`).
- **Data Tables**: Row height 44–48px for comfortable readability; subtle header `#F8FAFC/70` with uppercase 11px slate-500 labels; divider lines 1px `#F1F5F9`.
- **Form Controls & Search**: Uniform 32px (`h-8`) or 36px (`h-9`) height, `#F8FAFC` background transitioning to `#FFFFFF` on focus with `#2563EB` border.
