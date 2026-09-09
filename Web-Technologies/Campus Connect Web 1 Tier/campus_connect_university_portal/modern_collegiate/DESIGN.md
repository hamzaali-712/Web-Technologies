---
name: Modern Collegiate
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#43474e'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#455f88'
  primary: '#002045'
  on-primary: '#ffffff'
  primary-container: '#1a365d'
  on-primary-container: '#86a0cd'
  inverse-primary: '#adc7f7'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#0b2238'
  on-tertiary: '#ffffff'
  tertiary-container: '#23374f'
  on-tertiary-container: '#8ca0bd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#adc7f7'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#2d476f'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#d2e4ff'
  tertiary-fixed-dim: '#b3c8e6'
  on-tertiary-fixed: '#051c33'
  on-tertiary-fixed-variant: '#344861'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  title-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
---

## Brand & Style

This design system defines an authoritative yet approachable digital environment for higher education. The system balances collegiate prestige with consumer-grade software clarity, directly serving university students, faculty, and administrative staff across their daily academic workflows.

The visual direction sits at the intersection of modern institutional credibility and active productivity. It moves away from bureaucratic, dense campus portals of the past, embracing structured hierarchy, deliberate white space, and warm accents that inspire achievement. The experience should feel organized, dependable, and dignified—instilling confidence during high-stakes moments like exam registrations, tuition management, and research submissions.

## Colors

The palette establishes an academic environment anchored by deep collegiate blues and accented by amber and gold tones.

- **Primary (`#1A365D`) & Tertiary (`#0D233A`)**: Deep Navy and Midnight Blue serve as the grounding institutional anchors. Used for structural chrome, navigation, headers, primary action buttons, and dominant visual weight.
- **Secondary (`#D97706` / `#F59E0B`)**: Warm Amber provides focused contrast. Reserved for active states, key milestone badges, notifications, deadlines, and secondary calls-to-action that require student attention without alarming them.
- **Canvas & Surface Tint (`#F0F7FF`)**: A soft blue tint replaces stark neutral grays for main application backdrops, evoking calm academic focus while cleanly isolating card surfaces.
- **Surface Clean (`#FFFFFF`)**: Pure crisp white reserved for functional containers, modular cards, dialogs, and input backgrounds.
- **Neutral Text (`#1F2937`)**: Deep slate ensures high-contrast readability across academic documentation, schedules, and grading tables.
- **Border & Rule (`#E2E8F0` / `#CFE2FE`)**: Muted slate and soft blue outlines define boundaries without adding visual clutter.

## Typography

The typographic hierarchy utilizes Plus Jakarta Sans for structural headings and primary copy, delivering modern warmth, open apertures, and collegiate presence. Inter is incorporated for system labels, data tables, metrics, course codes, and compact UI metadata where mechanical precision and horizontal density are critical.

Letter spacing is tightened progressively across larger display tiers to retain visual punch and avoid loose headlines. For all numerical schedules, GPA monitors, and grade rosters, enable tabular figures (`tnum`) to keep values vertically aligned.

## Layout & Spacing

The system runs on an 8px modular spacing rhythm (with a 4px sub-grid for badges, metadata tags, and compact table cells). 

- **Layout Model**: A responsive fluid 12-column grid system bounded by a maximum content container of 1440px on high-resolution displays.
- **Breakpoints**:
  - `Mobile` (< 768px): 4-column layout, 16px gutters, 16px horizontal screen margins. Sidebars collapse into an off-canvas drawer.
  - `Tablet` (768px - 1024px): 8-column layout, 24px gutters, 24px margins. Sub-navigation collapses into tabs or pill bars.
  - `Desktop` (> 1024px): 12-column layout, 24px gutters, 32px margins. Persistent dual-sidebar support (global campus navigation at 260px and contextual course drawer at 320px).
- **Reflow Rules**: Multicolumn dashboards stack into single-column activity streams on mobile devices. Data-heavy tables convert to vertical card stacks or enable frozen horizontal scroll containers with visual edge fades.

## Elevation & Depth

Depth in this system is light, subtle, and structured, reflecting modern web software rather than heavy physical skeuomorphism. Layering relies on crisp boundaries and cool-tinted ambient shadows.

