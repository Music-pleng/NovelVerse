---
name: Serif & Spark
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#44474a'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#75777b'
  outline-variant: '#c5c6ca'
  surface-tint: '#5a5f64'
  primary: '#5a5f64'
  on-primary: '#ffffff'
  primary-container: '#f1f5fb'
  on-primary-container: '#6b7075'
  inverse-primary: '#c2c7cd'
  secondary: '#06658b'
  on-secondary: '#ffffff'
  secondary-container: '#8fd4ff'
  on-secondary-container: '#005c80'
  tertiary: '#325cac'
  on-tertiary: '#ffffff'
  tertiary-container: '#f3f4ff'
  on-tertiary-container: '#466dbe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dfe3e9'
  primary-fixed-dim: '#c2c7cd'
  on-primary-fixed: '#171c20'
  on-primary-fixed-variant: '#42474c'
  secondary-fixed: '#c5e7ff'
  secondary-fixed-dim: '#89cffa'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6a'
  tertiary-fixed: '#d9e2ff'
  tertiary-fixed-dim: '#afc6ff'
  on-tertiary-fixed: '#001944'
  on-tertiary-fixed-variant: '#114392'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-reading-lg:
    fontFamily: Inter
    fontSize: 19px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0.01em
  body-reading-md:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: 0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
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
  gutter: 1.5rem
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

The design system is crafted for an immersive, modern digital reading and serial fiction platform. It bridges the gap between editorial sophistication and dynamic webtoon energy, cultivating an atmosphere that feels inviting, expansive, and distraction-free.

### Brand Personality & Core Mood
- **Immersive & Calm:** Reading requires sustained visual comfort. The interface recedes into the background, prioritizing content readability and cover art vitality.
- **Warm & Engaging:** Unlike cold institutional archives, the system uses expressive accents to celebrate creator-reader interactions, updates, serialized chapter drops, and reading milestones.
- **Refined & Contemporary:** Influenced by modern editorial libraries and top-tier storytelling platforms, layouts feel spacious, precise, and deliberate.

### Design Movement
The visual language blends **Refined Content-First Minimalism** with subtle **Tactile Warmth**. It relies on generous negative space, gentle boundary definitions via low-contrast structural borders, and delicate ambient shadows that give graphic covers and navigation cards a tactile, paper-adjacent presence.

## Colors

The palette balances vibrant expressive focal points with calm, high-legibility surfaces optimized for extended reading sessions, now configured in a clean light mode.

### Palette Architecture
- **Primary (`#F1F5FB` - Soft Pale Slate):** Used for immediate calls-to-action, bookmark states, subscription highlights, reader reactions, and primary interactive moments.
- **Secondary (`#8DD3FE` - Sky Blue Accent):** Applied to serialization tags, chapter index badges, metadata links, and secondary interactive states.
- **Tertiary (`#7FA5FA` - Periwinkle Blue):** Dedicated to VIP unlocks, coin balances, reader rankings, and critique trophies.
- **Neutral Deep (`#0F172A` - Dark Slate):** Anchors high-contrast typography, primary headings, and critical labels.
- **Neutral Muted (`#334155` - Slate):** Renders long-form prose and chapter synopsis text with optimized contrast.
- **Surface Clean (`#FFFFFF`):** Base canvas for reading areas and active inputs in light mode.
- **Surface Warm Light (`#F8FAFC` to `#E2E8F0`):** Card backdrops, reader shelf tiles, and drawer containers.
- **Structural Outlines (`#CBD5E1`):** Soft perimeter strokes defining card edges, chapter dividing lines, and reading control dividers.

### Theme & Contrast Guidelines
The default mode is light (`color_mode: light`), featuring crisp light surfaces and high-contrast dark text inversion to ensure optimal readability and eliminate eye strain during daytime reading sessions.

## Typography

The typographic hierarchy harmonizes contemporary Latin geometric forms with broad multi-script and localized Thai pairing support.

### Hierarchy & Role Distribution
- **Headings & Display (`Plus Jakarta Sans`):** Delivers a welcoming, premium identity with open counter-spaces and rounded terminal nuances. Used for web novel titles, ranking numbers, showcase banners, and author bios.
- **Narrative Prose & Body (`Inter`):** Engineered for ultra-clean legibility at sustained intervals. Features optimized vertical metric alignment, extended ascenders/descenders, and wide language glyph sets.
- **Reader Line Height Scaling:** Reading bodies (`body-reading-lg`, `body-reading-md`) utilize generous line-height ratios (~1.75x–1.8x) to ensure smooth eye travel across serialized text columns without line skipping.

## Layout & Spacing

The layout balances browse-mode density with read-mode focus using a balanced spacing scale (`spacing: 2`).

