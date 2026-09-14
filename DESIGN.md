---
name: USDTX Financial OTC Desk
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
  on-surface-variant: '#3d4a42'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a72'
  outline-variant: '#bccac0'
  surface-tint: '#006c4a'
  primary: '#006948'
  on-primary: '#ffffff'
  primary-container: '#00855d'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dba9'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#0051d5'
  on-tertiary: '#ffffff'
  tertiary-container: '#316bf3'
  on-tertiary-container: '#fefcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85f8c4'
  primary-fixed-dim: '#68dba9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-numeric-lg:
    fontFamily: JetBrains Mono
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  label-numeric-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0em
  label-code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system defines a institutional-grade, white-glove OTC (Over-The-Counter) financial service bridging USDT and INR. The visual ethos rejects retail crypto cliches—dark interfaces, flashing candlestick charts, neon accents, and speculative noise—in favor of prime brokerage sobriety, regulatory authority, and banking confidence.

### Design Principles
- **Institutional Clarity:** Whitespace, structural precision, and crisp borders eliminate ambiguity. Financial numbers and settlement terms take precedence.
- **Reassurance of Settlement:** Visuals convey finality, security, and institutional custody. The platform feels closer to an FX settlement terminal or private wealth platform than a retail exchange.
- **Zero Ambiguity Operational UI:** Status indicators, rate lock timers, and counterparty credentials leave no room for cognitive drift.

### Design Movement
**Modern Corporate Fintech & Clean Functionalism:** High-luminance white canvases, structured tabular layouts, whisper-quiet micro-borders, deep navy typographic hierarchy, and surgical emerald highlights.

## Colors

The palette relies on stark structural contrast: high-key light backgrounds, deep navy text layers for readability, slate neutrals for structural grid division, and deliberate contextual states.

### Core Canvas & Structure
- **Base Background:** `#FFFFFF` (Primary surface) with secondary operational canvas in `#F8FAFC` (Slate 50).
- **Structural Outlines:** `#E2E8F0` (Slate 200) for standard card borders, grid dividers, and field frames. `#CBD5E1` (Slate 300) for active borders and hover boundaries.

### Typography Hierarchy
- **Heading & Value Text:** `#0F172A` (Slate 900) — delivers high contrast and executive presence for rates, balances, and totals.
- **Body & Primary Labels:** `#1E293B` (Slate 800) — clean, readable operational context.
- **Secondary / Supporting:** `#64748B` (Slate 500) — timestamps, metadata, helper text, and secondary units.
- **Muted / Disabled:** `#94A3B8` (Slate 400).

### Financial Semantic Colors
- **Primary Brand / Settlement Green:** `#059669` (Emerald 600) with hover `#047857` (Emerald 700) and subtle background tint `#ECFDF5` (Emerald 50). Used for confirmed values, completed settlements, primary actions, and net positive balances.
- **Processing / Operational Blue:** `#2563EB` (Blue 600) with surface `#EFF6FF` (Blue 50). Used for bank transfer verifications, queued orders, and system processing.
- **Pending / Action Required Amber:** `#D97706` (Amber 600) with surface `#FFFBEB` (Amber 50). Denotes awaiting bank credit, pending KYC verification, or counterparty rate validation.
- **Rejected / Terminated Rose:** `#E11D48` (Rose 600) with surface `#FFF1F2` (Rose 50). Denotes compliance flags, rejected slips, or transaction cancellations.

## Typography

Typography drives trust and operational speed. Two distinct families operate in harmony:
- **Hanken Grotesk:** Primary interface typeface. Sharp, contemporary grotesque with structural geometry and zero eccentricities. Delivers clean reading hierarchies across complex transactional summaries and operational portals.
- **JetBrains Mono:** Specialized data and financial numerals typeface. All transaction amounts, exchange quotes (e.g., `1 USDT = 89.42 INR`), UTR numbers, blockchain hashes, and bank IFSC codes use JetBrains Mono to ensure strict tabular alignment and character distinctiveness (preventing confusion between `0` and `O`, or `1` and `l`).

All financial tables must enforce tabular numerals (`tnum`) across all standard font declarations.

## Layout & Spacing

The layout is built on an intentional 8pt spatial cadence. The OTC operational desk requires density without visual clutter, prioritizing horizontal alignment of paired values (USDT sold vs. INR payout).

