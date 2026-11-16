---
version: alpha
name: Ramp System - Amrut Insurance & Investment
description: An adaptation of Ramp's warm editorial financial system for Amrut Insurance & Investment. Built on a restrained warm-neutral palette (deep ink #000000, muted ink #1A1919, warm stone canvas #F4F2F0, and elevated paper #FFFFFF), Swiss-influenced typographic discipline with high scale contrast and tight negative tracking, section-by-section dark and light alternation, 12px card radii, and realistic policy preview cards that ground insurance advisory in tangible certainty.

colors:
  primary: "#000000"
  on-primary: "#ffffff"
  ink: "#000000"
  muted-ink: "#1A1919"
  surface: "#212121"
  surface-hover: "#2a2929"
  canvas: "#F4F2F0"
  paper: "#FFFFFF"
  border-subtle: "#E5E2DE"
  border-dark: "#2A2826"
  text-primary: "#000000"
  text-secondary: "#5A5753"
  text-muted: "#8A8680"
  text-on-dark: "#FFFFFF"
  text-on-dark-muted: "#A8A49E"
  badge-emerald-bg: "#EFFCF8"
  badge-emerald-text: "#006642"
  badge-emerald-border: "#C7F2E5"
  badge-dark-bg: "#1A1919"
  badge-dark-text: "#F4F2F0"
  wa-green: "#25D366"
  wa-green-hover: "#20bd5a"

typography:
  hero-display:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 48px
    fontWeight: 400
    lineHeight: 50px
    letterSpacing: -0.48px
  section-display:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 40px
    fontWeight: 400
    lineHeight: 42px
    letterSpacing: -0.2px
  medium-display:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 28px
    fontWeight: 400
    lineHeight: 32px
    letterSpacing: 0
  body-large:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 20px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0
  body:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0
  body-small:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0
  label:
    fontFamily: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif
    fontSize: 11px
    fontWeight: 500
    lineHeight: 16px
    letterSpacing: 1.2px
    textTransform: uppercase
  mono-num:
    fontFamily: "JetBrains Mono", ui-monospace, SFMono-Regular, Menlo, monospace
    fontSize: 14px
    fontWeight: 500
    lineHeight: 20px
    letterSpacing: 0

rounded:
  none: 0px
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  4xl: 96px
  section: 112px

components:
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-small}"
    padding: "{spacing.sm} {spacing.lg}"
    borderColor: "{colors.border-subtle}"
  primary-button:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.body-small}"
    rounded: "{rounded.lg}"
    padding: "12px 20px"
  secondary-button:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    borderColor: "{colors.muted-ink}"
    typography: "{typography.body-small}"
    rounded: "{rounded.lg}"
    padding: "12px 20px"
  whatsapp-button:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    typography: "{typography.body-small}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  policy-card:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
    borderColor: "{colors.border-subtle}"
  stat-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  testimonial-card:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  dark-section-card:
    backgroundColor: "{colors.muted-ink}"
    textColor: "{colors.text-on-dark}"
    rounded: "{rounded.lg}"
    padding: "{spacing.xl}"
  badge-savings:
    backgroundColor: "{colors.badge-emerald-bg}"
    textColor: "{colors.badge-emerald-text}"
    borderColor: "{colors.badge-emerald-border}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "4px 10px"
---

# Amrut Insurance & Investment Design System (Ramp-Inspired)

## Overview

Amrut Insurance & Investment's visual system adapts Ramp's celebrated financial design architecture: an editorial, highly disciplined aesthetic built on warm neutral tones, tight typographic hierarchy, and generous spatial rhythm.

Traditional insurance portals in India suffer from aggressive clutter: flashing banners, high-pressure countdowns, and cold comparison grids. This design language replaces that noise with **understated institutional authority**:
- **Warm Stone Canvas** (`#F4F2F0`) paired with **Elevated Paper** (`#FFFFFF`) and **Deep Ink** (`#000000`).
- **Warm Dark & Light Section Alternation**: Dark hero and closing consultation bands juxtaposed with clean stone and white product breakdown sections to create compelling reading momentum without visual fatigue.
- **Weight-Disciplined Typography**: Regular weight (400) display headlines in large scale (48px / 40px) with tight negative tracking, paired with 11px uppercase tracked eyebrows and 16px body copy with generous line heights.
- **12px Card Radii**: A unified shape vocabulary applied across policy document cards, partner logo tiles, stat counters, and testimonial blocks.
- **Tangible Document Realism**: Presenting insurance policies not as vague concepts, but as realistic policy cards displaying starting rates, NCB percentages, 0% GST badges, and instant WhatsApp consultation links.

