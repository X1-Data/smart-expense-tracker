---
name: Quiet AI Ledger
colors:
  surface: '#fafaf5'
  surface-dim: '#dadad6'
  surface-bright: '#fafaf5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4ef'
  surface-container: '#eeeeea'
  surface-container-high: '#e8e8e4'
  surface-container-highest: '#e2e3de'
  on-surface: '#1a1c1a'
  on-surface-variant: '#424842'
  inverse-surface: '#2f312e'
  inverse-on-surface: '#f1f1ec'
  outline: '#727971'
  outline-variant: '#c2c8bf'
  surface-tint: '#44664a'
  primary: '#44664a'
  on-primary: '#ffffff'
  primary-container: '#7a9e7e'
  on-primary-container: '#13341c'
  inverse-primary: '#aad0ad'
  secondary: '#8e4e14'
  on-secondary: '#ffffff'
  secondary-container: '#ffab69'
  on-secondary-container: '#783d01'
  tertiary: '#006e24'
  on-tertiary: '#ffffff'
  tertiary-container: '#45a952'
  on-tertiary-container: '#00370e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c6ecc8'
  primary-fixed-dim: '#aad0ad'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#2d4e33'
  secondary-fixed: '#ffdcc4'
  secondary-fixed-dim: '#ffb780'
  on-secondary-fixed: '#2f1400'
  on-secondary-fixed-variant: '#6f3800'
  tertiary-fixed: '#93f998'
  tertiary-fixed-dim: '#78dc7e'
  on-tertiary-fixed: '#002106'
  on-tertiary-fixed-variant: '#005319'
  background: '#fafaf5'
  on-background: '#1a1c1a'
  surface-variant: '#e2e3de'
typography:
  h1:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
  body:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  button:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 20px
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
  container-max: 1200px
  gutter: 20px
---

## Brand & Style

The design system is rooted in the concept of **Quiet Tech**—a philosophy that prioritizes calm over clutter and mindfulness over data density. The brand personality is that of a supportive companion: approachable, non-judgmental, and exceptionally organized. It bridges the gap between traditional paper journaling and modern AI efficiency.

The visual style is a blend of **Minimalism** and **Soft Tactility**. It avoids the sterile coldness of typical fintech applications by utilizing a warm, organic color palette and generous whitespace. The interface should feel like high-quality stationery: tactile, structured, and inviting. AI interactions are never depicted as robotic; instead, they are treated as "magic dust" (✨) that silently organizes the user's financial life.

## Colors

The palette is anchored by **Sage Green (#7A9E7E)**, chosen for its associations with growth and tranquility. The foundation is a **Warm Cream (#F8F7F2)** background which reduces eye strain compared to pure white and reinforces the "paper" aesthetic.

- **Primary (Sage):** Used for primary actions, active states, and brand moments.
- **Surface (White):** Used for cards and floating containers to create subtle contrast against the cream background.
- **Semantic Colors:** 
    - **Income (#3FA34D):** A vibrant but natural green.
    - **Expense (#E57373):** A soft, desaturated red to prevent "financial anxiety."
    - **Streak (#F4A261):** A warm ochre for gamification and habit-tracking elements.
- **Borders:** A low-contrast stone hue (#EAE7DD) is used to define structure without creating visual noise.

## Typography

This design system utilizes **Inter** for its exceptional legibility and systematic feel. To maintain the "cozy" atmosphere, tracking (letter spacing) is slightly tightened on headlines to create a more custom, editorial look.

- **Headlines:** Use Semibold weight to provide clear hierarchy against the cream background.
- **Body Text:** Set at 15px to balance information density with readability.
- **Labels:** Used for metadata, dates, and category tags. Often set in the Secondary Text color (#8A8678).
- **Mobile Scaling:** H1 scales down to 24px on mobile devices to ensure titles do not wrap awkwardly.

## Layout & Spacing

The layout philosophy follows a **Fluid Content** model with a maximum container width. We prioritize "breathable" interfaces with significant padding inside components to reinforce the calm mood.

- **Grid:** A 12-column system is used for desktop, collapsing to a single column for mobile.
- **Rhythm:** All spacing is based on a 4px baseline grid. 
- **Margins:** Desktop views use 32px (xl) page margins, while mobile views use 16px (md) to maximize horizontal space for data.
- **Stacking:** Vertical spacing between cards and sections should be generous (24px - 32px) to prevent the "cluttered dashboard" feeling typical of finance apps.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Soft Ambient Shadows** rather than stark physical displacement.

- **Base Layer:** The background (#F8F7F2) is the lowest level.
- **Surface Layer:** Cards and containers are White (#FFFFFF). They use a very subtle shadow (0px 2px 8px rgba(46, 46, 42, 0.06)) to appear as if they are resting lightly on a paper surface.
- **Interactions:** On hover, cards may lift slightly (0px 4px 12px rgba(46, 46, 42, 0.08)).
- **AI Layers:** AI-generated suggestions or sparkles (✨) use a subtle "glow" effect rather than a shadow, utilizing a low-opacity Sage Green outer blur.

## Shapes

The shape language is defined by **Soft Geometricism**. All interactive elements and containers feature generous corner radii to appear friendly and safe.

- **Containers/Cards:** 16px default radius.
- **Buttons:** 12px radius for a balanced, modern look.
- **Input Fields:** 10px radius.
- **Chips/Tags:** Fully rounded (pill) for categorical distinction.

## Components

### Buttons
- **Primary:** Background #7A9E7E, Text #FFFFFF. No heavy gradients; flat or very subtle 1px inner top border for tactility.
- **Secondary:** Background #FFFFFF, Border 1.5px #EAE7DD, Text #2E2E2A.
- **AI Action:** Background #FFFFFF, Border 1.5px #7A9E7E, Text #7A9E7E with a ✨ prefix.

### Input Fields
- Understated style. Background #FFFFFF, Border 1.5px #EAE7DD. On focus, the border changes to Sage Green (#7A9E7E) with a soft 2px outer glow.

### Cards
- White background, 16px corner radius, subtle shadow. Cards should have no borders unless they are nested inside another white container.

### Chips & Tags
- Used for categories (e.g., "Groceries", "Rent"). Light Sage or Light Cream backgrounds with 12px font-size labels.

### Icons
- **Style:** Outline only (Lucide/Phosphor style).
- **Weight:** 1.5px stroke for 24px icons; 2px stroke for 32px featured icons.
- **AI Element:** The sparkle icon (✨) is used exclusively for AI-assisted logging, smart categorization, and insight generation.

### Habit & Speed Elements
- **Quick-Log Button:** A floating, primary-colored button centered at the bottom of mobile screens for thumb-friendly access.
- **Streak Tracker:** Uses the Fire/Streak color (#F4A261) in a soft, pill-shaped badge to celebrate daily logging consistency.