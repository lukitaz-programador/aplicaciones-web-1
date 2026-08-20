---
name: Vitality High-Performance System
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#39393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1b1b1c'
  surface-container: '#1f1f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353536'
  on-surface: '#e4e2e3'
  on-surface-variant: '#c5c9ac'
  inverse-surface: '#e4e2e3'
  inverse-on-surface: '#303031'
  outline: '#8f9378'
  outline-variant: '#444932'
  surface-tint: '#b0d500'
  primary: '#ffffff'
  on-primary: '#2a3400'
  primary-container: '#caf300'
  on-primary-container: '#596c00'
  inverse-primary: '#536600'
  secondary: '#c8c6c7'
  on-secondary: '#303031'
  secondary-container: '#49494a'
  on-secondary-container: '#bab8b9'
  tertiary: '#ffffff'
  on-tertiary: '#2f3131'
  tertiary-container: '#e2e2e2'
  on-tertiary-container: '#636565'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#caf300'
  primary-fixed-dim: '#b0d500'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#e5e2e3'
  secondary-fixed-dim: '#c8c6c7'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474647'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131314'
  on-background: '#e4e2e3'
  surface-variant: '#353536'
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
  headline-md:
    fontFamily: Montserrat
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
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

The design system is engineered to evoke a sense of elite performance and restorative luxury. It targets a demographic that values both physical intensity and mental wellness. The aesthetic is **High-Contrast Modern**, leaning into deep blacks and vibrant neon accents to create a "dark mode" first experience that feels private, focused, and high-end.

The style leverages heavy whitespace (even in dark themes), precision typography, and tactical use of "Energetic Lime" to guide the user’s eye toward action. It avoids clutter, prioritizing a "sanctuary" feel for the Spa sections and a "power" feel for the Gym sections through consistent, sleek surfaces.

## Colors

This design system utilizes a high-contrast palette to establish a premium, energetic atmosphere. 

- **Energetic Lime (#D4FF00):** Used exclusively for high-priority CTAs, progress indicators, and active states. It represents the "spark" of vitality.
- **Deep Charcoal (#1A1A1B):** The primary surface color. It provides a sophisticated, non-pure-black backdrop that reduces eye strain while maintaining a premium feel.
- **Clean White (#FFFFFF):** Used for primary headings and essential information to ensure maximum legibility against the dark background.
- **Surface Accents:** Use a slightly lighter neutral (#2A2A2B) for card backgrounds and input fields to create depth without relying on heavy borders.

## Typography

The typography strategy balances the aggressive, bold nature of fitness with the clean, structured nature of a luxury spa.

- **Headlines:** Montserrat is used for all headings. Use the ExtraBold (800) weight for hero sections to convey strength. Tighten letter spacing on larger sizes to maintain a compact, "impactful" look.
- **Body Text:** Inter provides a systematic and neutral counterpoint, ensuring high readability for workout descriptions, spa menus, and schedules.
- **Labels:** Use uppercase with increased letter spacing for small labels (e.g., categories, tags) to add a modern, editorial touch.

## Layout & Spacing

The design system employs a **Fluid Grid** model with generous internal padding to emphasize the "premium" feel—luxury is defined by the space you can afford to waste.

- **Grid:** A 12-column grid for desktop, 4-column for mobile.
- **Rhythm:** All spacing must be multiples of 8px. Use 24px (md) for standard gutters and 48px (lg) for vertical section breathing room.
- **Safe Zones:** Ensure a minimum of 24px horizontal margin on mobile devices to prevent content from touching the screen edges, maintaining the "framed" look of professional photography.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and extremely **Ambient Shadows**.

- **Level 0 (Background):** Pure #0F0F0F for the main canvas.
- **Level 1 (Cards/Surfaces):** Deep Charcoal (#1A1A1B). This is the default container for content.
- **Level 2 (Modals/Popovers):** Dark Grey (#2A2A2B) with a soft, diffused shadow.
- **Shadows:** Use large-blur (30px+), low-opacity (40%) shadows that are tinted with the background color (Black) rather than neutral grey. This creates a subtle "glow" effect rather than a harsh drop shadow.
- **Glassmorphism:** Apply a 20px backdrop blur to navigation bars and floating action buttons to maintain context of the background photography while ensuring text legibility.

## Shapes

The shape language is consistently **Rounded**, signifying a modern, approachable, and "human-centric" design.

- **Standard Elements:** Buttons, input fields, and small cards use a 16px (1rem) radius.
- **Large Containers:** Section containers and hero image masks can scale up to `rounded-xl` (24px) to create a distinct, soft-edged look that contrasts with the "hard" high-contrast colors.
- **Iconography:** Icons should feature rounded caps and corners to match the UI components.

## Components

- **Buttons:**
    - **Primary:** Background: Energetic Lime; Text: Deep Charcoal; Weight: Bold. No shadow, or a slight lime outer glow on hover.
    - **Secondary:** Border: 2px White (20% opacity); Text: White.
- **Input Fields:** Background: #2A2A2B; Border: None; Placeholder Text: #A1A1A1. On focus, add a 2px Energetic Lime border.
- **Chips:** Small, pill-shaped tags used for "Gym," "Spa," or "Yoga" categories. Background: #2A2A2B; Text: White; Font: `label-sm`.
- **Cards:** Use high-resolution photography as backgrounds for cards where possible. Overlay with a 40% black gradient from bottom-to-top to ensure text readability.
- **Progress Bars:** Use Energetic Lime for the active state and Deep Charcoal for the track. Essential for workout completion or membership status.
- **Navigation:** Bottom navigation (mobile) should be semi-transparent with a heavy backdrop blur, using Energetic Lime for active icons.