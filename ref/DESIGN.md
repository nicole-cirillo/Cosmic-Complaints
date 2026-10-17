---
name: Cosmic Bureaucracy
colors:
  surface: '#2c0026'
  surface-dim: '#2c0026'
  surface-bright: '#5a254f'
  surface-container-lowest: '#23001e'
  surface-container-low: '#370530'
  surface-container: '#3c0a34'
  surface-container-high: '#48163f'
  surface-container-highest: '#55214b'
  on-surface: '#ffd7f0'
  on-surface-variant: '#bcc9cc'
  inverse-surface: '#ffd7f0'
  inverse-on-surface: '#501c46'
  outline: '#879396'
  outline-variant: '#3d494c'
  surface-tint: '#64d5ef'
  primary: '#6cdcf6'
  on-primary: '#003640'
  primary-container: '#4bc0d9'
  on-primary-container: '#004b58'
  inverse-primary: '#006879'
  secondary: '#cabeff'
  on-secondary: '#312270'
  secondary-container: '#4a3d8a'
  on-secondary-container: '#bbaeff'
  tertiary: '#6cdcf3'
  on-tertiary: '#00363f'
  tertiary-container: '#4cc0d6'
  on-tertiary-container: '#004b57'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#a9edff'
  primary-fixed-dim: '#64d5ef'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5b'
  secondary-fixed: '#e6deff'
  secondary-fixed-dim: '#cabeff'
  on-secondary-fixed: '#1c065b'
  on-secondary-fixed-variant: '#483b88'
  tertiary-fixed: '#a4eeff'
  tertiary-fixed-dim: '#65d6ec'
  on-tertiary-fixed: '#001f25'
  on-tertiary-fixed-variant: '#004e5a'
  background: '#2c0026'
  on-background: '#ffd7f0'
  surface-variant: '#55214b'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers a futuristic administrative experience: an intergalactic registry office where complex grievances, celestial protocols, and cosmic claims are logged with absolute precision. The tone is deliberate, institutional, dryly procedural, yet visually transcendent. It blends bureaucratic rigidity with the cold expanse of deep space.

The aesthetic fuses crisp administrative forms, tactile archival structure, and high-contrast digital luminescence. Interfaces rely on translucent tabular grids, hairline periwinkle dividers, precise metadata callouts, and ceremonial administrative seals. The system balances deep plum voids with crystalline cyan accents, conveying bureaucratic authority, permanent record-keeping, and retro-futuristic efficiency.

## Colors

The palette establishes an immersive, high-contrast dark environment rooted in astronomical plum tones and bioluminescent signals.

- **Canvas Background (`#5C2751`)**: The foundational canvas representing deep space administrative halls. Used for overall layout backdrops and base document viewports.
- **Surface & Containers (`#6457A6`)**: The primary vessel color for dossiers, cards, panel modules, input backgrounds, and elevation tiers. Often modulated with variable alpha (`12%` to `40%`) over the deep canvas.
- **Subtle Borders & Administrative Support (`#9DACFF`)**: Applied to structural rules, hairline bounding boxes, timestamps, status legends, and secondary captions. At lower opacities (`15%` to `30%`), it provides non-intrusive container edges; at full intensity, it presents crisp legal copy.
- **Primary Action Accent (`#4BC0D9`)**: High-priority interactive commands, formal filing triggers, focused input borders, and primary status acknowledgments.
- **Hyper-Luminescent Accent (`#76E5FC`)**: Expressly reserved for active incident states, terminal highlights, urgent administrative notices, telemetry blips, and cosmic approval stamps.

## Typography

The typography reinforces the duality of bureaucratic legibility and sci-fi data classification:

- **Executive & Narrative (`Inter`)**: Governs editorial headings, body dispatches, legal clauses, and descriptions. Provides clean geometric neutrality and supreme optical legibility at high densities.
- **Administrative Telemetry (`JetBrains Mono`)**: Powers protocol labels, docket IDs, reference stamps, coordinates, filing numbers, timestamps, and active status tags. All monospace components leverage elevated tracking and uppercase formatting to imitate machine-printed bureaucratic output.

## Layout & Spacing

The layout is structured around an archival grid architecture: strict alignment, dense information displays, and modular docking containers.

- **Grid Architecture**: Standard 12-column layout on desktop viewports (`1200px+`) transitioning to an 8-column layout on tablet (`768px-1199px`) and a 4-column stack on mobile devices (`<768px`).
- **Rhythm & Cadence**: Structural sections prioritize dense horizontal and vertical division over excessive negative space. Form fields, status panels, and claim logs align precisely along shared borders to evoke a standardized intake ledger.
- **Adaptive Reflow**: Multi-column manifest lists collapse into stacked archival cards on smaller viewports, with metadata badges reflowing from inline trailers to pinned header ribbons.

