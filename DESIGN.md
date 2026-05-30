---
name: Industrial Heritage
colors:
  surface: '#fff8f7'
  surface-dim: '#f5d2ce'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ee'
  surface-container: '#ffe9e6'
  surface-container-high: '#ffe2de'
  surface-container-highest: '#fedbd6'
  on-surface: '#291715'
  on-surface-variant: '#5e3f3c'
  inverse-surface: '#402b29'
  inverse-on-surface: '#ffedea'
  outline: '#936e6a'
  outline-variant: '#e8bcb7'
  surface-tint: '#c00014'
  primary: '#bb0013'
  on-primary: '#ffffff'
  primary-container: '#e71520'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4ab'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#006193'
  on-tertiary: '#ffffff'
  tertiary-container: '#007bb8'
  on-tertiary-container: '#fcfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000d'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#91ccff'
  on-tertiary-fixed: '#001e31'
  on-tertiary-fixed-variant: '#004b72'
  background: '#fff8f7'
  on-background: '#291715'
  surface-variant: '#fedbd6'
  slate-dark: '#2D3436'
  slate-gray: '#636E72'
  timber-warm: '#D7B899'
  timber-light: '#F2EBE3'
  surface-muted: '#F4F4F4'
typography:
  display-lg:
    fontFamily: Domine
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Domine
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Domine
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Domine
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The brand personality is rooted in durability, heritage, and uncompromising quality. It caters to the premium construction and interior design market in India, where trust is built through longevity and structural integrity.

The design system adopts a **Corporate / Modern** style infused with **Industrial-Chic** elements. It balances the raw, tactile nature of plywood with a sophisticated, high-end digital presence. The visual language uses heavy whitespace to denote premium positioning, while sharp, professional architectural imagery anchors the brand in real-world application. Key brand assets, like the "25 Years Warranty" badge, are treated as trust-marks that break the grid to draw immediate attention.

## Colors

The palette is centered around a "Vibrant Brand Red" extracted from the core logo, serving as the primary action color for high-impact CTAs and branding elements. 

To achieve an industrial-chic feel, we utilize **Slate Greys** for primary text and structural UI elements, moving away from pure black to add depth and professional polish. **Subtle Wood Tones** (Timber Warm/Light) are used as sophisticated backgrounds for card sections and dividers, subtly referencing the physical product without being literal. Crisp White remains the dominant background color to maintain a "clean" and "premium" aesthetic.

## Typography

This design system uses a strategic pairing of a sturdy serif and a utilitarian sans-serif. 

**Domine** is selected for headlines to mirror the "old standard" serif of the brand heritage, providing an authoritative and established feel. It should be used for all major display and section headings. 

**Inter** handles all functional UI, body copy, and labels. Its neutral, high-readability profile balances the character of the serif, ensuring the interface feels modern and efficient. Labels and "Warranty" markers should utilize Inter in Bold with slight tracking (letter-spacing) to evoke industrial stamping and specification sheets.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop, centered to create a sense of focus and exclusivity. We employ a 12-column grid with generous 24px gutters.

The spacing rhythm is intentional and expansive. Large "Section Gaps" (120px) are used to separate different product tiers or brand stories, preventing the UI from feeling "cluttered" or "cheap." On mobile, margins tighten to 16px, and the grid collapses to a single column, but the vertical rhythm remains airy to maintain the premium feel. Use the 8px base unit for all component-level padding and internal spacing.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**.

1.  **Base Layer:** Pure white or `timber-light` for large sections.
2.  **Card Layer:** Pure white surfaces with "extra-diffused" low-opacity shadows (e.g., Blur: 30px, Y: 10px, Opacity: 6% Slate Dark). This makes the plywood product cards appear to float elegantly over the timber-toned backgrounds.
3.  **Interactive Layer:** Buttons and active states use a sharper shadow or a slight scale increase (1.02x) to suggest tactile feedback.

Avoid heavy borders; instead, use 1px `surface-muted` strokes for subtle definition if tonal separation isn't sufficient.

## Shapes

The shape language is **Soft (Level 1)**. 

While the product (plywood) is inherently rectangular and sharp-edged, the UI introduces 0.25rem (4px) corner radii to make the digital experience more approachable and modern. Large containers and product cards use `rounded-lg` (8px). 

**Badges & Seals:** The "Premium Quality" and "Warranty" badges should remain perfectly circular or follow the oval geometry of the primary logo to contrast against the structured, rectangular grid of the rest of the site.

## Components

### Buttons
Primary buttons use the Brand Red background with White text. They should have a minimum width to feel "sturdy" and use the `label-md` type style. Secondary buttons use a Slate Dark outline with a transparent background.

### Cards
Product cards are the centerpiece. They feature a white background, soft ambient shadows, and `rounded-lg` corners. Content should include a high-resolution texture crop of the plywood, the "25 Years Warranty" badge in the top-right corner, and technical specifications in `label-sm` grey text.

### Badges
The "25 Years Warranty" badge is a high-contrast element. It should be treated as a "seal of quality" using either the Brand Red or a Slate Dark circular container with white centered typography.

### Input Fields
Inputs should be clean and industrial, using a 1px `slate-gray` border and 4px border-radius. Use `surface-muted` for the background to make the white cards pop.

### Lists & Technical Specs
Use horizontal dividers in `surface-muted` and paired labels (e.g., **Thickness:** 18mm) to present technical data clearly, mimicking an architectural specification sheet.