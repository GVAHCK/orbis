---
name: Forge Dark Operations
colors:
  surface: '#131316'
  surface-dim: '#131316'
  surface-bright: '#39393c'
  surface-container-lowest: '#0e0e11'
  surface-container-low: '#1b1b1e'
  surface-container: '#1f1f22'
  surface-container-high: '#2a2a2d'
  surface-container-highest: '#353438'
  on-surface: '#e4e1e6'
  on-surface-variant: '#d0c3cb'
  inverse-surface: '#e4e1e6'
  inverse-on-surface: '#303033'
  outline: '#998e95'
  outline-variant: '#4d444b'
  surface-tint: '#e4b9df'
  primary: '#e4b9df'
  on-primary: '#442643'
  primary-container: '#ab84a8'
  on-primary-container: '#3c1f3c'
  inverse-primary: '#755374'
  secondary: '#c7c5d0'
  on-secondary: '#303038'
  secondary-container: '#494851'
  on-secondary-container: '#b9b7c1'
  tertiary: '#bfcd94'
  on-tertiary: '#2a340b'
  tertiary-container: '#899663'
  on-tertiary-container: '#232d05'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd6fa'
  primary-fixed-dim: '#e4b9df'
  on-primary-fixed: '#2c112d'
  on-primary-fixed-variant: '#5c3c5b'
  secondary-fixed: '#e4e1ec'
  secondary-fixed-dim: '#c7c5d0'
  on-secondary-fixed: '#1b1b22'
  on-secondary-fixed-variant: '#46464e'
  tertiary-fixed: '#dbe9ae'
  tertiary-fixed-dim: '#bfcd94'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1f'
  background: '#131316'
  on-background: '#e4e1e6'
  surface-variant: '#353438'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  code-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-padding: 24px
  gutter: 16px
---

## Brand & Style

This design system is built for high-density enterprise environments, focusing on data clarity, reduced eye strain, and professional authority. The personality is precise, reliable, and premium, utilizing a **Corporate / Modern** aesthetic with a refined dark-mode approach.

The visual language balances the density of ERP workflows with a sophisticated depth model. By utilizing deep charcoal foundations and carefully calibrated purple accents, the system provides a focused environment for power users who spend long hours managing complex logistics and financial data. The overall feel is one of structured efficiency and modern industrial strength.

## Colors

The palette transitions to a deep-space foundation to optimize readability and reduce glare.
- **Primary:** The signature purple has been shifted to a lighter, more desaturated luminance (#A37DA0) for interactive states to ensure WCAG AA compliance against dark backgrounds, while the original brand purple (#714B67) remains reserved for non-functional brand moments.
- **Surface Strategy:** We use a three-tier depth system. The base surface is a near-black charcoal. The container level provides the primary workspace background, and the "high" level is reserved for elevated cards and modals.
- **Typography Contrast:** Pure white is avoided to prevent "halo" effects. Instead, high-contrast off-white is used for primary content, and mid-tones are used for secondary labels and metadata.

## Typography

This design system utilizes **Inter** exclusively to leverage its exceptional legibility at small sizes, which is critical for dense ERP tables and dashboards. 

- **Weights:** Use Semi-Bold (600) for section headers and Bold (700) sparingly for primary KPIs.
- **Scale:** The hierarchy is tight. Body-md (14px) is the workhorse size for all data entries and form labels.
- **Optimization:** In dark mode, tracking (letter spacing) is slightly increased for small labels to prevent characters from visually "bleeding" together.

## Layout & Spacing

The layout follows a **Fluid Grid** model optimized for 12 columns on desktop. Because of the enterprise nature of the system, a high-density 4px baseline grid is used.

- **Density:** Tighten vertical spacing in data tables (8px cell padding) to maximize information density.
- **Margins:** Desktop views should maintain a 24px outer margin.
- **Breakpoints:**
  - Mobile: < 600px (4 columns)
  - Tablet: 600px - 1024px (8 columns)
  - Desktop: > 1024px (12 columns)
- **Sidebars:** Persistent left-hand navigation should be fixed at 240px to allow the primary content area to remain fluid.

## Elevation & Depth

In this dark mode environment, depth is communicated through **Tonal Layering** rather than heavy shadows. 

- **Stacking:** Elements closer to the user are lighter in color. The background is `#0F0F12`, cards sit on `#1C1C21`, and popovers/tooltips sit on `#2C2C34`.
- **Borders:** Subtle, low-contrast outlines (#3F3F46) are used on containers to define boundaries where tonal shifts are subtle.
- **Shadows:** When used (only for modals), use a 25% opacity pure black shadow with a 16px blur, ensuring no colored tints to maintain the professional "Operations" feel.

## Shapes

The design system employs a **Rounded** (8px) corner language across all primary UI components. This provides a modern, approachable feel that softens the "grid-heavy" nature of ERP interfaces.

- **Small Components:** Buttons and Input fields use 8px (0.5rem).
- **Medium Components:** Cards and Modals use 16px (1rem).
- **Large Components:** Outer layout containers may use 24px (1.5rem) if they are floating.

## Components

### Buttons
- **Primary:** Background #A37DA0, Text #0F0F12. Bold and clear.
- **Secondary:** Outlined with #3F3F46, Text #E2E2E6. 
- **Ghost:** No background, Text #A0A0A5, becomes #E2E2E6 on hover.

### Input Fields
- **Default:** Background #1C1C21, Border #3F3F46, Text #E2E2E6.
- **Focus State:** Border color shifts to #A37DA0 with a subtle outer glow.

### Cards
- Surfaces should use the `surface_container` color with 8px internal padding for high-density data displays. 
- Section headers within cards should have a subtle bottom border (#2C2C34).

### Data Tables
- Header row: Background #1C1C21, Text #A0A0A5 (All Caps, 12px Semi-bold).
- Rows: Alternating zebra striping is discouraged; use subtle thin horizontal dividers (#2C2C34) instead.

### Chips & Badges
- Use desaturated background tints (e.g., a dark forest green for "Success") with high-vibrancy text labels to ensure readability without overwhelming the dark interface.