## Elevation & Depth

Visual hierarchy does not use soft natural lighting or organic drop shadows. Depth is achieved purely through translucent surface stacking and luminescent planar outlines:

- **Surface Tiers**:
  - `Base`: `#5C2751` solid field.
  - `Level 1 (Panels & Folders)`: `#6457A6` applied at `20%` opacity with backdrop blur (`12px`), framed by `#9DACFF` at `20%` border opacity.
  - `Level 2 (Active Cards & Insets)`: `#6457A6` applied at `36%` opacity, framed by `#9DACFF` at `35%` border opacity.
  - `Level 3 (Modals & Flyouts)`: `#6457A6` at `80%` opacity over `#5C2751`, edged with `#4BC0D9` at `40%` opacity.
- **Glow & Radiation**: Active nodes and critical highlights emit a focused, atmospheric glow using `#76E5FC` (`box-shadow: 0 0 16px rgba(118, 229, 252, 0.25)`).
- **Outlines**: 1px crisp borders establish containment across all actionable regions; depth is a function of border opacity and edge illumination rather than physical elevation.

## Shapes

The shape system utilizes controlled, subtle roundedness (`0.25rem` standard, `0.5rem` for primary enclosures) to project institutional structure without modern software genericism.

- **Forms & Inputs**: Hardened `0.25rem` radii (`rounded-sm`), evoking physical index cards and computerized intake punchboards.
- **Containers & Dossiers**: Bounded with `0.5rem` radii (`rounded-md`), presenting durable boundaries that keep complex tables and sub-grids strictly organized.
- **Cosmic Administrative Seals & Badges**: Distinct circular geometry (`50%` radius) reserved specifically for cosmic stamps, status indicators, filing badges, and jurisdictional verification emblems.

## Components

### Buttons
- **Primary Intake (`Action`)**: Background in `#4BC0D9`, text in `#5C2751` (`Inter 600`), flat surface with no drop shadows. On hover, background shifts to `#76E5FC` accompanied by a localized cyan aura (`0 0 12px rgba(118, 229, 252, 0.4)`).
- **Secondary Administrative (`Procedural`)**: Semi-transparent `#6457A6` (`30%`) with a 1px `#9DACFF` (`40%`) border. Label rendered in `#9DACFF` with monospace styling (`JetBrains Mono`). Hover elevates border to `100%` `#9DACFF`.
- **Destructive / Expunge**: Transparent background, 1px border tinted in muted red-violet, shifting to intense alert outline upon interaction.

### Form Inputs & Terminal Fields
- **Intake Fields**: Background filled with `#6457A6` (`18%`), bounded by 1px `#9DACFF` (`30%`) border. Text rendered in `#FFFFFF`. Placeholder copy set in `#9DACFF` (`50%`).
- **Focused State**: Border sharpens to `#4BC0D9` with an inset `0 0 0 1px #4BC0D9` and a delicate outer cyan blur. Monospace reference tags flank input tops.

### Dossier Cards & Panels
- **Container Structure**: Deep translucent `#6457A6` bodies bounded by hairline periwinkle borders. Headers feature dedicated docket metadata bars separated by horizontal 1px dividing rules.
- **Filing Header**: Displays docket reference codes (e.g., `SEC-09 // REF-8841-C`) pinned top-left in `label-sm` monospace font.

### Administrative Status Chips & Badges
- **Configuration**: Ultra-compact rounded wrappers (`rounded-sm`) or delicate pill silhouettes containing monospace status indicators (`label-sm`).
- **Logged / Pending**: `#6457A6` background with `#9DACFF` border and text.
- **Active / Processing**: `#76E5FC` text with matching 1px border and low-opacity cyan background fill (`12%`).

### Cosmic Stamps & Seals
- **Filing Certification**: Delicate concentric circular badges featuring an inner hairline ring, radial text markings, an abbreviated sector glyph, and localized date stamps in `#76E5FC` or `#4BC0D9`. Positioned rotated at `(-4deg)` over approved or archived grievances.

### Checkboxes & Segmented Controls
- **Checkboxes**: 16x16px boxes with `0.125rem` corner radius, `#6457A6` base, and 1px `#9DACFF` border. Selected state utilizes solid `#4BC0D9` with deep `#5C2751` vector checkmark.
- **Radio Discs**: Outer `#9DACFF` ring encapsulating an independent inner celestial dot illuminated in `#76E5FC` when engaged.