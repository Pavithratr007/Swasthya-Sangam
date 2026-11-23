---
name: Serene Community Wellness
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
  on-surface-variant: '#414844'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#717974'
  outline-variant: '#c1c8c3'
  surface-tint: '#426657'
  primary: '#3f6355'
  on-primary: '#ffffff'
  primary-container: '#587c6d'
  on-primary-container: '#f5fff8'
  inverse-primary: '#a8cfbd'
  secondary: '#8e4e14'
  on-secondary: '#ffffff'
  secondary-container: '#ffab69'
  on-secondary-container: '#783d01'
  tertiary: '#89475f'
  on-tertiary: '#ffffff'
  tertiary-container: '#a55f78'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c4ebd9'
  primary-fixed-dim: '#a8cfbd'
  on-primary-fixed: '#002116'
  on-primary-fixed-variant: '#2a4d40'
  secondary-fixed: '#ffdcc4'
  secondary-fixed-dim: '#ffb780'
  on-secondary-fixed: '#2f1400'
  on-secondary-fixed-variant: '#6f3800'
  tertiary-fixed: '#ffd9e3'
  tertiary-fixed-dim: '#ffb0c9'
  on-tertiary-fixed: '#3a061e'
  on-tertiary-fixed-variant: '#70334a'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
typography:
  display-lg:
    fontFamily: Nunito Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  display-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.005em
  headline-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0em
  headline-md:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 34px
  headline-sm:
    fontFamily: Nunito Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-sm:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Nunito Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Nunito Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Nunito Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system centers on gentle, dignified communal care. Designed for self-help collectives, community health practitioners, and bilingual wellness networks, the visual aesthetic prioritizes psychological calm, mutual trust, and high legibility across diverse literacy and language backgrounds.

The visual style blends modern organic minimalism with soft, tactile warmth. Visual surfaces draw inspiration from botanical vitality and earthy calm—specifically sunlit sage leaves, unbleached cotton, and warm clay. Rather than clinical detachment or stark medical sterility, the aesthetic feels inviting, serene, and deeply grounded in daily communal rituals. Interfaces must remain uncluttered, supportive, and accessible across bilingual English and Indic script contexts (such as Kannada), ensuring typographic clarity and generous breathing room for expanded script heights.

## Colors

The palette establishes a reassuring, organic equilibrium suitable for reflective self-care and structured community health records.

- **Primary (`#6B9080` - Sage Green):** Symbolizes vitality, restorative balance, and grounded wellness. Used for primary actions, active navigational indicators, vital metric highlights, and key navigational headers.
- **Secondary (`#F4A261` - Soft Sunlit Terracotta):** Represents fellowship, morning energy, and warmth. Applied to milestones, attention indicators, secondary calls-to-action, and community session badges.
- **Tertiary (`#D98BA5` - Lotus Blossom Pink):** An empathetic accent invoking gentle mindfulness and wellness tracking. Used sparingly for personal health reflections, special progress markers, and focus states.
- **Neutral Surface (`#FAF6F0` - Warm Raw Cream):** The foundation canvas, providing an organic, low-glare reading environment that mitigates eye fatigue across sustained record-keeping sessions.
- **Text & Foreground:** Deep botanical charcoal (`#303A36`) delivers WCAG AAA compliant contrast against cream and white grounds, eliminating the harshness of pure black while retaining crisp legibility for complex bilingual scripts.
- **Card & Elevated Grounds:** Pure white (`#FFFFFF`) isolates active interactive content, creating crisp separation over the cream canvas.

## Typography

The type system is engineered around `Nunito Sans` for unified structural balance, gentle geometric curves, and open apertures. Its rounded terminals echo organic forms without sacrificing institutional precision.

Line-height ratios are expanded to 1.5–1.6x across body scales to naturally accommodate bilingual text, specifically rendering complex Indic vowel modifiers and stacked glyphs (such as Kannada conjuncts) without vertical truncation or cramped baselines. Headings utilize weights `600` and `700` to anchor information hierarchy with welcoming authority.

## Layout & Spacing

The layout model adopts a fluid-responsive grid system designed for effortless handheld recording in community circles and comprehensive desktop administration:

- **Desktop (1024px+):** 12-column layout with `2rem` margins and `1.25rem` gutters. Maximum content canvas bounded at 1280px to preserve comfortable scan lengths for health profiles.
- **Tablet (640px – 1023px):** 8-column layout with `1.5rem` margins and `1rem` gutters.
- **Mobile (< 640px):** 4-column layout with `1rem` outer canvas margins and `0.75rem` gutters, prioritizing immediate thumb-reachability and vertical continuity.

Vertical rhythm relies on a standard 4px/8px modular cadence. Generous padding (`space-lg` and `space-xl`) isolates multi-lingual form modules and attendance registers, reducing visual clutter and preventing cognitive overload during field data entry.

## Elevation & Depth

Visual depth is achieved through gentle tonal stratification and soft, warm-tinted ambient diffusion rather than harsh drop shadows.

- **Base Canvas:** Flat `#FAF6F0` (Warm Cream).
- **Surface Tier (Cards & Registers):** Pure `#FFFFFF` surfaces paired with an ultra-soft botanical ambient shadow: `0 4px 20px -2px rgba(48, 58, 54, 0.05)`.
- **Raised Interactive (Modals, Overlays, Active Pickers):** Lifted with dual-layer diffusion: `0 10px 30px -4px rgba(107, 144, 128, 0.12), 0 4px 8px -2px rgba(48, 58, 54, 0.04)`.
- **Ghost Borders:** Interactive elements and resting surfaces utilize delicate, low-contrast boundary lines (`1px solid rgba(107, 144, 128, 0.15)`) to maintain distinct structure on bright screens in outdoor daylight conditions.

## Shapes

With `roundedness: 2`, structural containers follow a soft, friendly, organic radius scale:
- **Base Components (Inputs, Buttons, Badges):** `0.5rem` (8px) radius, conveying accessible tactile softness.
- **Content Cards & Panels:** `1rem` (16px) radius (`rounded-lg`), evoking smooth river stones and leaf contours.
- **Promotional Modals & Feature Cards:** `1.5rem` (24px) radius (`rounded-xl`).
- **Pills & Status Tags:** Fully rounded pill radius (`9999px`) to frame individual members, statuses, and yoga practice categories.

## Components

### Buttons
- **Primary:** Filled `#6B9080` with pure white text, `0.5rem` border radius, `0.75rem 1.5rem` padding. Subtle transform translateY(-1px) with softened sage shadow on hover.
- **Secondary:** Filled `#FAF6F0` with `1.5px solid #6B9080`, text color `#303A36`.
- **Tertiary/Ghost:** Transparent ground, `#6B9080` text, highlighting on hover with `rgba(107, 144, 128, 0.08)`.

### Cards & Record Tiles
Constructed with `#FFFFFF` background, `1rem` rounded corners, `1.25rem` internal padding, and a hairline border of `rgba(107, 144, 128, 0.15)`. Member record cards incorporate a subtle `4px` vertical accent stripe on the left edge denoting attendance status (Sage: Present, Terracotta: Leave, Muted Gray: Unrecorded).

### Form Fields & Inputs
- **Inputs:** `#FFFFFF` background, `0.5rem` border-radius, minimum height of `48px` to ensure comfortable touch targets in field situations.
- **Bilingual Labels:** Primary label in English (`Nunito Sans`, 14px, weight 600, `#303A36`) with complementary Kannada subtitle directly adjacent or grouped (`Nunito Sans`, 13px, weight 400, `rgba(48, 58, 54, 0.75)`).
- **Focus State:** 2px ring in `#6B9080` with a 2px offset in `#FAF6F0`.

### Chips & Filters
Pill-shaped (`rounded-full`), padded `0.375rem 0.875rem`, employing `Nunito Sans` label-md. Selected state uses tinted sage (`#6B9080` background, white text); unselected state utilizes `#FFFFFF` with `1px solid rgba(107, 144, 128, 0.25)` and `#303A36` text.

### Checkboxes & Radio Controls
Slightly oversized (`20px x 20px`) for accessibility. Radios are circular; checkboxes feature `0.25rem` rounded corners. Active state filled with `#6B9080` exhibiting a clean white checkmark.

### Wellness Metric Trackers (Custom Component)
Segmented progress tracks with rounded endcaps displaying group attendance milestones and yoga practice frequencies. Filled with `#6B9080` or `#F4A261` over a neutral `#E9E2D8` track ground.