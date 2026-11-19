---
name: Artisanal Editorial
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4d444b'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#F3EDE3'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
  text-primary: '#221E1F'
  surface-card: '#FFFFFF'
  border-subtle: '#E5DCCE'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 3.5rem
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: '1.35'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.08em
  price-callout:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The design system establishes a tactile, grounded, and artisanal aesthetic tailored for a neighbourhood café and micro-roastery. The brand identity balances thoughtful hospitality with unpretentious authority: warm, plainspoken, and quietly confident with dry-humoured restraint. It speaks equally to a passerby making a quick decision on a phone screen and an office manager organising catering from a desktop browser.

The design movement combines **Minimalist Editorial** with **Tactile Warmth**. Visual priority is given to deliberate typography, generous organic breathing room, and structured information delivery rather than ornamental digital trickery. Surfaces evoke high-grade unbleached paper, freshly ground roasts, and quiet morning light. Interactions feel physical, deliberate, and direct—eschewing SaaS-like gradients or complex micro-interactions in favour of honest, immediate utility.

## Colors

The palette is rooted in physical materiality:
- **Primary (`#4A2C4D` — Deep Fig Purple):** Anchors brand authority, headline typography, primary interaction targets, and heavy framing elements.
- **Secondary (`#D9A441` — Warm Amber):** Reserved strictly for accents, badges, small price highlights, and focus rings. It is never used for running body copy or low-contrast text.
- **Neutral Canvas (`#FAF6F0` — Warm Off-White):** Provides an organic, unbleached paper ground that softens contrast and avoids the sterile glare of pure white.
- **Text Primary (`#221E1F` — Near-Black):** Ensures maximum legibility for long-form reading and menu prices without the harsh edge of `#000000`.

Use `surface-card` (`#FFFFFF`) sparingly for elevated containers, always separated from `#FAF6F0` via subtle hairline strokes (`border-subtle`, `#E5DCCE`) rather than synthetic dropshadows.

## Typography

The pairing creates an immediate dialogue between artisanal legacy and clean contemporary utility:
- **Headings (Playfair Display):** Rich, high-contrast transitional serif delivering warmth, history, and craft without feeling antique. It is used for page titles, menu section breaks, and founder quotes.
- **Body & Labels (Plus Jakarta Sans):** Modern geometric-humanist sans-serif that retains clean legibility at small sizes while offering open apertures and friendly curves that harmonize with the serif's warmth.

Letter spacing is slightly loosened for uppercase markers and labels (`label-sm`), while headline scales tighter as the point size increases. Menu item names pair with tabular figures or distinct serif styling for clear scanning.

## Layout & Spacing

The layout is strictly mobile-first with a single-column default. The composition prioritizes rapid information triage: crucial decisions (visiting hours, address, core offering) are positioned above any fold or immediately within first glance.

- **Breakpoints:**
  - Mobile: `< 640px` (Single column, max-width 100%, narrow reading gutters).
  - Tablet: `640px – 1023px` (Constrained single column or 2-column split for catering/menu listings).
  - Desktop: `≥ 1024px` (Max layout width capped at `1040px` to maintain an intimate, editorial feel).

- **Structure Rules:**
  - Menus are presented in a focused single column on mobile, transitioning to a maximum of two structured columns on desktop.
  - Catering cards stack vertically on small devices and align across a 3-column row on viewports `>= 768px`.
  - Margins maintain an unhurried, comfortable white border around all viewport edges, reinforcing the feeling of a printed leaflet or menu placard.

## Elevation & Depth

This design system avoids artificial drop shadows, floating blurred cards, or heavy Z-axis lighting. Depth is articulated through **Tonal Stacking** and **Hairline Outlines**:

- **Ground Level:** Base page background in `#FAF6F0`.
- **Raised Containers:** Secondary content cards and callout panels use `#FFFFFF` or `#F3EDE3`, bound by a delicate 1px border (`#E5DCCE`).
- **Hero & Image Depth:** Images are treated as natural paper cut-ins or full-bleed textural anchors. They carry crisp edges without soft vignetting.
- **Action Emphasis:** State transitions rely on background shifts (e.g., from `#4A2C4D` to deep plum `#361F38` on hover/press) and crisp 2px solid focus rings tinted in Warm Amber (`#D9A441`), avoiding fuzzy glow effects.

## Shapes

The design system embraces a **Soft (Level 1)** corner geometry:
- Standard elements (buttons, inputs, surface cards): `0.25rem` (4px).
- Larger containers and image frames: `0.5rem` (8px).
- Dietary pills and metadata tags: fully rounded caps (`9999px`) to immediately distinguish contextual metadata from interactive button shapes.

The subtle rounding keeps the layout structured, crisp, and editorial, evoking book covers, cafe order cards, and printed stationery rather than bubbly app interfaces.

## Components

### Buttons & Interactive CTAs
- **Primary Button:** Exactly one primary call-to-action per page. Filled with `#4A2C4D`, crisp white text, bold label weighting, padded `0.875rem 1.75rem`, `0.25rem` radius. On hover/active, darkens subtly with no upward shadow float.
- **Plain Link:** All other links throughout pages are understated text links styled in `#4A2C4D` with a subtle 1px baseline underline offset by 2px, shifting to `#D9A441` on hover.

### Menu List Items
- Formatted as horizontal rows with item title and diet tags on the left, an optional dotted or blank leader, and right-aligned price in `price-callout` styling.
- Compact line heights allow scanning 15+ items without excessive vertical scrolling.

### Dietary Chips & Badges
- Compact capsules (`padding: 0.125rem 0.5rem`, `border-radius: 9999px`).
- Inverted or border-based: border `1px solid #D9A441`, warm amber text `#221E1F`, `0.75rem` font size, bold tracking. Never distracting, always scannable.

### Catering & Package Cards
- Clean white surface (`#FFFFFF`), `1px solid #E5DCCE` perimeter border.
- Includes a dedicated header with package title in Playfair Display, prominent price per person (`$X per person`), bulleted inclusions, and minimum headcount guidelines.
- Mobile stacks cleanly with `space-md` gaps.

### Opening Hours & Visit Panels
- Styled as a legible, high-contrast two-column table. Left column: Days of the week in neutral muted tones; Right column: Operating hours right-aligned in `#221E1F`.
- "Today" or current operating status highlighted with an amber indicator dot.

### Global Footer
- Full-bleed section tinted in `#F3EDE3` with top border `1px solid #E5DCCE`.
- Clear, unstyled hierarchy: Brand name, 8 Chalk Lane address, hours summary, direct mailto link, and the dedicated "Order catering" action.