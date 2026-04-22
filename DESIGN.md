---
name: Software Engineering Workshop Design System
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
  on-surface-variant: '#44474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#505e7c'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0b1b35'
  on-primary-container: '#7584a3'
  inverse-primary: '#b8c7e9'
  secondary: '#964900'
  on-secondary: '#ffffff'
  secondary-container: '#ff8928'
  on-secondary-container: '#642f00'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001f29'
  on-tertiary-container: '#008fb4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b8c7e9'
  on-primary-fixed: '#0b1b35'
  on-primary-fixed-variant: '#384763'
  secondary-fixed: '#ffdcc6'
  secondary-fixed-dim: '#ffb786'
  on-secondary-fixed: '#311300'
  on-secondary-fixed-variant: '#723600'
  tertiary-fixed: '#bbe9ff'
  tertiary-fixed-dim: '#5ed4ff'
  on-tertiary-fixed: '#001f29'
  on-tertiary-fixed-variant: '#004d63'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  code:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The brand personality for this design system is intellectual, precise, and authoritative. It is designed to bridge the gap between academic rigor and modern software engineering practices. The visual language conveys a sense of stability and institutional trust while maintaining the agility of a tech-forward event.

The design movement is **Corporate/Modern** with a strong leaning toward **Minimalism**. By prioritizing high-quality typography and intentional whitespace, the system ensures that complex technical schedules and research papers remain legible and accessible. The aesthetic is clean and structured, utilizing a systematic approach to depth and color to guide the user through information-heavy layouts.

## Colors

The palette is rooted in a scholarly "Midnight Navy" (#0B1B35), which serves as the primary color for navigation, headers, and core brand elements. This color establishes a foundation of professionalism and depth.

- **Primary (#0B1B35):** Used for high-emphasis UI elements and structural components.
- **Secondary (#F58220):** An energetic orange reserved for calls to action, important alerts, and highlighting active states. It provides a sharp contrast against the navy to draw focus.
- **Tertiary (#00CCFF):** A "Tech Cyan" used for decorative accents, link states, and categorization in technical content.
- **Neutral:** A range of cool greys derived from the navy base, used for borders, secondary text, and background surfaces to prevent visual fatigue.

The system defaults to a **light mode** to maintain an academic, paper-like feel, utilizing subtle off-white surfaces to distinguish between different content modules.

## Typography

This design system utilizes a dual-font strategy to balance technical innovation with readability. 

**Space Grotesk** is chosen for headlines. Its geometric and slightly eccentric character reinforces the "software engineering" theme, giving the workshop a modern, cutting-edge edge.

**Manrope** is used for all body text and interface labels. It was selected for its exceptional balance and contemporary proportions, ensuring that long-form academic abstracts and schedule details are easy to digest. 

A strict vertical rhythm is maintained with a 1.6 line-height for body text to optimize legibility. Letter spacing is slightly tightened on display text for a more impactful, editorial appearance.

## Layout & Spacing

The layout follows a **Fixed Grid** model to mirror the structured nature of academic publications. Content is centered within a 1200px container to ensure optimal line lengths for reading.

A 12-column grid system is employed with 24px gutters. 
- **Academic Content:** Primarily spans the central 8 columns to focus the user’s attention.
- **Schedules & Lists:** Utilize the full 12 columns for horizontal density.

Spacing follows an 8px linear scale, ensuring consistent mathematical relationships between all elements. Large `xl` (80px) vertical padding is used to separate major sections, creating a "breathable" and premium experience that prevents the information-heavy content from feeling overwhelming.

## Elevation & Depth

This design system uses **Tonal Layers** and **Low-contrast outlines** rather than heavy shadows to convey hierarchy. This approach maintains a clean, scholarly aesthetic without unnecessary visual noise.

- **Level 0 (Base):** The primary background (#FFFFFF).
- **Level 1 (Subtle):** Used for cards and secondary content sections, utilizing a very light grey surface (#F8FAFC) with a thin 1px border (#E2E8F0).
- **Level 2 (Interaction):** When an element is hovered or active, a very soft, diffused ambient shadow (10% opacity of Primary Navy) is applied to suggest lift.

Depth is primarily established through color blocking—using the dark primary navy for headers to create a "heavy" top-down hierarchy that grounds the page.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding of corners strikes a balance between the rigid formality of "Sharp" edges and the overly casual nature of "Rounded" or "Pill-shaped" elements.

- **Small Components:** Checkboxes, input fields, and small tags use a 4px (0.25rem) radius.
- **Container Elements:** Cards and featured sections use a `rounded-lg` (8px) radius to provide a modern, friendly touch without losing the professional engineering feel.
- **Visual Accents:** Square edges may be used for decorative elements or geometric patterns in the background to reinforce the "structured" theme.

## Components

### Buttons
Primary buttons use the dark navy background with white text. Secondary buttons (CTAs) use the secondary orange. Buttons should have a medium height (44px) and use `label-md` typography for clear intent.

### Cards
Cards are essential for displaying workshop sessions and speakers. They should use the Level 1 elevation (subtle background and border) with 24px internal padding. The header of the card should use the primary navy for titles to ensure visibility.

### Input Fields & Selects
Inputs use a white background with a 1px cool grey border. On focus, the border transitions to the primary navy with a subtle 2px tertiary cyan outer glow.

### Chips & Tags
Used for categorizing technical tracks (e.g., "DevOps", "AI", "Testing"). These use a light tint of the tertiary cyan with dark navy text to remain distinct from primary actions.

### Progress Indicators
For multi-day workshop schedules, use vertical steppers that utilize the secondary orange for the "active" or "current" session to provide immediate visual orientation.

### Code Snippets
Given the software engineering focus, code snippets should be housed in a dark-themed block (#0B1B35) with syntax highlighting that utilizes the secondary orange and tertiary cyan for contrast.