---
name: Velvet Sip
colors:
  surface: '#fff8f7'
  surface-dim: '#dfd9d8'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f2f1'
  surface-container: '#f3eceb'
  surface-container-high: '#ede7e6'
  surface-container-highest: '#e8e1e0'
  on-surface: '#1d1b1b'
  on-surface-variant: '#4f4443'
  inverse-surface: '#33302f'
  inverse-on-surface: '#f6efee'
  outline: '#817473'
  outline-variant: '#d2c3c1'
  surface-tint: '#6f5957'
  primary: '#6f5957'
  on-primary: '#ffffff'
  primary-container: '#f4d7d4'
  on-primary-container: '#725c5a'
  inverse-primary: '#dcc0bd'
  secondary: '#50644c'
  on-secondary: '#ffffff'
  secondary-container: '#d0e6c8'
  on-secondary-container: '#546850'
  tertiary: '#6c5d39'
  on-tertiary: '#ffffff'
  tertiary-container: '#f0dcaf'
  on-tertiary-container: '#6f603c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f9dcd9'
  primary-fixed-dim: '#dcc0bd'
  on-primary-fixed: '#271816'
  on-primary-fixed-variant: '#564240'
  secondary-fixed: '#d3e9cb'
  secondary-fixed-dim: '#b7cdb0'
  on-secondary-fixed: '#0e1f0d'
  on-secondary-fixed-variant: '#394c36'
  tertiary-fixed: '#f5e0b4'
  tertiary-fixed-dim: '#d8c599'
  on-tertiary-fixed: '#241a01'
  on-tertiary-fixed-variant: '#534524'
  background: '#fff8f7'
  on-background: '#1d1b1b'
  surface-variant: '#e8e1e0'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
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
  xl: 32px
  xxl: 48px
  container-margin: 20px
  gutter: 16px
---

## Brand & Style

The brand personality is energetic, sweet, and highly visual, catering to a Gen-Z demographic that values "Instagrammable" aesthetics and fluid digital experiences. This design system focuses on a **Modern-Tactile** aesthetic—a blend of soft Minimalism and Glassmorphism that feels as light and airy as milk foam. 

The emotional response should be one of "effortless joy." The UI utilizes high-quality photography of condensation on glasses and vibrant tea textures, framed within a "floating layers" architecture. Depth is created not through heavy borders, but through color-tinted shadows and translucent surfaces, making the interface feel like a collection of light objects resting on a soft, cohesive base.

## Colors

The palette is inspired by natural ingredients, processed through a high-key, pastel lens to ensure the UI feels fresh rather than heavy. 

- **Primary (Strawberry Pink):** Used for primary actions, highlight states, and celebratory moments.
- **Secondary (Matcha Green):** Used for health-conscious categories, sustainability badges, and success states.
- **Tertiary (Passion Fruit Yellow):** Used for rewards, "New" labels, and high-energy promotions.
- **Neutral (Milk Tea Beige):** The grounding force of the system, used for large background containers and subtle UI separators.
- **Surface (Clean White):** Essential for the "floating" effect, providing the necessary contrast against the soft neutral backgrounds.

## Typography

This design system uses a dual-font strategy to balance trendiness with extreme readability. **Montserrat** provides a bold, geometric foundation for headlines, giving the brand a modern and confident voice. **Plus Jakarta Sans** is used for body text and labels; its soft curves and high legibility at small sizes complement the rounded UI elements.

Typography should be treated with generous leading (line-height) to maintain the "airy" feel. Avoid pure black text; instead, use a deep, warm charcoal (`#4A423E`) to maintain softness and reduce visual strain against the pastel backgrounds.

## Layout & Spacing

The layout philosophy is **Fluid-Organic**. We utilize a 12-column grid for desktop and a 4-column grid for mobile, but the content is never "boxed in." Elements should frequently break the vertical rhythm with staggered card heights or overlapping imagery to simulate bubbles rising.

Spacing is based on a 4px scale, but the default "breathing room" should favor the `lg` (24px) and `xl` (32px) increments. Whitespace is not just empty space in this design system; it is a structural element that defines the "airiness" of the brand. Horizontal margins on mobile are set to 20px to ensure touch targets are comfortable and content doesn't feel cramped.

## Elevation & Depth

Depth is the defining characteristic of this design system. We use **Multi-Layered Ambient Shadows** to achieve the "floating" effect. Instead of a single dark shadow, we use two:
1.  **The Glow:** A soft, wide-spread shadow tinted with the primary color at very low opacity (5%).
2.  **The Lift:** A slightly tighter, neutral-colored shadow that provides the actual physical lift.

**Backdrop Blurs:** High-level containers (like navigation bars or modal overlays) use a `20px` background blur with a semi-transparent white fill (80% opacity). This ensures that as the user scrolls, the vibrant colors of the "bubbles" and tea imagery bleed through softly, maintaining the layered feel.

## Shapes

The shape language is defined by **Extreme Rounding**. All primary containers (cards, buttons) should use a minimum of `1rem` (16px) corner radius. 

- **Standard Elements:** 16px (rounded-lg)
- **Large Cards/Featured Content:** 24px (rounded-xl)
- **Interactive Chips/Search Bars:** Fully rounded (Pill-shaped)

The goal is to eliminate sharp edges entirely, mimicking the soft, chewy nature of boba pearls. This creates a friendly and safe environment for the younger target audience.

## Components

### Buttons
Primary buttons use a subtle vertical gradient (e.g., Light Pink to Soft Peach) to create a "squishy," 3D feel. They should have a soft, tinted shadow that expands slightly when hovered. Text should be bold and uppercase for maximum clarity.

### Cards
Cards are the primary content vehicle. They must have a white background, no border, and the "floating" multi-layered shadow. Images within cards should have a slightly smaller corner radius than the card itself to create a nested, organic look.

### Filter Chips
Chips are pill-shaped. When inactive, they have a soft neutral background. When active, they transition to a solid pastel color with a subtle inner glow. The transition should be a smooth spring animation to reinforce the youthful vibe.

### Input Fields
Fields are oversized with 16px padding. Instead of a dark border, use a thick 2px border in a very light neutral tone, which shifts to the Primary Pink when focused. The focus state should also trigger a subtle "lift" shadow.

### Interactive Add-ons
Include "Floating Action Buttons" (FAB) for quick-cart access. These should be perfectly circular, using a vibrant gradient and a more pronounced elevation than standard buttons to denote their importance.