---

## Colors

The palette is intentionally narrow and grounded, shifting between deep ink and soft, warm stone surfaces.

| Token | Value | Role & Usage |
|---|---|---|
| `colors.ink` | `#000000` | Primary display text, dark section backgrounds, primary CTA buttons |
| `colors.muted-ink` | `#1A1919` | Dark cards, secondary button borders, dark mode canvas |
| `colors.surface` | `#212121` | Elevated dark components, mobile menu surfaces, dark card backgrounds |
| `colors.canvas` | `#F4F2F0` | Warm stone background for light sections, alternating band ground |
| `colors.paper` | `#FFFFFF` | Elevated policy cards, testimonial tiles, text on dark sections |
| `colors.border-subtle` | `#E5E2DE` | 1px hairline dividers on warm canvas and paper cards |
| `colors.border-dark` | `#2A2826` | 1px hairline borders for dark surfaces and inputs |
| `colors.text-secondary`| `#5A5753` | Secondary descriptive text, policy overviews, subtitles |
| `colors.text-muted`    | `#8A8680` | Tertiary captions, metadata, license notes |
| `colors.badge-emerald-bg` | `#EFFCF8` | Subtle mint background for GST and NCB savings badges |
| `colors.badge-emerald-text` | `#006642` | High-contrast forest green text for savings callouts |

### Color Section Alternation
1. **Hero Section (Dark Ink `#000000`)**: Deep contrast opening, establishing IRDAI certification, 15+ years experience, and 5,000+ protected families with clean white display typography.
2. **Partner Strip & Value Pillars (Warm Canvas `#F4F2F0`)**: 28+ leading insurer network (LIC, Tata AIA, Bajaj Allianz, Care Health, Star Health) resting on warm stone with greyscale and natural logo treatments.
3. **Featured Policy Breakdown (Paper `#FFFFFF`)**: 12px rounded cards showcasing health, term life, private car, and commercial insurance with transparent pricing and 0% GST highlights.
4. **Advisor Credibility & Testimonials (Warm Canvas `#F4F2F0`)**: Personal advisory focus on Amrut Patel, customer stories, claim support process, and Google Maps location.
5. **Direct Consultation Band (Dark Ink `#000000`)**: Low-friction closing CTA with instant WhatsApp message and phone contact.

---

## Typography

The typographic system adheres to Ramp's Swiss editorial discipline: high scale contrast, strict weight restraint, and negative display tracking.

| Token | Size | Weight | Line Height | Letter Spacing | Usage |
|---|---|---|---|---|---|
| `typography.hero-display` | 48px (3rem) | 400 | 50px | -0.01em (-0.48px) | Page titles, primary hero headline |
| `typography.section-display` | 40px (2.5rem) | 400 | 42px | -0.005em (-0.2px) | Major category and section headers |
| `typography.medium-display` | 28px (1.75rem)| 400 | 32px | 0 | Policy card headings, advisor name |
| `typography.body-large` | 20px (1.25rem)| 400 | 28px | 0 | Sub-headlines, lead introductory text |
| `typography.body` | 16px (1rem) | 400 | 24px (1.5) | 0 | Default paragraph copy, feature lists |
| `typography.body-small` | 14px (0.875rem)| 400 | 20px | 0 | Navigation links, card metadata, buttons |
| `typography.label` | 11px (0.6875rem)| 500 | 16px | +1.2px | Tracked uppercase section eyebrows & badges |
| `typography.mono-num` | 14px (0.875rem)| 500 | 20px | 0 | IRDAI Reg numbers, policy rates, phone numbers |

---

## Layout & Spatial Rhythm

