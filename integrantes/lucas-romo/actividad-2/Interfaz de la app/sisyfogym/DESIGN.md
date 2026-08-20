---
name: SisyfoGym
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#39393A'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#c5c9ac'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#8f9378'
  outline-variant: '#444932'
  surface-tint: '#b0d500'
  primary: '#ffffff'
  on-primary: '#2a3400'
  primary-container: '#caf300'
  on-primary-container: '#596c00'
  inverse-primary: '#536600'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#ffffff'
  on-tertiary: '#303031'
  tertiary-container: '#e4e2e3'
  on-tertiary-container: '#656465'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#caf300'
  primary-fixed-dim: '#b0d500'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#e4e2e3'
  tertiary-fixed-dim: '#c8c6c7'
  on-tertiary-fixed: '#1b1b1c'
  on-tertiary-fixed-variant: '#474648'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
  energetic-lime: '#D4FF00'
  deep-charcoal: '#1A1A1B'
  outline-muted: '#444932'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 24px
  container-max: 1280px
---

## Brand & Style
The design system for this brand is a **High-Contrast Modern** aesthetic tailored for a high-performance fitness and wellness environment. It draws inspiration from the relentless pursuit of physical excellence, contrasted with the restorative luxury of a premium spa.

The visual narrative is defined by a "Dark Mode First" philosophy, creating a focused, private, and elite atmosphere. It utilizes heavy whitespace, precision typography, and tactical bursts of color to guide users through their training and recovery journeys. The style is aggressive yet refined—conveying power through bold weights and a "sanctuary" feel through sleek, uncluttered surfaces.

## Colors
The palette is engineered for maximum impact and legibility in low-light environments.

- **Primary (Energetic Lime):** This is the "vitality" color. It is reserved strictly for high-priority CTAs, progress indicators, and active states. It should appear as a vibrant spark against the dark background.
- **Secondary (White):** Used for primary headlines and essential data points to ensure absolute clarity and a premium editorial feel.
- **Tertiary (Surface Accents):** A slightly lifted charcoal used for card backgrounds and input fields to create depth without the need for high-contrast borders.
- **Neutral (Deep Charcoal):** The foundation of the system. It uses a non-pure black to reduce eye strain and provide a sophisticated canvas for photography.

## Typography
Typography balances aggressive athletic energy with structured luxury.

- **Headlines:** Montserrat is the voice of the brand. Use ExtraBold (800) for hero sections and impact statements. Letter spacing is slightly tightened on larger displays to maintain a compact, powerful aesthetic.
- **Body:** Inter provides a systematic, highly legible counterpoint for workout technicalities and spa menus.
- **Labels:** Use uppercase for `label-bold` with increased tracking to create an architectural, modern look for categories and tags.

## Layout & Spacing
This design system uses a **Fluid Grid** model. In high-end wellness, luxury is expressed through generous spacing and "breathing room."

- **Grid:** 12-column for desktop, 4-column for mobile devices.
- **Rhythm:** All spacing follows an 8px base unit. Vertical rhythm should favor the `lg` (48px) unit between major sections to emphasize the premium feel.
- **Reflow:** On mobile, content must maintain a 24px horizontal safe zone to create a "framed" photographic look. On desktop, content should be centered within the 1280px container.

## Elevation & Depth
Hierarchy is established through **Tonal Layers** and **Ambient Shadows**, creating a sense of physical objects floating in a dark space.

- **Layering:** Level 0 is the background. Level 1 surfaces (cards) use a slightly lighter neutral. Level 2 (modals) use the lightest grey tier with a distinct shadow.
- **Shadows:** Shadows are extra-diffused (30px+) and low-opacity. To keep the dark theme rich, tint shadows with pure black rather than neutral grey, creating a soft "ink" glow.
- **Blur:** Use a 20px backdrop blur on navigation bars and persistent headers. This maintains a connection to the high-resolution fitness photography beneath the UI while ensuring text contrast.

## Shapes
The shape language is **Rounded**, providing a "human-centric" and approachable contrast to the high-intensity colors and dark theme.

- **Standard Elements:** Use the base `rounded` (0.5rem) for smaller items.
- **Feature Components:** Buttons and main cards utilize `rounded-lg` (1rem) for a distinct, modern silhouette.
- **Hero Containers:** Use `rounded-xl` (1.5rem) on large images or container sections to soften the visual impact of the high-contrast palette.
- **Icons:** Ensure all iconography uses rounded line caps and corners to match the UI radius.

## Components
Consistent styling of components reinforces the "High-Performance" narrative across the product.

- **Buttons:**
    - **Primary:** Background in Energetic Lime with Charcoal text. Use Bold weights. Add a subtle lime outer glow (box-shadow) on hover to simulate energy.
    - **Secondary:** Transparent background with a 2px White border at 20% opacity.
- **Input Fields:** Use Tertiary (#2A2A2B) for the background. On focus, transition to a 2px Energetic Lime border.
- **Chips:** Small, pill-shaped tags for "Gym" or "Spa" categories. Use Tertiary backgrounds with White `label-sm` text.
- **Cards:** Incorporate high-resolution training photography. Apply a 40% black linear gradient (bottom-to-top) to ensure white typography remains readable over imagery.
- **Progress Bars:** Vital for workout tracking. Use Energetic Lime for the fill and Deep Charcoal for the track.
- **Lists:** Use subtle `outline-variant` dividers (1px) between list items to maintain structure without cluttering the dark canvas.