---
name: Gourmet Pop & Fizz
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#edeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#4e4632'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#807660'
  outline-variant: '#d2c5ab'
  surface-tint: '#745b00'
  primary: '#745b00'
  on-primary: '#ffffff'
  primary-container: '#f6c400'
  on-primary-container: '#695200'
  inverse-primary: '#f2c000'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2e1'
  on-secondary-container: '#656464'
  tertiary: '#4c6700'
  on-tertiary: '#ffffff'
  tertiary-container: '#b3d763'
  on-tertiary-container: '#445d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe08c'
  primary-fixed-dim: '#f2c000'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#584400'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#cbf079'
  tertiary-fixed-dim: '#afd360'
  on-tertiary-fixed: '#141f00'
  on-tertiary-fixed-variant: '#384e00'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  caption:
    fontFamily: Montserrat
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is built to evoke a sense of high-energy indulgence and social joy. It balances the artisanal quality of a gourmet brand with the playful, explosive nature of popcorn. The personality is extroverted, appetizing, and unapologetically bold, targeting a younger, food-savvy demographic that values "shareable" aesthetic moments.

The design style is a hybrid of **Modern Minimalism** and **High-Contrast Boldness**. It utilizes expansive white space to let high-resolution product photography breathe, while punctuating the interface with vibrant, saturated color blocks. Visual interest is maintained through soft, tactile depth and large, rounded geometry that mimics the organic shape of the product itself.

## Colors

The palette is driven by a sunny, appetizing "Gourmet Gold" primary and a sophisticated "Midnight Onyx" secondary. 

- **Primary (#F6C400):** Used for key brand moments, primary CTAs, and active states. It evokes the warmth of butter and the premium quality of the product.
- **Secondary (#111111):** A deep, grounding black used for high-impact typography, buttons, and structural elements to provide a premium, modern contrast.
- **Tertiary (#7A9B2E):** A "Zesty Lime" green used for highlighting natural ingredients, specialty flavor profiles, and organic badges.
- **Surface (#F9F9FB):** A clean, soft neutral canvas that ensures high-resolution photography remains the hero of the experience.

## Typography

This design system uses **Plus Jakarta Sans** for headlines to achieve a soft, rounded, and contemporary friendly-bold aesthetic. Its generous x-height and open counters make it highly impactful for brand messaging. 

**Montserrat** is used for body text and labels to provide a clean, geometric structure that maintains readability at smaller sizes. 

- All headlines should use tight letter-spacing to appear more cohesive and "popped."
- Body copy should maintain standard tracking for optimal legibility during longer reading sessions.
- Use `label-bold` for navigation and small call-outs to create a rhythmic contrast with the softer headlines.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a focus on generous internal padding to create a "breathable" luxury feel.

- **Grid:** A 12-column system for desktop and a 4-column system for mobile. 
- **Rhythm:** An 8px base unit drives all spacing.
- **Margins:** Desktop layouts utilize wide 64px side margins to center the content and focus the eye on product photography. 
- **Vertical Spacing:** Use `xl` (80px) spacing between major sections to emphasize the "editorial" feel of the brand.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Tonal Layering**. 

- **Surface Levels:** The base layer is Neutral (#F9F9FB). Elevated cards use a very soft, diffused shadow (Blur: 30px, Y: 10px) with a 5% opacity of the Midnight Onyx secondary color.
- **Active Depth:** Interaction triggers a "press-in" effect where shadows shrink, or a "lift" effect where shadows expand and the element scales slightly (1.02x).
- **Glassmorphism:** Navigation bars use a high-blur (20px) backdrop filter with 80% opacity white to keep the product imagery visible as users scroll.

## Shapes

The shape language is defined by **High Roundedness**, mirroring the organic and soft nature of popped kernels.

- **Standard Elements:** Buttons and input fields use a `rounded-lg` (1rem/16px) radius.
- **Container Elements:** Product cards and hero sections use `rounded-xl` (1.5rem/24px) to create a soft, friendly frame for imagery.
- **Special Elements:** Feature badges and flavor tags use a full-pill shape to distinguish them from functional UI components.

## Components

### Buttons
- **Primary:** Solid #F6C400 with #111111 text for maximum visibility. High-contrast, 16px rounded corners. Hover state: Lighten by 10% and shift up 2px.
- **Secondary:** Solid #111111 with white text or outlined with 2px #F6C400 for flavor-specific CTAs.
- **Size:** Large touch targets (min 48px height) to accommodate social-media-style mobile browsing.

### Cards
- White background with soft ambient shadows. 
- Images should have a 1:1 or 4:5 aspect ratio and fill the top half of the card.
- Content within cards should have `md` (24px) padding.

### Input Fields
- Soft grey background (#F9F9FB) with a 2px border that turns #F6C400 on focus.
- Labels sit above the field in `label-bold` style.

### Chips & Badges
- Used for "Gluten Free," "Vegan," or "Limited Edition" tags.
- Use #7A9B2E for ingredient-based health callouts.
- Use full pill-shaped rounding and `caption` typography. 

### Interactive Hover
- Any interactive element (cards, buttons, icons) should utilize a smooth 200ms transition.
- Use a "bounce" easing function for a more playful, energetic feel.