---
name: Nexus Research Portal
colors:
  surface: '#041329'
  surface-dim: '#041329'
  surface-bright: '#2c3951'
  surface-container-lowest: '#010e24'
  surface-container-low: '#0d1c32'
  surface-container: '#112036'
  surface-container-high: '#1c2a41'
  surface-container-highest: '#27354c'
  on-surface: '#d6e3ff'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#d6e3ff'
  inverse-on-surface: '#233148'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#bdc2ff'
  on-secondary: '#131e8c'
  secondary-container: '#2f3aa3'
  on-secondary-container: '#a8afff'
  tertiary: '#4ee6aa'
  on-tertiary: '#003825'
  tertiary-container: '#22c990'
  on-tertiary-container: '#004e35'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bdc2ff'
  on-secondary-fixed: '#000767'
  on-secondary-fixed-variant: '#2f3aa3'
  tertiary-fixed: '#68fcbf'
  tertiary-fixed-dim: '#45dfa4'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#041329'
  on-background: '#d6e3ff'
  surface-variant: '#27354c'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  title-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system establishes a high-performance, precision-engineered university research portal that bridges academic rigor with enterprise SaaS clarity. The platform serves faculty investigators, doctoral candidates, cross-institutional collaborators, and grant funding officers who demand dense, legible research data without visual fatigue.

The visual direction pairs deep foundational slate and navy tones with crisp surface contrasts, electric cyan accents, and refined glass-panel layering. The atmosphere avoids institutional bureaucracy and traditional academic publishing conventions in favor of a modern technical dashboard: luminous data markers, micro-metric pills, restrained border glows, and crisp spatial hierarchy.

## Colors
The palette is rooted in an authoritative deep navy environment designed to reduce optical strain during intensive analytical workflows while giving data visualizations high-contrast prominence.

- **Primary (`#38BDF8`)**: Vibrant sky cyan used for primary calls-to-action, active research states, focus indicators, and focal data metrics.
- **Secondary (`#818CF8`)**: Muted indigo/slate violet utilized for secondary interactive triggers, category taxonomies, and multi-author relational tags.
- **Tertiary (`#34D399`)**: Emerald green signaling verified grant milestones, peer-review completion, and active server/compute nodes.
- **Neutral (`#0A192F`)**: Foundation base navy. Structural surface tiers step upward into `#0F172A` (surface base), `#1E293B` (cards and panels), and `#334155` (hairline dividers).
- **Text & Contrast**: Primary high-emphasis copy defaults to crisp `#F8FAFC`, secondary technical metadata to `#94A3B8`, and disabled/ghost states to `#64748B`.

## Typography
The typographic architecture relies exclusively on modern geometric and humanist grotesques. Serif typography is strictly prohibited across all touchpoints to preserve an agile, computational SaaS posture.

- **Display & Headlines (`Plus Jakarta Sans`)**: Delivers tight aperture, high technical legibility, and modern weight distribution for project titles, dashboard KPIs, and section headers.
- **Body & Technical Metadata (`Inter`)**: Engineered for tabular data density, dense abstract scanning, and cross-platform clarity. Tabular figures (`tnum`) must be activated for numeric data visualizations, timestamps, and grant funding counters.

## Layout & Spacing
The layout adheres to a flexible 12-column responsive grid anchored by an 8-point baseline rhythm.

- **Desktop (1280px+)**: 12 columns with `1.5rem` gutters and `2rem` outer canvas padding. Left navigation persists as a 260px collapsible panel; the primary analytical workspace handles dynamic multi-column card configurations (e.g., 8-column data stream + 4-column telemetry sidebar).
- **Tablet (768px - 1279px)**: 8 columns with `1.25rem` gutters and `1.5rem` margins. Sidebars collapse to slide-over drawers or modular top tabs.
- **Mobile (< 768px)**: 4 columns with `1rem` gutters and `1rem` safe-area canvas margins. Complex tables and split panels stack vertically into unified modular cards with horizontal sub-tab navigation.

## Elevation & Depth
Depth is constructed through optical transparency, tonal stratification, and faint edge luminance rather than heavy drop shadows.