### Container & Max-Width
- **Desktop Container**: Centered container with max-width `1200px` to `1280px` and `32px` to `48px` horizontal gutters.
- **Reading Measure**: Editorial text blocks are constrained to `640px` to `768px` for optimal legibility.

### Spacing Scale
- **Section Bands**: `80px` to `112px` vertical padding (`py-20` to `py-28`) for dramatic pacing between dark and light movements.
- **Card Internals**: `24px` standard internal padding (`p-6`), expanding to `32px` (`p-8`) on hero feature cards.
- **Grid Gaps**: Consistent `16px` (`gap-4`) to `24px` (`gap-6`) between policy cards and feature panels.

---

## Shapes & Geometry

- **12px (`rounded.lg`)**: The universal shape for policy cards, testimonial panels, stat cards, and standard action buttons.
- **Pill (`rounded.pill`)**: Reserved for WhatsApp floating triggers, marketing eyebrows, and savings badges ("0% GST", "Save 18% Tax").
- **Hairline Borders**: 1px subtle borders (`#E5E2DE` on light, `#2A2826` on dark) that provide structural crispness without heavy drop shadows.

---

## Components

### 1. Section Header Pattern
```html
<div class="mb-10 max-w-2xl">
  <span class="text-xs uppercase tracking-widest text-[#8A8680] font-medium block mb-2">
    IRDAI Reg. 2017342 • 15+ Years Trust
  </span>
  <h2 class="text-3xl sm:text-4xl text-[#000000] tracking-tight leading-tight font-normal">
    Clear policies. Impartial advice. Zero spam.
  </h2>
</div>
```

### 2. Policy Document Card
- **Background**: `#FFFFFF` (elevated paper) on `#F4F2F0` canvas.
- **Radius**: `12px` (`rounded-xl`), 1px subtle border (`border-[#E5E2DE]`).
- **Internal Padding**: `24px` (`p-6`).
- **Content Hierarchy**:
  1. Eyebrow category + Savings badge (`#EFFCF8` mint pill with `#006642` text).
  2. Starting price (e.g., `Starts from ₹714/yr*`) in crisp display typography.
  3. 3-point bullet checklist with subtle checkmark icons.
  4. Instant WhatsApp consultation button with pre-filled message parameter.

### 3. Primary & Secondary Buttons
- **Primary Button**: Solid ink (`bg-[#000000]`), paper text (`text-[#FFFFFF]`), `rounded-xl`, `px-5 py-3`, font-size `14px`.
- **Secondary Button**: Transparent background, ink text (`text-[#000000]`), 1px border (`border-[#1A1919]`), `rounded-xl`, `px-5 py-3`.
- **WhatsApp Direct Action**: `#000000` or `#25D366` pill button with embedded WhatsApp icon and telephone protocol.

### 4. Stat & Credibility Counter
- **Surface**: Warm stone `#F4F2F0` or dark surface `#1A1919`.
- **Number**: 36px–40px display font with JetBrains Mono numbers for exact tabular alignment.
- **Label**: 14px muted description beneath.

---

## Do's and Don'ts

### Do:
- **Do** alternate between dark (`#000000`) and warm stone (`#F4F2F0`) sections to create editorial rhythm.
- **Do** keep display type in regular weight (400) with tight negative tracking rather than aggressive bolding.
- **Do** maintain the 12px border radius across all primary cards and buttons.
- **Do** feature transparent starting rates (e.g. ₹714, ₹2,094, 0% GST) prominently to build immediate trust.
- **Do** provide direct, single-click WhatsApp and phone access to Amrut Patel on every key interaction surface.

### Don't:
- **Don't** add loud fluorescent gradients or tech-centric mesh backgrounds.
- **Don't** use pure stark white (`#FFFFFF`) as the full page background; let the warm stone canvas (`#F4F2F0`) ground the experience.
- **Don't** clutter cards with excessive badges or aggressive marketing countdown timers.
- **Don't** tighten body text line-height below `1.5` (`leading-relaxed` / 24px on 16px text).
- **Don't** hide advisor credentials or office address; trust in Indian insurance depends on physical and regulatory legitimacy.