### Layout System
- **Desktop (1280px+):** Max-width canvas capped at `1440px`. A 12-column grid system with 24px (`1.5rem`) gutters and 48px (`3rem`) margins. Operational consoles utilize fixed side navigation (`260px`) with fluid operational viewports.
- **Tablet (768px - 1024px):** 8-column layout with 16px (`1rem`) gutters and 24px (`1.5rem`) margins. Metric cards stack from 4 columns to 2x2 grids.
- **Mobile (< 768px):** 4-column layout with 16px outer margins. Data tables gracefully collapse into progressive stacked summary cards.

## Elevation & Depth

This system avoids floating, high-blur drop shadows and dark pseudo-neomorphic depths. Elevation is handled primarily through **tonal borders and calibrated micro-shadows**.

- **Level 0 (Flat / Canvas):** Surface color `#F8FAFC` on body with white `#FFFFFF` cards, separated by a clean 1px border of `#E2E8F0`.
- **Level 1 (Card & Section Elevation):** `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`. Borders remain active with `#E2E8F0`.
- **Level 2 (Popovers, Dropdowns, Action Sheets):** `box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.06), 0 4px 6px -4px rgba(15, 23, 42, 0.03)`, framed by a crisp border `#CBD5E1`.
- **Level 3 (Modal Dialogues & Order Confirmations):** `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`. Background backdrop uses `#0F172A` at `40%` opacity with a subtle 2px backdrop blur.

## Shapes

The interface balances sharp institutional precision with modern comfort. 

- **Cards & Data Modules:** `rounded-xl` (12px / 0.75rem) to `rounded-2xl` (16px / 1rem) for high-level order panels, quote containers, and KPI widgets.
- **Input Fields & Buttons:** `rounded-lg` (8px / 0.5rem) providing structural anchor points that feel distinct from outer card perimeters.
- **Badges & Status Pills:** Fully rounded / pill (`9999px`) to maintain clear differentiation between interactive inputs and non-interactive status badges.

## Components

### 1. Primary & Secondary Buttons
- **Primary CTA (Lock Quote, Confirm Payment, Authorize Settlement):** Solid `#059669`, label in pure white `#FFFFFF` (`font-weight: 600`). On hover, transitions cleanly to `#047857`. Focus ring: 2px offset with 2px width in `#10B981`.
- **Secondary CTA (Download Receipt, Copy Details):** Background `#FFFFFF`, border 1px solid `#E2E8F0`, label in `#0F172A`. On hover, background shifts to `#F8FAFC` and border to `#CBD5E1`.
- **Destructive / Cancellation Action:** Light surface `#FFF1F2`, text `#E11D48`, border 1px solid `#FECDD3`. On hover, text becomes white with solid background `#E11D48`.

### 2. Status Chips & Badges
All status chips use a pill shape, `11px` uppercase mono or `12px` medium grotesque, with a light tint background and solid readable text:
- **Pending / Action Required:** Surface `#FFFBEB`, text `#B45309`, border `#FDE68A`.
- **Processing / Verification:** Surface `#EFF6FF`, text `#1D4ED8`, border `#BFDBFE`.
- **Completed / Settled:** Surface `#ECFDF5`, text `#047857`, border `#A7F3D0`.
- **Rejected / Cancelled:** Surface `#FFF1F2`, text `#BE123C`, border `#FECDD3`.

### 3. OTC Currency Input & Conversion Field
- A stacked container featuring an interactive currency symbol toggle (`USDT` / `INR`), a large tabular input (`label-numeric-lg`), and an embedded "Available Limits" badge.
- Active focus displays a 1px border in `#059669` accompanied by a soft glow ring: `0 0 0 3px rgba(5, 150, 105, 0.12)`.

### 4. Tabular Settlements & Ledger Lists
- Rows feature a fixed 56px height, alternating no zebra striping; instead, subtle 1px border-bottom (`#F1F5F9`) with `#F8FAFC` row hover state.
- Columns use strict right-alignment for all monetary figures and settlement numbers, and left-alignment for party names, bank names, and order references.

### 5. Cards & Operational Modules
- Structural white `#FFFFFF` surface bounded by 1px solid `#E2E8F0` border and `rounded-xl` or `rounded-2xl`. Header contains contextual breadcrumb or state description, paired with an action button or copyable order ID. Inner padding is generous (`space-lg` to `space-xl`).