- **Base Canvas**: Solid `#0A192F`.
- **Level 1 (Card & Module Surface)**: Background `rgba(15, 23, 42, 0.75)` with backdrop filter blur of `16px` and a 1px border stroke of `rgba(255, 255, 255, 0.08)`.
- **Level 2 (Active / Hover / Modals)**: Background `rgba(30, 41, 59, 0.85)` with backdrop blur `24px`, ambient shadow `0 20px 25px -5px rgba(2, 6, 23, 0.6), 0 8px 10px -6px rgba(2, 6, 23, 0.4)`, and edge stroke `rgba(56, 189, 248, 0.25)`.
- **Glow Accents**: Primary action surfaces leverage a soft localized radial cyan glow (`rgba(56, 189, 248, 0.15)`) diffusing 32px behind focal widgets to establish visual hierarchy.

## Shapes
Geometry is calibrated to standard `12px` to `16px` radii, creating a clean balance between technical authority and ergonomic consumer software polish.

- **Primary Cards and Panels**: Fixed at `12px` to `16px` radius (`rounded-lg` / `rounded-xl`).
- **Interactive Inputs and Buttons**: Set to `8px` (`0.5rem`) for crisp button outlines and balanced form fields.
- **Status Pills and Badges**: Fully rounded (`9999px`) to visually differentiate metadata chips from structural content containers.

## Components

### Buttons
- **Primary**: Sky cyan background (`#38BDF8`), dark navy text (`#0A192F`, font-weight 600), `8px` border radius, padding `0.5rem 1rem`. Subtly brightens on hover with an ambient `rgba(56, 189, 248, 0.35)` glow.
- **Secondary / Outline**: Translucent background `rgba(255, 255, 255, 0.04)`, 1px border `rgba(255, 255, 255, 0.15)`, text `#F8FAFC`. On hover, the border shifts to `#38BDF8` with a background fill of `rgba(56, 189, 248, 0.08)`.
- **Ghost / Minimal**: Borderless, text `#94A3B8`, brightening to `#F8FAFC` on hover with a `rgba(255, 255, 255, 0.05)` backdrop.

### Metric Badges & Status Chips
- Pill-shaped (`9999px`), padding `0.25rem 0.625rem`, typography `label-sm`.
- Formatted as muted tinted fills with 1px borders: Active grant (`rgba(52, 211, 153, 0.12)` fill, `#34D399` text, `rgba(52, 211, 153, 0.3)` border); In-Review (`rgba(129, 140, 248, 0.12)` fill, `#818CF8` text, `rgba(129, 140, 248, 0.3)` border).
- Tabular figures applied to all metric quantities and citation counts.

### Data Cards
- Container styled with `16px` corner radius, frosted base fill (`rgba(15, 23, 42, 0.75)`), 1px border (`rgba(255, 255, 255, 0.08)`), and padding of `1.5rem`.
- Card headers feature clear separation: title on the left, telemetry pill or contextual kebab action on the right.
- Visual dividers within cards use crisp 1px strokes of `rgba(255, 255, 255, 0.06)`.

### Form Inputs & Filters
- Background `rgba(10, 25, 47, 0.6)`, border `1px solid rgba(255, 255, 255, 0.12)`, radius `8px`, typography `body-md` in `#F8FAFC`.
- Focus state triggers an immediate `1px solid #38BDF8` border with a subtle outer ring glow `0 0 0 3px rgba(56, 189, 248, 0.2)`. Placeholder text remains `#64748B`.

### Checkboxes & Radios
- Square checkbox (`4px` radius) or circular radio (`9999px`) in 1px stroke `rgba(255, 255, 255, 0.25)`.
- Checked state fills with `#38BDF8`, sporting an interior `#0A192F` checkmark or radio dot.

### Specialized Research Widgets
- **Author Lineage Bar**: Inline linked chips featuring collaborator avatars with overlap offsets and department metadata.
- **Grant Burn-Rate & Telemetry Trackers**: Ultra-slim (`6px`) progress tracks with `9999px` radius, utilizing linear gradients from `#38BDF8` to `#818CF8` over muted track troughs (`rgba(255, 255, 255, 0.08)`).
- **Code & Dataset Repos**: Distinct dark monospaced block containers (`rgba(2, 6, 23, 0.75)`) with copyable DOI tokens and quick-export action handles.