- **Level 0 (Flat / Canvas)**: Non-elevated surfaces resting on the `#F0F7FF` background. Separated purely by hairline borders (`1px solid #E2E8F0`).
- **Level 1 (Cards & Standard Panels)**: Base surface for interactive items, course widgets, and schedule entries. Uses a crisp white background with an ambient shadow: `box-shadow: 0 1px 3px 0 rgba(13, 35, 58, 0.04), 0 1px 2px -1px rgba(13, 35, 58, 0.04)` combined with a perimeter boundary `border: 1px solid rgba(226, 232, 240, 0.8)`.
- **Level 2 (Dropdowns, Popovers & Hover States)**: Lifted cards and secondary overlays: `box-shadow: 0 4px 6px -1px rgba(13, 35, 58, 0.07), 0 2px 4px -2px rgba(13, 35, 58, 0.05)`.
- **Level 3 (Modals & Command Palettes)**: High-priority system dialogues: `box-shadow: 0 20px 25px -5px rgba(13, 35, 58, 0.12), 0 8px 10px -6px rgba(13, 35, 58, 0.08)`. Modals pair with a backdrop scrim colored `rgba(13, 35, 58, 0.45)` with `backdrop-filter: blur(4px)`.

## Shapes

The interface embraces a balanced 8px to 12px geometric standard, creating friendly, approachable components while preserving structural efficiency.

- **Base Radius (`0.5rem` / 8px)**: Standard inputs, buttons, table cell selections, notification toasts, and inline dropdown items.
- **Card Radius (`0.75rem` / 12px)**: Dashboard widgets, course module containers, modal dialogs, and slide-out side sheets.
- **Pill Radius (`9999px`)**: Status chips, category tags, user presence indicators, and academic term selector pills.
- **Sharp Details (`0px`)**: Full-bleed application topbars, global split panels, and strict calendar grid borders.

## Components

### Buttons
- **Primary**: Solid Deep Navy (`#1A365D`) fill, `#FFFFFF` text. Hover transitions to Tertiary (`#0D233A`). 8px border radius, 40px standard height (48px on mobile touch viewports), font-weight 600. Focus rings feature an amber outer halo (`2px solid #F59E0B` with 2px offset).
- **Secondary / Action**: Warm Gold/Amber (`#D97706`) background with white text, deployed for key conversion flows (e.g., "Submit Application", "Pay Tuition").
- **Outline**: 1px border (`#CFE2FE`), transparent background, `#1A365D` text. On hover: fills with 50% opacity of `#F0F7FF`.
- **Ghost**: Transparent background, `#1F2937` text. On hover: fills with `#F0F7FF`.

### Badges & Chips
- **Academic Badges**: 24px height, full pill radius (`9999px`), uppercase `label-sm` typography with `0.04em` tracking.
- **Status Tints**:
  - *Active / Enrolled*: Emerald green text on mint wash (`#ECFDF5` / `#059669`).
  - *Pending / Waitlisted*: Amber text on warm gold wash (`#FFFBEB` / `#D97706`).
  - *Prerequisite Alert*: Rose text on soft red wash (`#FEF2F2` / `#DC2626`).
  - *Informational / Course Level*: Slate text on blue tint wash (`#EFF6FF` / `#1A365D`).

### Cards & Modules
- Clean `#FFFFFF` fill with `12px` rounded corners and Level 1 elevation.
- Dividers between card header and body use `1px solid #F1F5F9`.
- Dynamic hover state: lifts smoothly by 2px with transition to Level 2 elevation and a border accent highlight (`#BFDBFE`).

### Input Fields & Controls
- **Form Inputs**: 40px height, 8px radius, white background, framed by `1px solid #CBD5E1`. Placeholder text in `#94A3B8`. Active focus applies an internal `#1A365D` boundary and an external `0 0 0 3px rgba(26, 54, 93, 0.12)` halo.
- **Checkboxes & Radios**: 18px square (or circle) with 4px radius. In active state, filled with `#1A365D` featuring a white vector checkmark.

### Lists & Data Tables
- Row height: 48px standard, alternating light hover states (`#F8FAFC`).
- Header cells: `label-sm` uppercase, `#64748B`, set against a faint blue-tint background (`#F8FAFC`).
- Sticky table headers and pinned student identifier columns maintain Level 1 elevation during horizontal scrolling.

### Specialized Collegiate Components
- **Course Schedule Timeline**: Vertical or weekly matrix layout with colored left-side edge indicators mapping to department disciplines.
- **Academic Progress Bar**: 8px height track (`#E2E8F0`) with a smooth fill gradient transitioning from `#1A365D` to `#F59E0B` reflecting degree completion.
- **GPA / Grade Callout**: Compact modular tile featuring oversized `display-lg` numbers in `#0D233A` with adjacent contextual ranking badges.