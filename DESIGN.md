---
name: Structural Vitality
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#564334'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#897362'
  outline-variant: '#ddc1ae'
  surface-tint: '#904d00'
  primary: '#904d00'
  on-primary: '#ffffff'
  primary-container: '#ff8c00'
  on-primary-container: '#623200'
  inverse-primary: '#ffb77d'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5d5f5f'
  on-tertiary: '#ffffff'
  tertiary-container: '#a9aaaa'
  on-tertiary-container: '#3d3f3f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77d'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e3e2e2'
typography:
  display:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
spacing:
  base: 4px
  unit-1: 4px
  unit-2: 8px
  unit-4: 16px
  unit-6: 24px
  unit-8: 32px
  unit-12: 48px
  unit-16: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The brand personality for this design system is authoritative, industrious, and dependable. It bridges the gap between the raw power of heavy machinery and the precision of modern engineering. The target audience includes property developers, site managers, and commercial stakeholders who value transparency and strength.

The aesthetic follows a **Modern Brutalist** direction. It utilizes high-contrast intersections, heavy strokes, and an unyielding grid to convey structural integrity. While the visuals are "rugged," the implementation remains clean through generous whitespace, ensuring the UI feels like a professional tool rather than an unpolished draft. The emotional response should be one of absolute confidence—a digital representation of a job site that is safe, organized, and moving at full speed.

## Colors

The palette is rooted in safety and utility. **Construction Orange (#FF8C00)** serves as the primary action color, used for high-visibility interactive elements and critical emphasis. **Deep Black (#1A1A1A)** provides the structural framework, used for heavy headers, backgrounds, and primary text. 

A scale of utilitarian grays is used for auxiliary information, mimicking the tones of concrete and steel. Success, warning, and error states should avoid pastel variants; instead, use saturated, industrial-grade tones to maintain the high-contrast aesthetic.

## Typography

The typography system is designed for maximum impact and legibility. **Montserrat** is the engine for headlines, utilizing heavy weights and uppercase styling to mimic the "boldness" of architectural blueprints and site signage. 

**Inter** handles the heavy lifting for body copy and data. Its neutral, systematic nature ensures that technical details remain highly readable even in dense layouts. Vertical rhythm is strictly enforced with a 4px baseline grid, ensuring that every line of text feels aligned to an invisible structural frame.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop and a **Fluid Grid** for mobile. On desktop (1440px+), the content is housed within a 1280px wide container.

- **Desktop:** 12-column grid, 24px gutters, 64px outer margins.
- **Tablet:** 8-column grid, 24px gutters, 32px outer margins.
- **Mobile:** 4-column grid, 16px gutters, 16px outer margins.

Spacing follows a strict 4px base unit. Use generous "Construction-scale" padding (32px or 48px) to separate major sections, reinforcing the feeling of vast open space and organized job sites.

## Elevation & Depth

To maintain the rugged, flat aesthetic, this design system avoids soft ambient shadows. Instead, it uses **Structural Tiering** and **Bold Outlines**:

1.  **Level 0 (Base):** Light gray (#F5F5F5) or White.
2.  **Level 1 (Cards/Panels):** Pure white with a 2px solid black border. 
3.  **Level 2 (Active/Hover):** A "Hard Shadow" effect—a solid 4px offset in Deep Black or Construction Orange with 100% opacity. 

Depth is communicated through thickness and color fill rather than light simulation. Overlays use a high-opacity black backdrop (80%) to maintain the high-contrast feel of the brand.

## Shapes

The shape language is strictly **Sharp (0px roundedness)**. This reinforces the "Built" nature of the brand, reflecting steel beams, cut stone, and architectural precision. 

Every interactive element—buttons, input fields, containers—must feature 90-degree corners. Diagonal slashes (45-degree angles) may be used as decorative accents or "caution striping" in patterns to add visual interest without compromising the structural rigidity of the UI.

## Components

### Buttons
- **Primary:** Solid Construction Orange, uppercase bold text in Deep Black. Sharp corners. 2px black bottom border for "weight."
- **Secondary:** Solid Deep Black, white text.
- **Ghost:** Transparent background, 2px black border.

### Inputs & Fields
- Fields must have a 2px solid Deep Black border. 
- Labels are always positioned above the field in `label-bold` style.
- Focus state: Border color changes to Construction Orange with a 4px solid shadow offset.

### Cards
- White background, 2px solid black border.
- Header sections of cards should use a Deep Black background with white typography for clear hierarchy.

### Status Indicators
- Use heavy, filled blocks for status tags (e.g., "In Progress," "Completed"). 
- No icons-only buttons; icons should always be accompanied by labels to ensure industrial-grade clarity.

### Data Visualization
- Bar charts should use solid blocks of Orange and Black. 
- Grid lines should be prominent (1px solid light gray) to mimic graph paper or blueprints.