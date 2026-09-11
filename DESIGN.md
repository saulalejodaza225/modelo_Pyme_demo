---
name: Vértice Precision Automotive
colors:
  surface: '#111418'
  surface-dim: '#111418'
  surface-bright: '#36393e'
  surface-container-lowest: '#0b0e12'
  surface-container-low: '#191c20'
  surface-container: '#1d2024'
  surface-container-high: '#272a2e'
  surface-container-highest: '#323539'
  on-surface: '#e1e2e8'
  on-surface-variant: '#e2bfb2'
  inverse-surface: '#e1e2e8'
  inverse-on-surface: '#2e3135'
  outline: '#a98a7e'
  outline-variant: '#5a4137'
  surface-tint: '#ffb597'
  primary: '#ffb597'
  on-primary: '#581d00'
  primary-container: '#ff6a1a'
  on-primary-container: '#591e00'
  inverse-primary: '#a43d00'
  secondary: '#41e575'
  on-secondary: '#003915'
  secondary-container: '#06c85d'
  on-secondary-container: '#004d1f'
  tertiary: '#c1c7d1'
  on-tertiary: '#2b3139'
  tertiary-container: '#9399a3'
  on-tertiary-container: '#2b3139'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#ffb597'
  on-primary-fixed: '#360f00'
  on-primary-fixed-variant: '#7d2d00'
  secondary-fixed: '#66ff8e'
  secondary-fixed-dim: '#3de273'
  on-secondary-fixed: '#002109'
  on-secondary-fixed-variant: '#005322'
  tertiary-fixed: '#dde3ee'
  tertiary-fixed-dim: '#c1c7d1'
  on-tertiary-fixed: '#161c24'
  on-tertiary-fixed-variant: '#414750'
  background: '#111418'
  on-background: '#e1e2e8'
  surface-variant: '#323539'
typography:
  display-lg:
    fontFamily: Barlow Condensed
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: 0.04em
  display-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 38px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: 0.03em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: 0.03em
  headline-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.03em
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.04em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a high-performance, technical-luxe identity for an elite automotive center in Bogotá. The visual language conveys rigorous German-level engineering discipline, surgical cleanliness, and cutting-edge mechanical diagnostic capabilities. It directly rejects the greasy, disorganized tropes of traditional auto repair shops in favor of a motorsport pit-lane aesthetic merged with high-end industrial design.

