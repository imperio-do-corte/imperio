---
name: Obsidian & Gold Atelier
colors:
  surface: '#131318'
  surface-dim: '#131318'
  surface-bright: '#39393e'
  surface-container-lowest: '#0e0e13'
  surface-container-low: '#1b1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#2a292f'
  surface-container-highest: '#35343a'
  on-surface: '#e4e1e9'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e4e1e9'
  inverse-on-surface: '#303035'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#e7c35a'
  on-secondary: '#3d2f00'
  secondary-container: '#896c00'
  on-secondary-container: '#fff3dc'
  tertiary: '#f7c852'
  on-tertiary: '#3e2e00'
  tertiary-container: '#d9ad39'
  on-tertiary-container: '#584200'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffe08b'
  secondary-fixed-dim: '#e7c35a'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#ffdf98'
  tertiary-fixed-dim: '#eec14b'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5a4300'
  background: '#131318'
  on-background: '#e4e1e9'
  surface-variant: '#35343a'
  surface-deep: '#0B0B0E'
  surface-raised: '#16161E'
  surface-elevated: '#1E1E29'
  graphite-border: '#2A2A35'
  graphite-subtle: '#3E3E4F'
  gold-ambient-glow: rgba(212, 175, 55, 0.15)
  gold-rim-highlight: rgba(229, 193, 88, 0.45)
  text-pure: '#FFFFFF'
  text-muted: '#9D9DAF'
typography:
  display-hero:
    fontFamily: Montserrat
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: 0.12em
  display-hero-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: 0.08em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: 0.06em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: 0.04em
  headline-md:
    fontFamily: Montserrat
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: 0.04em
  headline-sm:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Montserrat
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.18em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
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
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system embodies an elite, ritualistic grooming culture tailored for the modern gentleman who values discretion, precision, and bespoke luxury. The aesthetic harmonizes architectural dark minimalism with opulent tactile accents—drawing inspiration from haute horlogerie, boutique speakeasies, and bespoke tailoring houses.

### Emotional Landscape & Persona
- **Attitude**: Confident, deliberate, uncompromising, and refined. Never flashy; always substantial.
- **Target Audience**: Discerning professionals, executives, and modern tastemakers seeking an elevated sanctuary rather than a standard transactional service.
- **Visual Stance**: Deep obsidian spatial environments layered with frosted glass, polished brass/gold edge reflections, fine hairlines, and architectural typography.

### Design Direction: Imperial Dark Glassmorphism
The aesthetic relies on multi-tiered, semi-translucent dark surfaces (`#121217` to `#1A1A22`) elevated over deep void black (`#0B0B0E`). Visual hierarchy is anchored by crisp metallic gold accents (`#D4AF37`), brushed brass borders (0.5px–1px), and soft ambient amber glows. Typographic treatment juxtaposes bold, wide-tracked geometric uppercase headlines with ultra-clean, legible humanist sans-serif body copy.

## Colors

The palette is tuned exclusively for a luxury dark-mode experience. Light mode is intentionally omitted to preserve the intimate, high-end atmosphere.

### Chromatic Hierarchy
- **Primary (`#D4AF37`)**: The authentic hallmark gold. Used for focal CTAs, selected booking slots, luxury badges, and active state indicators.
- **Secondary (`#E5C158`)**: Pale champagne gold. Deployed for micro-highlights, hover illumination, and key metric indicators.
- **Tertiary (`#C59B27`)**: Antique deep gold. Provides depth in metallic gradients, pressed-state fills, and secondary interactive borders.
- **Neutral (`#121217`)**: Dense obsidian canvas. Forms the structural base foundation across all layouts.

### Named Specialty Tokens
- **`surface-deep` (`#0B0B0E`)**: Absolute background ground layer.
- **`surface-raised` (`#16161E`)**: Base tile for cards, drawers, and form modules.
- **`surface-elevated` (`#1E1E29`)**: Floating elements, popovers, and sticky navigation bars.
- **`graphite-border` (`#2A2A35`) & `graphite-subtle` (`#3E3E4F`)**: Non-interactive delimiters, keeping layouts structured without chromatic clutter.
- **`gold-ambient-glow` & `gold-rim-highlight`**: Used selectively for radiant borders and button hover envelopes.

## Typography

Typography establishes an intentional contrast between authoritative masculine presence and frictionless readability.

- **Headlines (`Montserrat`)**: Set strictly in uppercase or controlled title case. Wide letter spacing (`0.04em` to `0.18em`) injects breathing space, evoking high-end editorial magazines and Swiss luxury craftsmanship.
- **Body Copy (`Plus Jakarta Sans`)**: Neutralized, open apertures with warm curves counteract the severity of the black and gold palette. Generous line heights ensure effortless scanning during service selection and scheduling flows.
- **Labels & Overlines (`label-caps`)**: Compact uppercase tokens paired with expansive tracking (`0.18em`) denote sub-categories, price indicators, and status chips with precision.

## Layout & Spacing

The layout adopts an architectural 12-column responsive fluid grid on desktop (`max-width: 1360px`), transitioning to a 6-column structure on tablet (`768px - 1024px`) and a single-column stacked hierarchy on mobile viewport displays.

