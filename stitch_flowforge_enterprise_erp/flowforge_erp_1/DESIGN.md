---
name: FlowForge ERP
colors:
  surface: '#fff7f9'
  surface-dim: '#e0d8da'
  surface-bright: '#fff7f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf1f4'
  surface-container: '#f4ecee'
  surface-container-high: '#efe6e9'
  surface-container-highest: '#e9e0e3'
  on-surface: '#1e1b1d'
  on-surface-variant: '#4e444a'
  inverse-surface: '#342f31'
  inverse-on-surface: '#f7eef1'
  outline: '#80747a'
  outline-variant: '#d1c3ca'
  surface-tint: '#79526f'
  primary: '#57344f'
  on-primary: '#ffffff'
  primary-container: '#714b67'
  on-primary-container: '#f0bfe0'
  inverse-primary: '#e9b8d9'
  secondary: '#7c5071'
  on-secondary: '#ffffff'
  secondary-container: '#fec7ed'
  on-secondary-container: '#7b4f70'
  tertiary: '#34451e'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b5d33'
  on-tertiary-container: '#c0d5a0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd7f1'
  primary-fixed-dim: '#e9b8d9'
  on-primary-fixed: '#2f1029'
  on-primary-fixed-variant: '#5f3b56'
  secondary-fixed: '#ffd7f1'
  secondary-fixed-dim: '#edb6dc'
  on-secondary-fixed: '#310e2b'
  on-secondary-fixed-variant: '#623958'
  tertiary-fixed: '#d5eab4'
  tertiary-fixed-dim: '#b9ce9a'
  on-tertiary-fixed: '#112000'
  on-tertiary-fixed-variant: '#3b4c24'
  background: '#fff7f9'
  on-background: '#1e1b1d'
  surface-variant: '#e9e0e3'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1440px
  gutter: 24px
  margin-desktop: 40px
  margin-mobile: 16px
  stack-xs: 4px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
  stack-xl: 48px
---

## Brand & Style
The design system is engineered for a world-class enterprise ERP environment where high information density must coexist with visual clarity. The brand personality is authoritative yet frictionless, blending the structural rigor of traditional enterprise software with the refined polish of modern developer tools.

The aesthetic follows a **Modern Corporate** direction with **Glassmorphism** accents. It prioritizes a "calm productivity" atmosphere—utilizing generous white space (inspired by Notion), precise mathematical spacing (inspired by Linear), and sophisticated depth (inspired by Stripe). The UI evokes an emotional response of total control and premium reliability, ensuring users feel empowered rather than overwhelmed by complex workflows.

## Colors
This design system employs a sophisticated, muted plum palette for its primary identity, signifying maturity and professional depth. The primary and secondary colors are reserved for high-level brand moments and primary actions.

- **Primary & Secondary:** Used for global navigation, active states, and primary call-to-actions.
- **Accent & Success:** The emerald accent provides a high-contrast focal point for interactive highlights, while the success green is dedicated to positive financial and operational status updates.
- **Neutral Palette:** A meticulous range of slate grays defines the structural hierarchy. In dark mode, the palette shifts to deep navy hues to reduce eye strain during long-form data management.
- **Functional Tinting:** Backgrounds use subtle blue-tints to maintain a "cool" professional temperature.

## Typography
The typography system utilizes **Inter** exclusively to achieve a systematic, utilitarian aesthetic that remains highly legible at small sizes. 

- **Scale:** A high-end type scale is used to create clear differentiation between data labels and editorial headers.
- **Tracking:** Negative letter-spacing is applied to larger display heads for a tighter, "Apple-esque" premium feel.
- **Utility:** Small labels (11px-13px) are prioritized for high-density ERP tables and sidebars, ensuring metadata is accessible without cluttering the interface.
- **Weight:** Semi-bold (600) is the preferred weight for interactive triggers and headers to maintain a strong visual anchor.

## Layout & Spacing
The layout philosophy centers on a **Fixed-Fluid hybrid grid**. The main content area utilizes a 12-column grid with a 24px gutter, while the sidebar navigation remains fixed at 280px to maximize vertical workflow efficiency.

- **Density:** Spacing is built on a 4px baseline grid. High-density data views (tables, kanbans) use "Compact" spacing (8px-12px padding), while landing pages and dashboard overviews use "Spacious" units (24px-48px).
- **Safe Areas:** Consistent 40px outer margins on desktop ensure content feels framed and premium.
- **Responsive Behavior:** On tablet, the sidebar collapses into a rail or drawer. On mobile, the 12-column grid reflows to a single column with 16px horizontal margins.

## Elevation & Depth
Elevation is communicated through **Tonal Layering** and **Ambient Shadows**. Instead of heavy blacks, shadows use a tinted primary/neutral mix with high diffusion.

- **Levels:** 
  - `Base`: Background layer (#F8FAFC).
  - `Flat`: Surface cards with a 1px border (#E2E8F0) and no shadow.
  - `Raised`: Modals and dropdowns featuring a "Soft Glass" effect (backdrop-blur: 12px) and a multi-layered shadow (0px 10px 15px -3px rgba(0,0,0,0.05)).
- **Glassmorphism:** Used sparingly for global headers and floating action bars to maintain context of the content beneath while providing a premium, modern edge.

## Shapes
The shape language is defined by a refined **Rounded (0.5rem)** base, transitioning to **Rounded-XL (1.5rem)** for major structural containers like dashboard cards and primary buttons.

- **Buttons & Inputs:** Use the `rounded-lg` (1rem) standard to feel approachable yet precise.
- **Data Cells:** Use `rounded-sm` (2px-4px) or sharp corners to maximize horizontal space in dense tables.
- **Selection States:** Focus rings and selection indicators should follow the radius of their parent element precisely.

## Components
Consistent component behavior is vital for an ERP's steep learning curve.

- **Buttons:** Primary buttons use `rounded-xl` with a subtle top-light inner shadow to appear "tactile." 
- **Data Tables:** High-density with sticky headers. Rows use a hover state highlight (#F1F5F9). Borderless cells with 12px vertical padding.
- **Kanban Boards:** Cards utilize the `card_dark` or `surface_light` tokens with a 1px border. Drag-and-drop states are indicated by a 2px accent-colored dashed outline.
- **Input Fields:** Minimum height of 40px. Use `label-md` for floating labels. Focus state uses a 2px spread of the primary color at 20% opacity.
- **Analytics Widgets:** Incorporate Sparklines and Donut charts using the Secondary and Success color tokens. Backgrounds for widgets should feature a subtle gradient (Surface to Background) to denote depth.
- **Chips:** Small, `rounded-pill` shapes with low-opacity background tints of the status color (e.g., Success green at 10% opacity for "Paid" invoices).