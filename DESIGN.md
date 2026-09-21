---
name: By You Design System
colors:
  surface: '#fff8f6'
  surface-dim: '#e7d7d2'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ec'
  surface-container: '#fbeae5'
  surface-container-high: '#f5e5e0'
  surface-container-highest: '#f0dfda'
  on-surface: '#221a17'
  on-surface-variant: '#584237'
  inverse-surface: '#382e2b'
  inverse-on-surface: '#feede8'
  outline: '#8c7265'
  outline-variant: '#dfc0b1'
  surface-tint: '#9d4300'
  primary: '#9d4300'
  on-primary: '#ffffff'
  primary-container: '#ff7b25'
  on-primary-container: '#602600'
  inverse-primary: '#ffb690'
  secondary: '#006b5c'
  on-secondary: '#ffffff'
  secondary-container: '#68fadd'
  on-secondary-container: '#007261'
  tertiary: '#6a5b54'
  on-tertiary: '#ffffff'
  tertiary-container: '#af9d95'
  on-tertiary-container: '#41352f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#68fadd'
  secondary-fixed-dim: '#44ddc1'
  on-secondary-fixed: '#00201a'
  on-secondary-fixed-variant: '#005145'
  tertiary-fixed: '#f3ded5'
  tertiary-fixed-dim: '#d6c3ba'
  on-tertiary-fixed: '#241914'
  on-tertiary-fixed-variant: '#51443e'
  background: '#fff8f6'
  on-background: '#221a17'
  surface-variant: '#f0dfda'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  prompt-card:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 2.5rem
  space-3xl: 3rem
  card-margin-x: 1.25rem
  card-padding: 2rem
---

## Brand & Style

This design system expresses intimate vulnerability, authentic playfulness, and heartfelt connection. Built for moments where two or more individuals let down their guards to share stories, it pairs warm humanism with a tactile, editorial game aesthetic.

The target audience spans friends, couples, and thoughtful conversationalists seeking depth beyond superficial exchanges. The visual tone evokes safety, warmth, and joyful curiosity.

The visual style blends **Tactile Organic Modernism** with warm editorial elements:
- Generous, organic corner curves mimicking real paper card stock.
- Saturated citrus energy balanced with grounding teal and tender peach underlays.
- Tactile, physics-informed card surfaces that feel ready to flip, swipe, and explore.

## Colors

The palette balances joyful warmth with calming depth:

- **Primary (`#FF7B25`)**: Radiates warmth, spontaneous honesty, and infectious vitality. Applied to focal interactive controls, card highlights, and key brand moments.
- **Secondary (`#00BFA5`)**: A rich, vibrant teal that anchors deep reflection, introspective categories, and balancing counterpoints.
- **Tertiary (`#FDE8DF`)**: A soothing peach tint that acts as the primary canvas wash, eliminating harsh digital glare and giving surfaces a soft parchment quality.
- **Neutral (`#2D2421`)**: Warm charcoal infused with deep espresso undertones, delivering optimal legibility without the sterile chill of pure black.
- **Card Background (`#FFFFFF`)**: Pure, crisp card stock to establish contrast against the tinted parchment app canvas (`#FAF5EF` and `#FFF0EB`).

## Typography

The type system uses **Plus Jakarta Sans** across all roles to unify the friendly, modern editorial rhythm. Its open apertures, warm geometry, and clean terminal strokes provide approachable clarity for conversational prompts.

- **Display & Headlines**: Generous weights (`700` and `800`) with tight letter-spacing give card headings and deck titles a friendly, magazine-like weight.
- **Prompt Card (`prompt-card`)**: The emotional core of the system. Sized at 22px with an expansive line height (32px) to allow deep reflective questions to breathe naturally.
- **Body & Labels**: Standard body text remains comfortably legible at regular weight, while micro-labels and pill chips use bold, tracked uppercase or sentence case for immediate scanning.

## Layout & Spacing

The layout embraces mobile-first vertical intimacy. It relies on fluid container framing with generous internal negative space to replicate holding physical cards.

