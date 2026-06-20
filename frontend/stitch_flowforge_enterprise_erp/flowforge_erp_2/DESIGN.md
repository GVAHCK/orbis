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
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h1-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  h2:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  h4:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  caption:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  button:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 0.25rem
  sm: 0.5rem
  md: 1rem
  lg: 1.5rem
  xl: 2.5rem
  gutter: 1.5rem
  margin: 2rem
  max-width: 1440px
---

## Brand & Style

This design system is engineered for high-velocity enterprise resource planning, balancing the information density required for operational excellence with the refined aesthetics of modern SaaS leaders. The brand personality is **authoritative yet fluid**, designed to reduce the cognitive load of complex data management.

The visual style is **Modern Corporate with a Tonal Layering approach**. It draws inspiration from the utility of Linear and the approachable clarity of Notion. It utilizes a refined "Glass-Enterprise" aesthetic—where critical data sits on solid surfaces, while utility panels and navigation overlays utilize subtle backdrop blurs and semi-transparent layers to maintain spatial context. The result is a UI that feels light and breathable, even when displaying vast amounts of relational data.

## Colors

The color palette is anchored by deep, sophisticated plums (`primary` and `secondary`) which establish a professional, executive tone. The `accent` emerald provides a high-contrast focal point for primary actions and growth indicators.

Functional colors (Success, Warning, Danger) follow industry standards to ensure immediate recognition in dashboards. In Light Mode, the `background` is a cool neutral, allowing the `surface` (white) containers to pop via subtle elevation. In Dark Mode, the system shifts to a deep navy architecture, utilizing `card` overlays to create a sense of hierarchy and depth without excessive brightness.

## Typography

This design system utilizes **Inter** exclusively to leverage its exceptional legibility in data-dense environments. The scale is built on a high-contrast rhythm, where display and header levels use tighter tracking and heavier weights to command attention.

For operational views, `body-sm` and `caption` are the workhorses. Use `label-caps` for table headers and section overlines to provide clear structural markers without competing with the content. Ensure line heights for body text remain generous (1.5–1.6x) to maintain readability in long-form reports and multi-column forms.

## Layout & Spacing

The system uses a **12-column fluid grid** for dashboard views and a **fixed-center grid** (1440px max) for document and settings pages. The spacing logic is based on a 4px baseline, ensuring all components align perfectly with the typographic grid.

- **Desktop:** 2rem margins, 1.5rem gutters. Sidebars should be collapsible to maximize workspace.
- **Tablet:** 1.5rem margins, 1rem gutters.
- **Mobile:** 1rem margins, 0.5rem gutters. Layouts reflow to a single column.

Priority is given to **Density Control**. Data-heavy tables should offer "Compact" and "Comfortable" modes, toggling vertical padding between `xs` and `md` units.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Soft Shadows**. Instead of heavy blacks, shadows use a tinted primary color (e.g., `#714B67` at 8% opacity) to feel integrated into the surface.

1.  **Level 0 (Background):** Solid `#F8FAFC`. Used for the main canvas.
2.  **Level 1 (Surface):** Solid White with a 1px border (`#E2E8F0`). Used for cards and primary content containers.
3.  **Level 2 (Navigation/Glass):** White at 80% opacity with a 20px backdrop blur. Used for sticky headers and floating sidebars to maintain a sense of space.
4.  **Level 3 (Popovers/Modals):** Solid White with a `0 10px 25px -5px` tinted shadow. These should appear to float significantly above the content.

## Shapes

The shape language is consistently **Rounded (8px / 0.5rem)**, reflecting a modern, approachable enterprise feel. 

- **Small Components (Inputs, Buttons, Chips):** Use the base `rounded` (8px).
- **Medium Components (Cards, Modals):** Use `rounded-lg` (16px) to define major content areas.
- **Large Components (Sections, Hero areas):** Use `rounded-xl` (24px) for distinct architectural breaks.
- **Interactive States:** Use a 2px focus ring with 4px offset to ensure accessibility without breaking the radius.

## Components

- **Buttons:** Primary buttons use a solid `#714B67` fill with white text. Secondary buttons use a subtle background tint or ghost-border style. 
- **Input Fields:** Use a 1px border in `#E2E8F0` that transitions to the Primary Plum on focus. Labels sit outside the field in `caption` style.
- **Chips/Badges:** Utilize a soft tint of the functional color (e.g., 10% opacity Success Green) with high-contrast text for status indicators. 
- **Cards:** White surfaces with 8px radius and a subtle 1px border. Avoid heavy shadows unless the card is interactive or draggable.
- **Data Tables:** Use alternating row stripes (Zebra) in `#F8FAFC` for high-density readability. The header row should be pinned with a glassmorphism blur during scroll.
- **Global Search:** A persistent, centered floating bar (Command + K) utilizing a heavy backdrop blur and 16px radius.