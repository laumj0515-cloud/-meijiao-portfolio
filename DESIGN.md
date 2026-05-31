---
name: Meijiao Portfolio System
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5c5f60'
  on-secondary: '#ffffff'
  secondary-container: '#e1e3e4'
  on-secondary-container: '#626566'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b1a'
  on-tertiary-container: '#868382'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e1e3e4'
  secondary-fixed-dim: '#c5c7c8'
  on-secondary-fixed: '#191c1d'
  on-secondary-fixed-variant: '#454748'
  tertiary-fixed: '#e6e2df'
  tertiary-fixed-dim: '#cac6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-xl:
    fontFamily: Inter, PingFang SC
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 110%
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Inter, PingFang SC
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 120%
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter, PingFang SC
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 120%
  headline-md:
    fontFamily: Inter, PingFang SC
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 130%
  body-lg:
    fontFamily: Inter, PingFang SC
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 160%
  body-md:
    fontFamily: Inter, PingFang SC
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 160%
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 100%
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  container-max: 1440px
---

## Brand & Style

The design system is built for a personal portfolio that balances the precision of AI product management with a high-end editorial aesthetic. Inspired by the work of Olha Lazarieva, the style is **Minimalist and High-Contrast**, prioritizing clarity, intentionality, and sophisticated asymmetry. 

The goal is to evoke an emotional response of "Intelligence and Clarity." By using a stark neutral foundation, the system acts as a gallery frame, allowing the vibrant colors and complex imagery of specific AI projects to become the focal point. The visual language uses dramatic scale shifts and generous negative space to guide the user's attention through a narrative journey of technical expertise and product vision.

## Colors

The palette is strictly functional and architectural. The primary interaction color and typography color is a **Deep Charcoal (#1A1A1A)**, providing maximum contrast against the **Off-White (#F8F9FA)** canvas.

- **Surface (Primary):** Off-white background to reduce eye strain compared to pure white, while maintaining a clean, "gallery" feel.
- **Ink (Primary):** Deep charcoal for all essential text and structural lines.
- **Project Accents:** While the design system provides a default Blue (#0055FF), individual project pages are encouraged to override the accent color to reflect the specific branding of the AI product being showcased.

## Typography

This design system utilizes a "Mega-Scale" typography philosophy. Headlines are treated as graphic elements, often breaking the grid or spanning large portions of the viewport.

- **Primary Stack:** Inter is the primary typeface for its neutral, technical clarity. For Simplified Chinese characters, PingFang SC is used to maintain a modern, sans-serif aesthetic with consistent optical weight.
- **Hierarchy:** Use `display-xl` for section numbers or impactful hero statements. `headline-lg` is reserved for project titles. 
- **Character:** Tight letter-spacing on large headings creates a "compact" and high-impact look, while body text maintains generous leading (1.6x) for readability in long-form product case studies.

## Layout & Spacing

The layout follows an **Asymmetric 12-Column Fluid Grid** with a fixed maximum width to ensure readability on large monitors.

- **Asymmetry:** Content should not always center-align. For example, a project description might occupy columns 2-6, while the hero image occupies columns 7-12.
- **Rhythm:** Use an 8px base unit. Section spacing should be aggressive—vertical gaps of 160px or 240px are recommended between major sections to emphasize the minimalist "void."
- **Mobile Reflow:** On mobile devices, the 12-column grid collapses into a single-column stack with 24px side margins. Oversized headers should scale down using the `-mobile` variants to ensure they don't break the viewport.

## Elevation & Depth

This design system avoids traditional shadows and depth metaphors. It is a strictly **Flat / Tonal** system.

- **Stacking:** Depth is communicated through layering and overlapping. Elements (like images or floating labels) can overlap the edges of other containers to create a sense of physical arrangement without using drop shadows.
- **Lines:** Use 1px or 2px solid charcoal lines (#1A1A1A) to separate sections or define card boundaries where necessary.
- **Interactions:** Hover states should use color fills (solid blocks of color) rather than elevation changes.

## Shapes

The shape language is primarily **Sharp and Architectural**. 

- **Corner Radius:** A "Soft" setting (0.25rem) is used only for interactive components like buttons and input fields to make them feel slightly more approachable. 
- **Project Cards:** Large project cards and images should remain perfectly sharp (0px) to mimic the look of printed editorial layouts and high-end photography.
- **Masking:** Use geometric masks (circles or 45-degree cuts) occasionally for AI-themed decorative elements to break the rectangular dominance.

## Components

### Buttons
Primary buttons are solid #1A1A1A blocks with white Inter Semibold text. They should have no shadows and use a "fill" transition on hover, perhaps expanding slightly in width.

### Project Cards
Large-scale containers. The image is the primary focus, often taking up 100% of the card width. Text meta-data (Project Name, Year, Role) should be placed either directly below in a clean grid or floating in a high-contrast label.

### Lists
Experience and skill lists should use thin 1px horizontal dividers. Use `label-caps` for list headers. The layout should be asymmetric—labels on the left, descriptions on the right with a large gap.

### Navigation
A minimalist top bar. Use a fixed-position "Floating Frame" style or a simple text-based menu. On scroll, the navigation can hide or become a small circular "Menu" button to maximize whitespace for the content.

### Input Fields
Used for contact forms. Bottom-border only (ghost style) with #1A1A1A 1px lines. Labels should stay small and sit above the line. Focus state shifts the line weight to 2px.