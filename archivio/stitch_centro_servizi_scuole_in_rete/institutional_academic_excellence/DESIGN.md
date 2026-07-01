---
name: Institutional Academic Excellence
colors:
  surface: '#f8faf7'
  surface-dim: '#d9dad8'
  surface-bright: '#f8faf7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f1'
  surface-container: '#edeeec'
  surface-container-high: '#e7e9e6'
  surface-container-highest: '#e1e3e0'
  on-surface: '#191c1b'
  on-surface-variant: '#404945'
  inverse-surface: '#2e3130'
  inverse-on-surface: '#f0f1ee'
  outline: '#707975'
  outline-variant: '#bfc9c4'
  surface-tint: '#306859'
  primary: '#00352a'
  on-primary: '#ffffff'
  primary-container: '#0f4d3f'
  on-primary-container: '#84bdab'
  inverse-primary: '#98d2bf'
  secondary: '#325f9a'
  on-secondary: '#ffffff'
  secondary-container: '#93bdfe'
  on-secondary-container: '#194c85'
  tertiary: '#243129'
  on-tertiary: '#ffffff'
  tertiary-container: '#3a473f'
  on-tertiary-container: '#a7b5aa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b4efdb'
  primary-fixed-dim: '#98d2bf'
  on-primary-fixed: '#002019'
  on-primary-fixed-variant: '#135042'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#a6c8ff'
  on-secondary-fixed: '#001c3a'
  on-secondary-fixed-variant: '#124780'
  tertiary-fixed: '#d8e6db'
  tertiary-fixed-dim: '#bccabf'
  on-tertiary-fixed: '#121e17'
  on-tertiary-fixed-variant: '#3d4a41'
  background: '#f8faf7'
  on-background: '#191c1b'
  surface-variant: '#e1e3e0'
typography:
  display-lg:
    fontFamily: Merriweather
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Merriweather
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Merriweather
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 44px
  headline-md:
    fontFamily: Merriweather
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Source Sans 3
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is anchored in a **Modern Institutional** aesthetic that balances the gravity of educational administration with a contemporary, accessible warmth. It targets educational professionals and institutions, demanding an environment that feels authoritative yet never cold.

The visual narrative is defined by:
- **Sophisticated Order:** A rigorous adherence to hierarchy and whitespace that signals competence and reliability.
- **Editorial Polish:** Utilizing high-quality serif typography to evoke the feeling of established academic journals and official documentation.
- **Organic Professionalism:** Moving away from sterile corporate greys toward a warmer, "paper-like" palette that feels more human and tactile.
- **Quiet Precision:** Subtle elevations and soft edges that provide a modern user experience without sacrificing the conservative values of a government-adjacent service center.

## Colors

The color strategy utilizes a high-contrast but low-vibrancy palette to maintain an aura of "Institutional Calm."

- **Foundation:** The primary background (#F4F4F0) acts as a warm, off-white canvas, reminiscent of high-grade stationery. Pure white (#FFFFFF) is reserved exclusively for elevated surfaces and interactive cards to create a clear "layering" effect.
- **Brand Core:** "Institutional Forest" (#0F4D3F) is the anchor, used for primary navigation and key calls to action. It is complemented by "Professional Blue" (#184B84), used sparingly for secondary accents or links to distinguish different service categories.
- **Typography:** Text is never pure black. Using #1D2420 ensures deep legibility while maintaining a subtle green undertone that harmonizes with the brand. Secondary text (#5D6A61) provides enough contrast for accessibility while softening the visual density of long-form content.

## Typography

The typographic system creates a dialogue between tradition and modernity. 

- **Headlines:** Merriweather is used for all major titles. Its sturdy serifs and open forms communicate authority and trust. For Large Display titles, a slightly negative letter spacing is applied to create a more compact, "premium" editorial feel.
- **Body & UI:** Source Sans 3 provides high legibility for data-heavy administrative interfaces. It is a workhorse font that remains neutral and clear at small sizes.
- **Hierarchy:** Maintain clear vertical rhythm by using the `body-lg` for introductory paragraphs and `body-md` for general content. Labels should frequently use uppercase with increased letter spacing to denote section headers or metadata without needing excessive weight.

## Layout & Spacing

This design system employs a **Fixed-Fluid Hybrid** grid. Content is centered within a 1280px container on desktop to prevent excessive line lengths and maintain focus.

- **Rhythm:** An 8px base unit drives all spacing decisions. Large sections should be separated by 80px or 120px to provide the "breathing room" required for a premium feel.
- **The "Bento" Logic:** Cards and content blocks should use a 24px gutter. On mobile, the grid collapses to a single column with 20px side margins.
- **Sectional Backgrounds:** Use the Primary and Secondary brand colors as ultra-soft, low-opacity gradients (e.g., 5% opacity) to subtly distinguish between different landing page sections without using hard horizontal lines.

## Elevation & Depth

Depth is used sparingly to maintain a clean, "flat-plus" appearance. 

- **Surface Strategy:** Background elements sit on the #F4F4F0 base. Primary content containers (cards, modals) are pure white (#FFFFFF).
- **Soft Elevation:** Shadows must be extremely diffused. Use a "Soft Institutional Shadow": `0px 4px 20px rgba(29, 36, 32, 0.06)`. This creates a subtle lift that makes cards feel tangible but integrated.
- **Interactive Depth:** Upon hover, a card's shadow should slightly expand and the element should lift by 2px to provide tactile feedback.
- **Borders:** Use a 1px solid border in a slightly darker shade than the background (`#E2E2DC`) for elements that require definition but no elevation.

## Shapes

The shape language is characterized by **Soft Geometric Precision**. 

- **Primary Corners:** A base radius of 8px (0.5rem) is used for standard buttons and input fields, balancing approachable softness with professional structure.
- **Large Containers:** Cards and major section containers use 16px (1rem) for a more modern, friendly presence. 
- **Icons:** Should follow a "Line Art" style with 1.5px or 2px strokes and slightly rounded caps to match the UI's geometry.

## Components

- **Buttons:** Primary buttons use the Forest Green (#0F4D3F) with white text. Secondary buttons use an outline of the same green or the Professional Blue (#184B84) for specific actions like "Support" or "Resources." Padding should be generous (12px 24px).
- **Cards:** Cards are the primary content vehicle. They feature #FFFFFF backgrounds, the "Soft Institutional Shadow," and 16px corner radius. Headlines within cards should be `headline-md` (Merriweather).
- **Input Fields:** Use a subtle background fill (#FFFFFF) with a 1px border (#E2E2DC). On focus, the border transitions to Forest Green with a 2px outer "glow" in the same color at 10% opacity.
- **Chips/Badges:** Small, 4px rounded capsules with low-saturation backgrounds (e.g., light blue or light green tints) and dark text to categorize school services or document types.
- **Lists:** Use "Invisibly Framed" lists—horizontal separators should be thin, light lines (`#E2E2DC`) that do not touch the edges of the container, maintaining an airy feel.
- **Micro-interactions:** Transitions for hover states and page loads should be "Elegant Ease": `cubic-bezier(0.4, 0, 0.2, 1)` over 300ms. No "bouncing" or aggressive movement.