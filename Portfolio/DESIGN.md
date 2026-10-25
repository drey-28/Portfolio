---
name: Obsidian Deep Glass
colors:
  surface: '#0e131f'
  surface-dim: '#0e131f'
  surface-bright: '#343946'
  surface-container-lowest: '#080e1a'
  surface-container-low: '#161c28'
  surface-container: '#1a202c'
  surface-container-high: '#242a36'
  surface-container-highest: '#2f3542'
  on-surface: '#dde2f3'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dde2f3'
  inverse-on-surface: '#2b303d'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#bfc6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#b4c5ff'
  on-tertiary: '#002a78'
  tertiary-container: '#618bff'
  on-tertiary-container: '#002469'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#dbe2fd'
  secondary-fixed-dim: '#bfc6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#0e131f'
  on-background: '#dde2f3'
  surface-variant: '#2f3542'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.025em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Geist
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses high-precision technical sophistication through an experimental glassmorphic lens. It targets technical operators, developers, and data engineers requiring deep-focus environments. 

The emotional tone balances computational coldness with luminous intelligence. By blending deep abyssal navy tones, razor-thin translucent surfaces, and electric bioluminescent highlights, the visual identity avoids toy-like frosted glass in favor of an engineered optical instrument. Structural geometry is strict and disciplined, utilizing monospaced metrics and subtle specular rims to evoke an advanced instrumentation HUD.

## Colors

The palette operates on layered optical density against an ultra-deep void (`#030712`). 

- **Primary (`#3b82f6`)**: Bioluminescent sapphire; used for high-signal interactive states, focal focal points, active cursor tracks, and glow nodes.
- **Secondary (`#091124`)**: Deep midnight glass matrix; forms the base for volumetric panels, layered container planes, and structured sidebars.
- **Tertiary (`#2563eb`)**: Cobalt accent; drives nested selections, focus perimeters, and active status telemetry.
- **Neutral (`#030712` to `#1e293b`)**: Structural backdrop tiers calibrated to let translucent frosted planes register with distinct refraction.

Surface borders use a linear gradient ranging from `rgba(59, 130, 246, 0.35)` to `rgba(255, 255, 255, 0.04)` to simulate directional rim lighting on cut glass edges.

## Typography

Typography acts as a precision technical readout. Space Grotesk provides a retro-futuristic, high-geometry edge across display levels and prominent data headers, grounding the fluid luminescence of the background. Geist delivers clinical clarity and optical legibility in high-density data tables, properties inspectors, and long-form readouts.

Display titles must always feature tight tracking to reinforce mechanical rigidity. Labels use slight positive letter-spacing and uppercase rendering for status indicators and micro-telemetry data tags.

## Layout & Spacing

The structural layout relies on a strict 12-column fluid grid governed by modular, nested glass shells. 

- **Desktop (>= 1280px)**: 12-column grid with `2rem` margins and `1.5rem` gutters. Floating glass panels maintain deliberate negative space to let underlying bioluminescent light-bleeds register.
- **Tablet (768px - 1279px)**: 8-column layout with `1.5rem` margins and `1rem` gutters. Non-essential panels collapse into sliding frosted drawers.
- **Mobile (< 768px)**: 4-column layout with `1rem` edge margins. Glass effects simplify blur radii to ensure performance stability, flattening secondary layered panels into unified cards.

## Elevation & Depth

Visual hierarchy uses progressive optical density, backdrop filters, and bioluminescent diffusion rather than heavy opaque drop shadows.

- **Canvas Base**: `#030712` overlaid with subtle, radial gradient flares (`rgba(37, 99, 235, 0.12)` blur 120px) positioned behind primary interaction zones.
- **Level 1 (Panels & Surfaces)**: Background `rgba(9, 17, 36, 0.55)`, backdrop filter blur `16px`, bordered by `1px solid rgba(59, 130, 246, 0.15)`. No drop shadow.
- **Level 2 (Active Cards & Floating Containers)**: Background `rgba(15, 23, 42, 0.65)`, backdrop filter blur `24px`, bordered by `1px solid rgba(59, 130, 246, 0.3)`. Shadow: `0 8px 32px -4px rgba(0, 0, 0, 0.6)`.
- **Level 3 (Modals, Popovers & Flyouts)**: Background `rgba(9, 17, 36, 0.85)`, backdrop filter blur `32px`, bordered by `1px solid rgba(59, 130, 246, 0.5)`. Shadow: `0 16px 48px -8px rgba(3, 7, 18, 0.9), 0 0 24px 0 rgba(59, 130, 246, 0.2)`.

Specular highlights are produced via an inner top glow: `box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.12)`.

## Shapes

The design system enforces a soft, clinical roundedness tier (`1`). Base elements utilize `0.25rem` (4px) corner radii, large cards use `0.5rem` (8px), and hero containers scale to `0.75rem` (12px). 

Sharp geometric discipline is maintained across the UI: no pill shapes or oversized circular shells are permitted. Radii should feel milled and laser-cut rather than organic. Thin `1px` structural vector borders define every component edge to retain glass clarity against dark backdrops.

## Components

### Buttons
- **Primary**: Solid sapphire fill (`#3b82f6`) with dark text (`#030712`), font weight 500, inner top highlight `inset 0 1px 0 rgba(255,255,255,0.3)`. Subtle radial bloom on hover (`0 0 16px rgba(59, 130, 246, 0.4)`).
- **Secondary (Glass)**: Background `rgba(59, 130, 246, 0.08)`, border `1px solid rgba(59, 130, 246, 0.25)`, text `#93c5fd`. Hover shifts background to `rgba(59, 130, 246, 0.16)` with border brightness increase.
- **Ghost**: Zero background, crisp text `#94a3b8`, hover text `#ffffff` with `rgba(255,255,255,0.05)` background fill.

### Cards & Panels
Constructed as frosted telemetry slabs. Standard padding uses `space-lg` (1.5rem). The top edge features a directional gradient border fading from `#3b82f6` to `transparent`. Internal dividers are strict 1px rules using `rgba(59, 130, 246, 0.1)`.

### Input Fields
Backdrop `rgba(3, 7, 18, 0.6)` with backdrop blur `8px`. Border `1px solid rgba(59, 130, 246, 0.2)`. Text `#f8fafc`. Active focus state triggers an immediate crisp boundary shift to `1px solid #3b82f6` paired with an external sapphire halo (`box-shadow: 0 0 0 2px rgba(59, 130, 246, 0.25)`).

### Chips & Badges
Low-profile height (22px). Background `rgba(37, 99, 235, 0.12)`, text `#60a5fa`, border `1px solid rgba(59, 130, 246, 0.25)`. Monospaced numerical values use `Geist` with uppercase tracking. Status variants utilize micro-glowing dots (4px diameter) with soft CSS pulse animations.

### Checkboxes & Radio Buttons
Base geometry uses 4px radii for checkboxes and circular geometry for radios. Box surface `rgba(9, 17, 36, 0.7)` with `1px solid rgba(59, 130, 246, 0.3)`. Checked state transitions instantly to `#3b82f6` with a high-contrast dark mark (`#030712`) and a localized `0 0 8px rgba(59, 130, 246, 0.5)` glow.

### Lists & Data Rows
Alternating zebra patterns are prohibited. Rows separate via `1px solid rgba(255, 255, 255, 0.04)`. Hovering a row triggers a subtle translucent luminous sweep (`background: rgba(59, 130, 246, 0.05)`).