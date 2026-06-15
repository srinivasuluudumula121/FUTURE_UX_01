---
name: Premium Dental Identity
colors:
  surface: '#fff8f5'
  surface-dim: '#ead6cc'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ea'
  surface-container: '#feeadf'
  surface-container-high: '#f8e4da'
  surface-container-highest: '#f2dfd4'
  on-surface: '#231913'
  on-surface-variant: '#564337'
  inverse-surface: '#392e27'
  inverse-on-surface: '#ffede4'
  outline: '#897365'
  outline-variant: '#ddc1b1'
  surface-tint: '#964900'
  primary: '#964900'
  on-primary: '#ffffff'
  primary-container: '#e57a1f'
  on-primary-container: '#4e2300'
  inverse-primary: '#ffb786'
  secondary: '#7c5543'
  on-secondary: '#ffffff'
  secondary-container: '#fec9b1'
  on-secondary-container: '#795240'
  tertiary: '#416743'
  on-tertiary: '#ffffff'
  tertiary-container: '#78a178'
  on-tertiary-container: '#113718'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc6'
  primary-fixed-dim: '#ffb786'
  on-primary-fixed: '#311400'
  on-primary-fixed-variant: '#723600'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#efbba4'
  on-secondary-fixed: '#2f1406'
  on-secondary-fixed-variant: '#623e2d'
  tertiary-fixed: '#c2eec0'
  tertiary-fixed-dim: '#a7d1a5'
  on-tertiary-fixed: '#002107'
  on-tertiary-fixed-variant: '#294f2d'
  background: '#fff8f5'
  on-background: '#231913'
  surface-variant: '#f2dfd4'
typography:
  display-hero:
    fontFamily: Epilogue
    fontSize: 72px
    fontWeight: '600'
    lineHeight: 80px
    letterSpacing: -0.02em
  hero-heading:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.01em
  section-heading:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  card-heading:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  stat-display:
    fontFamily: Epilogue
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
  body-reg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  nav-button:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 22px
  small:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 18px
  section-heading-mobile:
    fontFamily: Epilogue
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1280px
  content-width: 1200px
  gutter: 24px
  margin-mobile: 20px
  hero-padding-y: 120px
---

## Brand & Style

This design system establishes a visual language where premium healthcare meets editorial luxury. The aesthetic is defined by "Warm Minimalist Professionalism"—moving away from the cold, clinical whites of traditional dentistry toward a sophisticated, lifestyle-oriented experience. 

The strategy utilizes high-fashion editorial layouts characterized by generous whitespace, floating layered geometry, and a sophisticated color story. The goal is to evoke a sense of calm authority, modern reliability, and bespoke care. Every interaction should feel intentional and "soft," utilizing large-radius curves and ambient depth to reassure the patient while maintaining the precision of a high-end medical institution.

## Colors

The palette is anchored in organic, earthy tones that differentiate from the typical blue/green medical spectrum. 

- **Primary Brand Orange (#E57A1F):** Used for primary actions, calls to emotion, and "trust points." It provides energy and warmth.
- **Premium Brown (#4A2A1A):** Replaces black for text and structural blocks to add a sense of luxury, heritage, and depth.
- **The Warm Neutral Tier:** The primary background is a cream wash (#FAF7F3), paired with a slightly deeper neutral surface (#F5F4F2) and pure white (#FFFFFF) for elevated cards. This tri-tone neutral approach creates a sophisticated "layered" effect without needing heavy lines.
- **Success Accent (#7DA67D):** A muted sage used for trust badges, success states, and health indicators.

## Typography

The system uses a dual-font strategy. **Epilogue** (acting as a premium alternative to Clash Display) provides a modern, geometric character for headlines and statistics, ensuring the brand feels "editorial." 

**Plus Jakarta Sans** is used for all functional UI, body copy, and navigation. Its soft curves complement the brand’s geometry while maintaining high legibility for medical information. Large line heights (1.6x - 1.7x for body) are essential to maintain the "airy" luxury feel. Headlines should use tight tracking (-1% to -2%) for a more impactful, contemporary look.

## Layout & Spacing

This system utilizes a **12-column fixed-grid model** for desktop, centered within a 1280px viewport. The hallmark of the layout is "Macro-Spacing"—using 120px gaps between major vertical sections to prevent visual clutter and give the user's eyes room to breathe.

- **Desktop (1280px+):** 1200px content area, 12 columns, 24px gutters.
- **Tablet (768px - 1024px):** 8 columns, 40px margins, 16px gutters.
- **Mobile (Under 768px):** 4 columns, 20px margins, fluid stacking. Section spacing reduces to 64px.

Elements should be aligned to a strict 8pt grid to maintain rhythm. Floating cards should often bleed slightly off-center or overlap section boundaries to create a sense of dynamic depth.

## Elevation & Depth

Hierarchy is established through **Ambient Depth** rather than stark borders. The system uses three primary elevation tiers:

1.  **Base Layer:** The Warm Cream (#FAF7F3) page background.
2.  **Surface Layer:** Subtle Containers (#F5F4F2) with no shadows, used to group related content like service lists.
3.  **Elevated Layer:** Pure White (#FFFFFF) cards featuring "Healthcare Ambient Shadows"—very low-opacity, large-radius blurs (e.g., `0px 12px 32px rgba(74, 42, 26, 0.05)`). The brown primary text color is used as the shadow tint to keep it warm and organic.

Interactive elements like buttons should gain a slightly more pronounced shadow on hover to simulate physical "lift."

## Shapes

The shape language is "Hyper-Rounded," moving away from clinical sharpness to communicate approachability.

- **Pill Shapes (999px):** Reserved for buttons, navigation links, and tags/chips.
- **Hero Containers:** 36px radius for the most significant visual containers.
- **Standard Cards:** 28px radius for high-level sections.
- **Internal Cards:** 24px radius for service or doctor modules.
- **Form Inputs:** 18px radius to balance the pill-shaped buttons.

Image assets should always carry a minimum of a 24px radius to match the container language.

## Components

### Buttons
- **Primary:** Pill-shaped, #E57A1F background, White text. Subtle elevation.
- **Secondary:** Pill-shaped, transparent with a 1.5px border of #EAE7E2, or #F5F4F2 background. Text in #4A2A1A.
- **Icon Buttons:** Circular containers with 50% opacity icons for a "glass" effect when overlaying images.

### Cards
- **Service Cards:** White background, 28px radius, 32px internal padding. Features a top-aligned icon and bottom-aligned "Learn More" link.
- **Doctor Profiles:** Large image with a 24px radius, with a floating white card overlapping the bottom edge containing the name and specialty.

### Form Elements
- **Inputs:** 18px radius, #FAF7F3 background with a 1px #EAE7E2 border. Focus state moves the border to #E57A1F.
- **Labels:** 14px Plus Jakarta Sans SemiBold in #4A2A1A.

### Navigation
- **Header:** Sticky, blurred backdrop (Glassmorphism) with a pill-shaped "Book Now" primary button.
- **Footer:** High-contrast #4A2A1A background with White or Cream text, utilizing 4-column layout for links and locations.