### Grid & Layout Systems
- **Catalog & Discovery View:** Employs a 12-column responsive fluid grid on desktop (`margin: 2rem`, `gutter: 1.5rem`) adjusting to a 4-column system on mobile (`margin-mobile: 1rem`, `gutter-mobile: 0.75rem`). Book cover grids scale dynamically: 5–6 items per row on large viewports, 3 on tablet, and 2.2 on mobile (horizontal swipe carousel).
- **Novel Reading Canvas:** Constrained to an optimal reading column with max width `720px` centered on canvas. Desktop side margins transition to auxiliary reader functions (floating table of contents, progress pill, comment stream dock).
- **Webtoon & Vertical Strip Canvas:** Constrained to a max width of `800px` without horizontal padding; image assets flush edge-to-edge with contextual overlay navigation that autohides on scroll.

## Elevation & Depth

Visual hierarchy combines stacked surface tones with delicate ambient shadows to evoke the physical weight of art prints and books within a light interface.

### Elevation Levels
- **Level 0 (Flat / Reading Base):** `#FFFFFF` or `#F8FAFC`. Zero elevation, zero shadow.
- **Level 1 (Cards & Structural Units):** Bounded by a 1px border of `#CBD5E1` and accompanied by a soft diffused shadow: `0px 2px 8px -2px rgba(0, 0, 0, 0.05)`.
- **Level 2 (Book Covers & Interactive Tiles):** Book covers receive a structured dual-layer depth: `0px 4px 14px -3px rgba(0, 0, 0, 0.08), 0px 2px 4px -2px rgba(0, 0, 0, 0.04)`. Hover transitions elevate to `0px 10px 24px -4px rgba(0, 0, 0, 0.12)` with a subtle upward translate of 2px.
- **Level 3 (Floating Bars & Bottom Sheets):** Reader customization drawers, bottom navigation bars, and chapter quick-select menus use `0px 12px 32px -4px rgba(0, 0, 0, 0.12)` alongside a 1px border `#CBD5E1` and an optional backdrop-filter blur of `12px` at 90% opacity.

## Shapes

The design system adopts a **Rounded** shape language (`roundedness: 2`, base radius `0.5rem` / `8px`).

### Surface Application
- **Standard UI Containers (Cards, Modals):** `0.5rem` to `1rem` (`rounded-lg`).
- **Book Covers & Artwork:** Strictly `0.5rem` (`8px`) on outer edges to maintain geometric book spine proportions while softening harsh digital corners.
- **Interactive Tags, Badges & Pills:** Elevated to pill shape (`9999px` / full roundedness) to signal clickability, ranking positions, and status states (e.g., "Updated", "Chapter 42", "Top 10").
- **Avatars:** Fully circular (`rounded-full`) with optional 2px border offset for creator distinction.

## Components

### 1. Buttons
- **Primary Action:** Solid `#0F172A` background, light label, full pill radius or `rounded-lg`, zero horizontal border. Subtle inner glow on active state.
- **Secondary Action:** Transparent base with `#CBD5E1` border, `#0F172A` text, hover transition to `#F1F5FB` background.
- **Reader Icon Floating Action Buttons:** Circular (`44px` diameter) with Surface Light backdrop, Level 2 elevation, hosting icon vectors (font scale adjust, day mode toggle, contents list).

### 2. Badges & Chips
- **Ranking Pills:** Solid `#7FA5FA` text on `#F1F5FB` background for top rank positions; `#0284C7` text on `#F8FAFC` for genre markers.
- **Chapter Status Chips:** Miniature pill (`label-sm`), featuring high-contrast dot indicators (e.g., Sky blue dot for fresh unread chapters, muted slate for viewed).

### 3. Book Cover & Webtoon Cards
- **Aspect Ratio:** Standard novel covers use `2:3` ratio; comic thumbnails use `3:4`.
- **Structure:** Inner image masked with `rounded-md`, resting inside card surface with subtle ambient shadow. Bottom text group includes 2-line truncated title (`title-md`), author line (`body-sm`), and a bottom row displaying star ratings and bookmark tallies.

### 4. Search Bar
- Expansive, rounded pill container with `#F1F5FB` background, `#64748B` icon prefix, clear text action on input, and instant dropdown panel previewing matching novel covers, tag matches, and author names.

### 5. Reader Customization Controls
- **Floating Settings Palette:** Segmented controls for light canvas tones.
- **Typography Steppers:** Direct buttons to modify font size from 14px to 24px, accompanied by line-spacing toggles and font family selection (Sans vs Serif).

### 6. Inputs & Comment Fields
- Outlined with `#CBD5E1`, focusing to `#8DD3FE` with a soft `0 0 0 3px rgba(141, 211, 254, 0.3)` focus ring. Comment threads display nested user avatars, time badges, like counter reactions, and spoiler-shield blur covers.