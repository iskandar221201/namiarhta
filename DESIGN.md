---
name: Architectural Precision
colors:
  surface: '#faf9fa'
  surface-dim: '#dbdadb'
  surface-bright: '#faf9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f4'
  surface-container: '#efedef'
  surface-container-high: '#e9e8e9'
  surface-container-highest: '#e3e2e3'
  on-surface: '#1b1c1d'
  on-surface-variant: '#43474c'
  inverse-surface: '#303032'
  inverse-on-surface: '#f2f0f1'
  outline: '#73787c'
  outline-variant: '#c3c7cc'
  surface-tint: '#4a6172'
  primary: '#000b14'
  on-primary: '#ffffff'
  primary-container: '#092332'
  on-primary-container: '#738b9d'
  inverse-primary: '#b1cadd'
  secondary: '#006a69'
  on-secondary: '#ffffff'
  secondary-container: '#80f5f3'
  on-secondary-container: '#007070'
  tertiary: '#060c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#182500'
  on-tertiary-container: '#79904c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cde6fa'
  primary-fixed-dim: '#b1cadd'
  on-primary-fixed: '#031e2d'
  on-primary-fixed-variant: '#32495a'
  secondary-fixed: '#80f5f3'
  secondary-fixed-dim: '#61d8d7'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#00504f'
  tertiary-fixed: '#d2ec9e'
  tertiary-fixed-dim: '#b6d085'
  on-tertiary-fixed: '#131f00'
  on-tertiary-fixed-variant: '#394d10'
  background: '#faf9fa'
  on-background: '#1b1c1d'
  surface-variant: '#e3e2e3'
  surface-muted: '#F4F7F8'
  text-body: '#334155'
  text-muted: '#64748B'
  border-subtle: '#E2E8F0'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  stats-number:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is rooted in the "Architectural Precision" style—a blend of **Corporate Modern** and **Minimalist** aesthetics. It is designed to evoke trust, technical competence, and meticulous transparency. The target audience includes high-end residential clients and commercial developers who value integrated, "no-drama" project management.

Visuals are governed by a strict structural grid, clean lines, and an information-first hierarchy. The style avoids unnecessary decorative elements, instead using architectural photography, precise stats, and generous whitespace to communicate premium quality and reliability.

## Colors
The palette uses a sophisticated, high-contrast mix to balance corporate stability with modern energy.
- **Primary (#092332):** A deep, architectural navy used for typography, headers, and primary UI anchors to establish authority.
- **Secondary (#2BAEAD):** A professional teal used for interactive elements, icon backgrounds, and structural accents.
- **Tertiary (#E3FEAE):** A high-visibility lime used sparingly for highlights, statistics, and critical call-to-action (CTA) accents to guide the eye.
- **Neutral:** A range of cool grays and off-whites are used to maintain a clean, airy feel and provide depth without visual clutter.

## Typography
Inter is used exclusively to maintain a systematic, utilitarian, and highly readable appearance. 
- **Hierarchy:** Strong contrast in font weight (Extra Bold for headers vs. Regular for body) creates clear navigation paths.
- **Readability:** Body text uses a slightly increased line height (1.6) for better legibility in technical descriptions.
- **Special Roles:** A dedicated `stats-number` style is used for the impact section to emphasize experience and success metrics. Labels use uppercase and slight tracking for a professional, "blueprint-like" aesthetic.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop (1280px max-width) with a 12-column structure. 
- **Sectioning:** Generous vertical padding (120px) separates major narrative blocks (About, Services, Portfolio) to allow the content to "breathe" and maintain a premium feel.
- **Rhythm:** An 8px base unit governs all internal spacing.
- **Mobile Adaptivity:** On mobile, margins reduce to 16px and sections collapse to a single column. The hero text scales down using the `display-lg-mobile` token to ensure immediate impact without horizontal scrolling.

## Elevation & Depth
This design system uses **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows to convey depth, reinforcing the architectural "flat plan" concept.
- **Surfaces:** Use subtle shifts in background color (e.g., from White to Surface-Muted) to distinguish between content sections.
- **Cards:** Project and service cards utilize a 1px solid border (`border-subtle`) instead of shadows.
- **Interactions:** A very soft, ambient shadow (10% opacity, Primary color tint) is only applied on hover to suggest "lifting" the element for interaction.

## Shapes
The shape language is **Soft (0.25rem)**. This slight rounding takes the edge off the "industrial" feel of the construction industry, making the brand feel more approachable and modern while maintaining the precision of straight architectural lines.
- **Buttons and Inputs:** Use a standard 4px radius.
- **Featured Images:** Use a slightly larger 8px radius (`rounded-lg`) to soften the visual impact of photography.

## Components
- **Buttons:** Primary buttons use the Primary color (#092332) with white text. Secondary buttons use an outline style with the Secondary color (#2BAEAD). Hover states should involve a background color fill or a slight shift in saturation.
- **Service Cards:** Features a top-aligned icon (Secondary color), a `title-lg` header, and `body-md` text. The entire card area is interactive.
- **Stats Bar:** A horizontal strip often placed below the Hero. It uses `stats-number` with the Tertiary color (#E3FEAE) to highlight key achievements against a Primary background.
- **Input Fields:** Clean, 1px bordered boxes with `label-md` floating labels. Use the Secondary color for the focus state border.
- **Chips/Badges:** Small, `label-md` text containers with the Surface-Muted background used for project categories (e.g., "Residential", "Commercial").
- **Portfolio Gallery:** A masonry or clean grid layout where images feature a subtle overlay on hover, revealing the project name and location.