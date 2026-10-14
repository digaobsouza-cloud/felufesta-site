---
name: Festive Craft & Print
colors:
  surface: '#fbf8ff'
  surface-dim: '#dbd9e1'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2fb'
  surface-container: '#efecf5'
  surface-container-high: '#eae7ef'
  surface-container-highest: '#e4e1ea'
  on-surface: '#1b1b21'
  on-surface-variant: '#5a3f48'
  inverse-surface: '#303036'
  inverse-on-surface: '#f2eff8'
  outline: '#8e6f78'
  outline-variant: '#e2bdc7'
  surface-tint: '#b90066'
  primary: '#b70065'
  on-primary: '#ffffff'
  primary-container: '#e4007f'
  on-primary-container: '#fffeff'
  inverse-primary: '#ffb0c9'
  secondary: '#006491'
  on-secondary: '#ffffff'
  secondary-container: '#3db8fd'
  on-secondary-container: '#004667'
  tertiary: '#725c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca800'
  on-tertiary-container: '#4d3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e3'
  primary-fixed-dim: '#ffb0c9'
  on-primary-fixed: '#3e001e'
  on-primary-fixed-variant: '#8d004d'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#8aceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004b6f'
  tertiary-fixed: '#ffe07c'
  tertiary-fixed-dim: '#ecc200'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#564500'
  background: '#fbf8ff'
  on-background: '#1b1b21'
  surface-variant: '#e4e1ea'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system blends celebratory energy with commercial clarity. Created for quick-print services, custom stationery, and festive party supplies, the brand personality is joyful, dependable, inventive, and energetic. The experience translates the tactile magic of fresh ink and paper into a crisp digital interface.

The visual direction follows **Modern Tactile Minimalism** infused with high-chroma CMYK-inspired accents. Interfaces maintain a clean, white-space-forward canvas to keep personalized product previews, stationery options, and party templates legible. Playful geometric roundings, soft layered shadows, and saturated color pops elevate everyday utilitarian tasks into a delight-driven celebration.

## Colors

The palette takes direct cues from traditional CMYK process inks (Cyan, Magenta, Yellow, Key/Black) while tuning them for modern digital accessibility and festive exuberance.

- **Primary (`#E4007F` - Process Magenta / Vibrant Pink):** Anchors high-priority actions, conversion flows, featured categories, and joyous interactive states.
- **Secondary (`#009FE3` - Process Cyan / Bright Sky):** Guides discovery tags, structural tabs, secondary utilities, and informational balance.
- **Tertiary (`#FFD200` - Warm Gold / Canary Accent):** Reserves energy for badges, celebratory highlights, party ribbons, and promotional banners. Must always be paired with dark neutral text to ensure high contrast.
- **Neutral (`#1E1E24` - Deep Graphite / Rich Black):** Grounds all typography and container boundaries, avoiding harsh `#000000` while preserving print-grade definition.
- **Surface Backgrounds:** Primarily crisp whites (`#FFFFFF`) and warm snow tones (`#F9F9FB`), preventing visual fatigue and allowing vibrant product photographs to take center stage.

## Typography

**Plus Jakarta Sans** provides a geometric, approachable backbone across every touchpoint. Its soft circular curves mirror the welcoming ambiance of festivities while maintaining precision across data-dense order trackers and product catalogs.

- **Headlines & Display:** Set in Bold (`700`) and ExtraBold (`800`) weights with tight letter tracking to convey confidence, festivity, and clear storefront signposting.
- **Body:** Uses Regular (`400`) and Medium (`500`) weights with generous line heights to facilitate effortless reading of stationery dimensions, paper weights, and customization options.
- **Labels & Microcopy:** Rendered in SemiBold (`600`) with modest letter spacing for crisp legibility on pills, tags, price callouts, and configuration chips.

## Layout & Spacing

A flexible 12-column layout rhythm governs desktops, scaling down gracefully to 8 columns on tablets and 4 columns on mobile viewports.

- **Outer Margins:** Scale from compact 16px (`1rem`) on hand-held devices to 48px (`3rem`) on wide screens to maintain structural balance.
- **Grid Gutters:** Retain a consistent 16px to 24px rhythm to ensure dense customization cards, print preview grids, and catalog tiles never crowd one another.
- **Component Padding & Flow:** Apply the `space-*` scale predictably—internal card padding leverages `space-lg`, while inline label-to-icon pairings utilize `space-xs` and `space-sm`.

## Elevation & Depth

Visual hierarchy uses clean multi-level surfaces elevated by soft, tinted shadows rather than heavy border outlines:

- **Surface 0 (Canvas Base):** Pure white `#FFFFFF` or subtle `#FAFAFC` backdrop.
- **Surface 1 (Standard Cards & Tiles):** Elevated with a subtle diffused shadow: `0 4px 16px -2px rgba(30, 30, 36, 0.06), 0 2px 6px -1px rgba(30, 30, 36, 0.03)`.
- **Surface 2 (Interactive Floating Cards / Hover States):** Lifts with a primary-tinted glow: `0 12px 28px -4px rgba(228, 0, 127, 0.12), 0 4px 10px -2px rgba(30, 30, 36, 0.04)`.
- **Surface 3 (Modals, Drawers, Quick-Quote Overlays):** Grounded by a higher blur shadow with low opacity backdrop backdrop-filters: `0 20px 40px -8px rgba(30, 30, 36, 0.16)`.

## Shapes

The system embraces friendly, organic curves that feel approachable and celebratory:

- **Base Radius (`0.5rem` / 8px):** Applied to form fields, inputs, dropdowns, and micro-controls.
- **Medium/Large Radius (`1rem` / 16px):** Standard for product cards, modal containers, and celebratory banners.
- **Pill / Circular Radius (`9999px`):** Reserved for floating action buttons, status pills, category chips, and cart quantity selectors.

## Components

### Buttons
- **Primary Button:** Solid Magenta (`#E4007F`) background with pure white text, bold weight, and a smooth hover transition that deepens tone to `#C7006F` alongside an ambient shadow.
- **Secondary Button:** Solid Cyan (`#009FE3`) or vibrant Cyan outline (`2px solid #009FE3`) with high-contrast text. Ideal for secondary actions like "Download Template" or "Personalize Artwork."
- **Tertiary / Promo Button:** Gold (`#FFD200`) background with Graphite (`#1E1E24`) text, utilized for special offers and event packages.

### Chips & Badges
- **Category Filter Chips:** Rounded pill shapes with soft neutral backgrounds (`#F3F3F6`) shifting to active Cyan or Magenta fills with crisp white text when selected.
- **Status Tags:** Compact pills with pastel backgrounds and saturated text (e.g., Yellow `#FFF8D6` with `#8C6B00` text for "Em Produção", Cyan `#E5F6FD` with `#007AB0` for "Pronto").

### Cards & Catalogs
- **Product & Kit Cards:** Clean white containers featuring a 16px corner radius, full-bleed imagery showing real stationery or party arrangements, and a bottom content area showcasing dynamic price tags, custom options, and quick-add actions.

### Form Inputs & Checkers
- **Text Inputs:** Soft border (`1.5px solid #E2E2E8`), 8px border radius, focusing into a vibrant Cyan glow (`#009FE3`) with 0 0 0 3px ring opacity.
- **Checkboxes & Radios:** Smoothly rounded squares and circles that fill with solid Magenta (`#E4007F`) upon selection, containing a clean white checkmark.

### Customizers & File Uploaders
- **Upload Zone (Gráfica Rápida):** Dashed border with a soft tint (`2px dashed #009FE3`), spacious icon illustration, and clear guides for acceptable formats (PDF, AI, PNG, Corel).