- **Grid Model**: A centered single-column card viewport on mobile devices (max-width `420px`), framed by `1.25rem` (`20px`) safe-edge margins. On tablet/desktop screens, content remains anchored inside a centered `480px` mobile preview viewport to preserve intimate card-deck proportions.
- **Vertical Rhythm**: Built upon an `8px` base grid. Interactive primary buttons sit parked in a dedicated bottom action bay elevated with safe-area paddings (`space-xl` bottom clearance).
- **Breathing Room**: Card interiors enforce a minimum `2rem` (`32px`) padding around conversational questions, ensuring text never feels crowded by badges or decorative footer waves.

## Elevation & Depth

Visual hierarchy uses warm, diffuse ambient drop shadows that simulate real playing cards layered on a cloth surface:

- **Level 0 (Flat Canvas)**: Soft tint background (`#FFF0EB` / `#FAF5EF`) with no elevation.
- **Level 1 (Stacked Deck Backdrop)**: Underneath cards in a swipe stack use subtle offsets (`0 4px 12px rgba(45, 36, 33, 0.04)`), angled slightly (between -3° and +3°) to suggest physical card depth.
- **Level 2 (Active Prompt Card)**: Main active conversation cards lift into focus with a dual ambient shadow: `0 8px 24px -4px rgba(255, 123, 37, 0.12), 0 4px 12px rgba(45, 36, 33, 0.06)`. The subtle warm orange tint warms the elevation without muddiness.
- **Level 3 (Floating Action & Modals)**: Floating controls and bottom-sheet drawers utilize `0 16px 36px -6px rgba(45, 36, 33, 0.14)`.

## Shapes

The shape system adopts a pill-shaped and ultra-rounded philosophy (`roundedness: 3`):

- **Conversation Cards**: Custom ultra-rounded radius of `28px` to `32px`, mimicking rounded physical bridge cards and welcoming touch.
- **Primary Buttons & Action Chips**: Full pill shape (`border-radius: 9999px`) to create an inviting, squeeze-friendly tactile surface.
- **Illustrative Blobs & Card Accents**: Organic, undulating asymmetric curves layered behind questions to reinforce the handmade warmth of the visual identity.

## Components

### Conversation Card (Core Component)
- **Container**: White (`#FFFFFF`) surface, `32px` corner radius, `2rem` internal padding. Enforces a standard aspect ratio of `3:4` or `4:5`.
- **Header Slot**: Holds a pill-shaped category chip (left-aligned) and deck progress counter (right-aligned).
- **Prompt Area**: Centered question set in `prompt-card` style with warm neutral text (`#2D2421`).
- **Footer Bar**: Solid or semi-translucent accent band (e.g. secondary teal `#00BFA5`) with white category caption text (`label-sm`).

### Buttons
- **Primary Action**: Pill shape (`9999px`), bold Plus Jakarta Sans label, vibrant orange fill (`#FF7B25`), pure white text, with a subtle warm glow on press.
- **Secondary Action**: Pill shape, warm cream fill (`#FAF5EF`), subtle teal text (`#00BFA5`), zero border.
- **Ghost / Icon Button**: Circular (`48px` x `48px`), soft peach hover state (`#FDE8DF`), charcoal icon stroke.

### Chips & Badges
- **Category Pill**: `12px` vertical padding, `16px` horizontal padding, pill radius (`9999px`). Default state uses soft peach (`#FDE8DF`) with orange text (`#FF7B25`), or light teal with deep teal text (`#05B39C`).

### Interactive Stack Physics
- **Deck Stack**: Multiple offset card planes visible behind the active card (`scale(0.96)`, `translateY(12px)` for card 2; `scale(0.92)`, `translateY(24px)` for card 3) with fading opacities (`0.85` and `0.70`).

### Navigation Bar
- **Bottom Navigation**: Floating pill-dock elevated above the canvas, featuring minimal icon-only buttons with active indicators in primary orange.