---
name: Elite Heritage
colors:
  surface: '#1e0f0e'
  surface-dim: '#1e0f0e'
  surface-bright: '#473533'
  surface-container-lowest: '#180a09'
  surface-container-low: '#271816'
  surface-container: '#2c1b1a'
  surface-container-high: '#372624'
  surface-container-highest: '#43302e'
  on-surface: '#fadcd8'
  on-surface-variant: '#e4beb9'
  inverse-surface: '#fadcd8'
  inverse-on-surface: '#3e2c2a'
  outline: '#ab8985'
  outline-variant: '#5b403d'
  surface-tint: '#ffb4ac'
  primary: '#ffb4ac'
  on-primary: '#690007'
  primary-container: '#a40011'
  on-primary-container: '#ffada5'
  inverse-primary: '#ba1a1e'
  secondary: '#c9c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#e9c176'
  on-tertiary: '#412d00'
  tertiary-container: '#674b0a'
  on-tertiary-container: '#e4bd72'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#93000e'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#1e0f0e'
  on-background: '#fadcd8'
  surface-variant: '#43302e'
  rubine-red: '#A40011'
  matte-black: '#0D0D0D'
  parisian-gold: '#C5A059'
  st-gallen-white: '#F4F4F4'
typography:
  display-xl:
    fontFamily: Bebas Neue
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 80px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bebas Neue
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0.03em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style

The design system establishes a "Sports Luxury" aesthetic for FC Besa St. Gallen, merging the intensity of professional football with the refined exclusivity of a boutique fashion house. The brand personality is aggressive yet sophisticated, targeting a modern audience that values heritage and high-performance lifestyle.

The visual style is a hybrid of **High-Contrast / Bold** and **Glassmorphism**. It utilizes dramatic lighting, deep shadows, and translucent layers to create a sense of depth and prestige. The emotional response is one of aspiration and belonging—moving the club identity from a local sports organization to a premium lifestyle brand.

**Core Principles:**
- **Editorial Impact:** Large-scale, condensed typography that commands attention.
- **Cinematic Depth:** Use of glassmorphism to layer information over high-action, dramatic photography.
- **Heritage Refined:** Integrating the club's red and black roots through a more muted, luxurious lens with gold accents.

## Colors

The palette is anchored in **dark mode** to emphasize the luxury "boutique" feel. 

- **Primary (Rubine Red):** A deeper, more saturated crimson than standard athletic red, used for high-impact actions and primary branding.
- **Secondary (Matte Black):** The foundation of the UI, providing a rich, velvet-like background that allows colors and imagery to pop.
- **Tertiary (Parisian Gold):** Reserved for victory elements, premium highlights, and delicate accents (e.g., thin borders, trophy icons).
- **Neutral (St. Gallen White):** An off-white used for high legibility in body text, preventing the harshness of pure #FFFFFF against dark backgrounds.

## Typography

Typography is a primary differentiator in this design system. We use a high-contrast pairing of a condensed display face and a technical, modern sans-serif.

- **Headlines:** **Bebas Neue** provides a vertical, editorial strength reminiscent of high-end sports journals. It should be used for all major headers and impact statements.
- **Body & Functional:** **Hanken Grotesk** offers a clean, sharp, and contemporary feel. Its precise geometry ensures legibility at small sizes while maintaining the professional tone of the brand.
- **Styling Note:** Headlines should frequently use "Parisian Gold" or "St. Gallen White" to maintain hierarchy. Use "Label-Caps" for secondary navigation or small metadata like "Match Date" or "Player Position."

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is built on "Section Blocks," where each content area is separated by significant vertical whitespace (`section-gap`) to allow the high-contrast imagery to breathe.

- **Desktop:** 12 columns / 24px gutter / 64px side margins.
- **Mobile:** 4 columns / 16px gutter / 20px side margins.
- **Asymmetry:** To mirror the dynamic movement of football, use asymmetrical layouts where text blocks and images overlap or are offset from the center axis.

## Elevation & Depth

Visual hierarchy is achieved through **Glassmorphism** and **Tonal Layering**. Surfaces are rarely opaque unless they are the base background.

- **Base Layer:** Matte Black (#0D0D0D).
- **Surface Layer:** Use semi-transparent dark fills (e.g., `rgba(20, 20, 20, 0.7)`) with a 12px-20px backdrop-blur. 
- **Accents:** 1px "Parisian Gold" borders with low opacity (20-30%) should be used to define card boundaries on dark backgrounds.
- **Shadows:** Avoid heavy black shadows. Instead, use "Glows"—faint, diffused Rubine Red or Gold outer glows—to indicate active or hovered states.

## Shapes

The shape language is **Soft (0.25rem)**. While the "Sports Luxury" vibe is sharp and aggressive, subtle rounding of corners adds a touch of modern refinement and makes the interface feel more approachable on mobile devices.

- **Buttons & Cards:** 4px (0.25rem) radius.
- **Large Sections/Banners:** Should remain sharp (0px) to emphasize the grid and structural integrity.

## Components

### Buttons
- **Primary:** Solid Rubine Red background, White Bebas Neue text (uppercase). No border.
- **Secondary:** Transparent background, 1px Parisian Gold border, Gold Hanken Grotesk text.
- **Ghost:** White text with a glassmorphic background for use over images.

### Cards & Information Info
- **Navigation Menu:** Fixed top bar with a deep backdrop blur and a thin Parisian Gold bottom border.
- **Player/News Cards:** Full-bleed imagery with a glassmorphic overlay at the bottom for text. Use high-contrast photography (deep blacks, bright highlights).

### Inputs & Selection
- **Form Fields:** Matte Black background with a 1px Dark Grey border. On focus, the border transitions to Rubine Red.
- **Checkboxes/Radios:** Square (4px radius) with Rubine Red fills when active.

### Imagery Guidance
- **Direction:** All photography must be high-contrast with dramatic directional lighting (chiaroscuro). 
- **Treatment:** Increase black points and apply a slight desaturation to all colors except for the club's Rubine Red. Action shots should feel frozen in time, emphasizing the grit and "premium" nature of the sport.