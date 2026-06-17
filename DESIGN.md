---
name: Stature & Clarity
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45474c'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f73'
  primary: '#091426'
  on-primary: '#ffffff'
  primary-container: '#1e293b'
  on-primary-container: '#8590a6'
  inverse-primary: '#bcc7de'
  secondary: '#4648d4'
  on-secondary: '#ffffff'
  secondary-container: '#6063ee'
  on-secondary-container: '#fffbff'
  tertiary: '#001721'
  on-tertiary: '#ffffff'
  tertiary-container: '#002d3d'
  on-tertiary-container: '#3e9ac0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e3fb'
  primary-fixed-dim: '#bcc7de'
  on-primary-fixed: '#111c2d'
  on-primary-fixed-variant: '#3c475a'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#c0e8ff'
  tertiary-fixed-dim: '#7bd1fa'
  on-tertiary-fixed: '#001e2b'
  on-tertiary-fixed-variant: '#004d66'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  h1:
    fontFamily: Inter
    fontSize: 3.75rem
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.75'
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  section-padding: 120px
  container-max: 1280px
  gutter: 32px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is built for a professional who commands presence through expertise and quiet confidence. The aesthetic is rooted in **Corporate Modernism** with a focus on high-end editorial clarity. It avoids the sterile coldness of standard SaaS templates by introducing tonal depth and sophisticated layering.

The target audience consists of executive recruiters, potential partners, and high-level clients who value precision, reliability, and modern sensibility. The UI should evoke a sense of "architectural calm"—organized, intentional, and unmistakably professional. We utilize heavy whitespace and strict typographic hierarchies to ensure the user's focus remains on the professional's achievements and thought leadership.

## Colors

The palette is anchored by **Slate Blue (#1E293B)**, providing a deep, authoritative foundation for headers and primary actions. To introduce visual interest beyond a standard corporate look, we employ a dual-accent strategy: **Indigo (#6366F1)** for primary interactive elements and **Sky Blue (#7DD3FC)** for softer highlights and subtle indicators.

The background is strictly **#F8FAFC**, a deliberate off-white that reduces eye strain and provides a premium "matte" feel compared to pure white. Section differentiation is achieved through subtle shifts to a slightly cooler grey tint (#F1F5F9) rather than using heavy borders, maintaining a seamless, fluid transition between content blocks.

## Typography

Using **Inter** exclusively across all levels ensures a highly systematic and functional appearance. The distinction is created through aggressive scale and weight contrast. 

Headlines utilize "Extra Bold" weights and tight letter-spacing to create a "stature" effect, mimicking high-end business journals. Body text is set with generous line-height to ensure readability and a feeling of openness. We use a specialized "Label-Caps" style for overlines and category tags to provide a secondary layer of information without competing with the primary headings.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for desktop, centered within the viewport to maintain a curated, gallery-like feel. We use a 12-column grid with wide 32px gutters to allow the professional content to breathe.

The spacing rhythm is based on a 4px baseline, but emphasizes large vertical gaps (120px+) between major sections to enforce the "Clarity" aspect of the brand. This prevents the portfolio from feeling cluttered. Content blocks should be stacked using consistent "Stack" tokens to maintain rhythmic alignment across different pages.

## Elevation & Depth

To maintain a modern, professional look, this design system avoids heavy shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

1.  **Surfaces:** The primary surface is #F8FAFC. Secondary surfaces (cards or inset sections) use #FFFFFF or #F1F5F9.
2.  **Depth:** Depth is conveyed through thin, 1px borders in #E2E8F0. 
3.  **Shadows:** When necessary (e.g., for hovering over a project card), use a single, highly diffused "Ambient Shadow": `0 20px 25px -5px rgba(30, 41, 59, 0.04)`. The shadow color is tinted with the primary Slate Blue to keep the palette cohesive.

## Shapes

The shape language is **Soft (Level 1)**. Elements use a 0.25rem (4px) base radius. This creates a subtle hint of approachability while maintaining the sharp, disciplined look of a traditional professional document. 

Large containers like project cards may scale up to 0.5rem (8px) for a slightly more modern feel, but buttons and input fields should remain at the base 4px to keep the UI looking crisp and precise.

## Components

### Buttons
- **Primary:** Solid #1E293B background with white text. High-contrast, no shadow, 4px radius.
- **Secondary:** Outline #E2E8F0 with #1E293B text. Transitions to a light #F1F5F9 fill on hover.
- **Ghost:** Indigo (#6366F1) text with no background, used for less prominent actions or "Read More" links.

### Cards & Sections
- **Project Cards:** White (#FFFFFF) background with a 1px #E2E8F0 border. Use the Sky Blue (#7DD3FC) for small accent bars or category tags to pull interest.
- **Section Tints:** Alternate sections between #F8FAFC and #F1F5F9 to create visual separation without needing horizontal dividers.

### Form Inputs
- Fields use a white background with a 1px #E2E8F0 border. Focus states transition the border to Indigo (#6366F1) with a soft 2px outer glow of the same color at 10% opacity.

### Navigation & Identity
- Navigation is minimalist. Use the "Label-Caps" typography for nav links to ensure they feel like structural elements rather than primary content.
- Include a "Stature Bar": a thin 4px vertical accent of Indigo (#6366F1) at the start of major section titles to provide a consistent visual anchor throughout the scrolling experience.