The design movement is **Technical Precision Dark**: a controlled dark-mode environment relying on architectural contrast, razor-thin structural borders, graphite layers, and calibrated flashes of high-visibility signal orange (#FF6A1A). The interface communicates absolute mechanical reliability, prompt diagnostics, and white-glove automotive care.

## Colors

The palette is engineered around an authentic automotive instrument cluster hierarchy:

- **Canvas Base (`#111418`)**: Deep graphite black that absorbs ambient light and frames interactive components.
- **Surface Level 1 (`#1A1F24`)**: Base containers, structural panels, and cards.
- **Surface Level 2 (`#222830`)**: Elevated modules, dropdowns, inputs, and active states.
- **Structural Border (`#2A3038`)**: 1px architectural boundary providing structural framing without visual clutter.
- **Primary Signal Orange (`#FF6A1A`)**: High-torque interactive accent for primary actions, critical statuses, and dynamic border glow indicators.
- **Direct Comm Green (`#25D366`)**: Reserved strictly for high-conversion WhatsApp direct contact touchpoints.
- **Primary Text (`#F2F4F5`)**: High-legibility cold white for values, technical data, and dominant headers.
- **Secondary / Muted Text (`#9AA4AE`)**: Mechanical slate gray for labels, metric units, subtitles, and secondary indicators.

## Typography

Typography establishes an intentional contrast between industrial power and Swiss analytical utility:

- **Headlines (`Barlow Condensed`)**: Rendered in uppercase with slight positive tracking (`0.02em` to `0.04em`) to mirror motorsport telemetry and performance vehicle badge typography.
- **Body & Metrics (`Inter`)**: Neutral, highly legible grotesque suited for complex vehicle diagnostic checklists, pricing tables, VIN inputs, and status dashboards. Numbers feature tabular lining formatting (`font-variant-numeric: tabular-nums`) to maintain rigid alignment in invoices and mechanical quotes.

## Layout & Spacing

The system runs on an 8pt architectural grid with a 12-column fluid framework:

- **Desktop (>= 1200px)**: 12 columns, `1.5rem` (24px) gutters, max-width bounded at 1280px or 1440px for wide telemetry views. Outer margins at `2rem` (32px).
- **Tablet (768px - 1199px)**: 8 columns, `1rem` (16px) gutters, `1.5rem` outer margins.
- **Mobile (< 768px)**: 4 columns, `1rem` (16px) gutters, `1rem` (16px) outer margins.

Spacing inside cards and mechanical modules utilizes `space-md` (16px) or `space-lg` (24px) to avoid claustrophobia while maintaining an information-dense, instrumentation-grade feel.

## Elevation & Depth

Visual hierarchy is maintained through controlled graphite layering combined with precision border lighting:

- **Rest Elevation**: Cards reside at `#1A1F24` over `#111418` framed by a 1px border of `#2A3038`. No heavy cast shadows are permitted on rest.
- **Hover & Focus Interaction**: Upon user intent or hover, cards translateY by -2px, shifting the border to `#FF6A1A` accompanied by an ambient, localized perimeter glow: `0 8px 24px -4px rgba(255, 106, 26, 0.18)`.
- **Modals & Overlays**: Elevated to `#222830` with a 1px `#2A3038` edge and a deep backdrop veil: `rgba(17, 20, 24, 0.85)` with `backdrop-filter: blur(12px)`.

## Shapes

The geometric framework balances mechanical stability with ergonomic softness:

- **Interactive Controls (Buttons, Form Inputs, Segmented Controls)**: Defined strictly at `8px` corner radius. This reinforces a machined, tool-like tactility.
- **Containers & Cards**: Formed at `14px` corner radius (`rounded-md/lg` blend) to soften complex telemetry views without appearing toy-like.
- **Status Tags & Badges**: Small technical pill forms or clipped tags (`4px` to `6px`) reflecting automotive inspection tags.

## Components

### Buttons
- **Primary Action**: Solid `#FF6A1A` fill, `#111418` bold typography, 8px border-radius, height 48px (large) or 40px (medium). Hover: `#FF7E38`, active: `#E55A0D`.
- **Secondary / Technical Action**: Background `#1A1F24`, 1px border `#2A3038`, text `#F2F4F5`. Hover: Border `#FF6A1A`, text `#FF6A1A`, background `#222830`.
- **WhatsApp Concierge**: Solid `#25D366` fill, white `#FFFFFF` text, subtle elevation on hover with `0 4px 16px rgba(37, 211, 102, 0.25)`. Exclusively used for immediate quote confirmation or emergency dispatch.

### Cards & Service Panels
- Rendered on `#1A1F24` with a 1px `#2A3038` outline and 14px radius. 
- Header features uppercase `Barlow Condensed` titles with inline status badges (e.g., "EN DIAGNÓSTICO", "APROBADO").
- Hover transitions in 200ms cubic-bezier: 2px rise, `#FF6A1A` border accent, ambient subtle orange bloom.

### Input Fields & Selectors
- Container height 44px, background `#1A1F24`, border 1px `#2A3038`, radius 8px, text `#F2F4F5`.
- Placeholder `#9AA4AE`.
- Focus state: Border transitions to `#FF6A1A` with a 2px outer aura `rgba(255, 106, 26, 0.20)`. No default browser rings.

### Checkboxes & Radios
- Square 18px boxes with 4px radius or 18px circles.
- Unchecked: 1px border `#2A3038`, background `#111418`.
- Checked: Fill `#FF6A1A` with a bold white checkmark/dot.

### Technical Badges & Metric Chips
- Inline labels with 4px radius, uppercase `Inter` 10px bold, tracking 0.05em.
- Background: `rgba(42, 48, 56, 0.6)` with 1px border `#2A3038`.
- Active variant: Background `rgba(255, 106, 26, 0.12)`, border `rgba(255, 106, 26, 0.40)`, text `#FF6A1A`.

### Diagnostic & Status Trackers
- Multi-step mechanical progress bars showing vehicle repair stages. Complete steps illuminated in `#FF6A1A`, pending steps muted in `#2A3038`.