### Layout Principles
- **Generous Canvas Margins**: Layouts utilize broad outer borders (`margin: 3rem`) to evoke an unhurried, boutique atmosphere. Negative space communicates prestige.
- **Rhythm**: All vertical distribution conforms to an 8pt modular interval (`0.5rem` = 8px baseline). Vertical spacing between major sections relies on `space-2xl` (64px) to preserve clarity between services, master barber profiles, and booking modules.

## Elevation & Depth

Spatial depth is established through frosted glassmorphism, multi-layer surface stacking, and selective incandescent gold rim lighting. Flat dropshadows are entirely avoided.

### Elevation Hierarchy
1. **Canvas (Ground)**: `#0B0B0E`. Non-reflective, infinite depth.
2. **Layer 1 (Card & Module Foundation)**: Background `rgba(18, 18, 23, 0.72)` combined with `backdrop-filter: blur(16px)`. Framed with a precise `1px solid rgba(212, 175, 55, 0.12)`.
3. **Layer 2 (Interactive Floating Elements)**: Background `rgba(26, 26, 34, 0.88)` with `backdrop-filter: blur(24px)`. Border is refined to `1px solid rgba(229, 193, 88, 0.3)`. Shadow: `0 16px 36px -8px rgba(0, 0, 0, 0.7)`.
4. **Layer 3 (Modal & Booking Sheet Overlays)**: Surface `#1E1E29` with `box-shadow: 0 24px 64px -12px rgba(0, 0, 0, 0.9), 0 0 1px 1px rgba(212, 175, 55, 0.3)`.

### The "Imperial Glow" Technique
When hovering key elements or highlighting VIP tier services, apply an ambient back-projected blur:
`box-shadow: 0 0 28px -4px rgba(212, 175, 55, 0.25), inset 0 1px 0 0 rgba(255, 255, 255, 0.15)`.

## Shapes

The design system employs controlled, modern rounded geometry (`roundedness: 2`, corresponding to `0.5rem` base, scaling to `1rem` on container cards and `1.5rem` / `rounded-2xl` on primary focal modals and hero features).

- **Standard Cards & Modals**: `1rem` to `1.5rem` (`rounded-2xl`). This softens dark industrial tones and introduces contemporary organic elegance.
- **Buttons & Control Inputs**: `0.75rem` (`rounded-xl`). Maintains structural firmness without sharp corners.
- **Micro Tags & Service Chips**: `0.5rem` or full pills (`rounded-full`) for status indicators.

## Components

### Buttons
- **Primary (The Signature Gold)**: Background is a subtle diagonal metallic sheen: `linear-gradient(135deg, #D4AF37 0%, #E5C158 50%, #C59B27 100%)`. Typography is `label-caps` in deep black (`#0B0B0E`), bold weight. Active state incorporates micro-scale down (`transform: scale(0.98)`). Hover triggers an ambient golden halo: `box-shadow: 0 8px 24px -2px rgba(212, 175, 55, 0.35)`.
- **Secondary (Obsidian Glass)**: Background `rgba(22, 22, 30, 0.65)` with `1px solid rgba(212, 175, 55, 0.4)`. Text in `#FFFFFF`. Hover transitions border to pure `#E5C158` and text to `#D4AF37`.
- **Ghost (Barber Action)**: Background transparent, border transparent, gold underline micro-interaction on hover with `letterSpacing` expanding smoothly by `0.02em`.

### Cards (Glassmorphism Escuro)
Cards feature `rgba(18, 18, 23, 0.65)` background fill with `backdrop-filter: blur(14px)` and fine hairline borders (`#2A2A35`). Featured or VIP cards receive an inner top border highlight (`border-t: 1px solid rgba(229, 193, 88, 0.4)`). Internal padding scales from `space-md` (mobile) to `space-lg` (desktop).

### Form Inputs & Date/Time Selectors
Input fields are styled as recessed dark chambers: background `#0B0B0E` with a hairline outline `#2A2A35`. Placeholder text in `#9D9DAF`. Focused state transitions the border to `#D4AF37` accompanied by an inner glow `box-shadow: 0 0 10px rgba(212, 175, 55, 0.2)`. Time-slot selector chips display in muted graphite, switching to liquid gold with dark text upon selection.

### Service Lists & Barbershop Catalog
List rows feature subtle bottom graphite dividers (`#1A1A22`). Hovering over a service row gently translates the content `4px` to the right, illuminating the price tag from muted white to vibrant `#E5C158`.

### Checkboxes & Radios
Custom circular controls with dark graphite fill. Checked state displays a solid `#D4AF37` core with an outer ring illumination. Micro-animation: gentle radial bloom on toggle.

### Bespoke Component: Barber Mastercard & Appointment Drawer
- **Barber Mastercard**: Portrait card showcasing master cuts with high-contrast monochrome photography that smoothly blooms into rich tones on hover, accented with golden rating stars and a translucent reservation bar.
- **Appointment Drawer**: Slide-over sheet with high frosted blur (`backdrop-filter: blur(28px)`), anchored by step milestones indicated via metallic gold pips and fine hairlines.