---
name: Trello Clone (planning board)
description: A file-backed planning board drawn in one neutral scale, where only information carries colour.
colors:
  ground: "#efefef"
  surface-0: "#ffffff"
  surface-1: "#fafafa"
  surface-2: "#f3f3f3"
  surface-3: "#ebebeb"
  line: "#e4e4e4"
  line-card: "#e6e6e6"
  line-strong: "#d2d2d2"
  line-hover: "#b9b9b9"
  muted: "#6b6b6b"
  ink-quiet: "#555555"
  ink-2: "#3d3d3d"
  ink: "#111111"
  ink-hover: "#2a2a2a"
  accent: "#b5d334"
  accent-wash: "#f2f7dd"
  accent-line: "#a3c037"
  accent-sel: "#e2efb0"
  danger: "#b42318"
  danger-wash: "#fdecea"
  label-green-bg: "#e3f2e6"
  label-green-ink: "#1f6b35"
  label-green-dot: "#3fa45b"
  label-yellow-bg: "#faf0c6"
  label-yellow-ink: "#735708"
  label-yellow-dot: "#e2b203"
  label-orange-bg: "#fde7d4"
  label-orange-ink: "#984a0c"
  label-orange-dot: "#f08a24"
  label-red-bg: "#fbe3e0"
  label-red-ink: "#a3271b"
  label-red-dot: "#e2483d"
  label-purple-bg: "#efe6fb"
  label-purple-ink: "#6236a8"
  label-purple-dot: "#9f6ad4"
  label-blue-bg: "#e2ebfb"
  label-blue-ink: "#1f4fa3"
  label-blue-dot: "#3b74d6"
  label-sky-bg: "#dcf1f7"
  label-sky-ink: "#0f6278"
  label-sky-dot: "#2aa8c9"
  label-lime-bg: "#ecf4d4"
  label-lime-ink: "#4c660b"
  label-lime-dot: "#94c748"
  label-pink-bg: "#fbe4ef"
  label-pink-ink: "#a12562"
  label-pink-dot: "#e0559a"
  label-black-bg: "#e9e9e9"
  label-black-ink: "#2b2b2b"
  label-black-dot: "#4a4a4a"
typography:
  headline:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.015em"
  title:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.015em"
  title-list:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    lineHeight: 1.3
  body:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.45
  body-long:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "13.5px"
    fontWeight: 500
    lineHeight: 1
  caption:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "12.5px"
    fontWeight: 500
    fontFeature: "tnum"
  pill:
    fontFamily: "Satoshi, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "11.5px"
    fontWeight: 500
    letterSpacing: "0.005em"
rounded:
  pill: "6px"
  control-sm: "8px"
  control: "9px"
  card: "10px"
  toast: "11px"
  panel: "12px"
  list: "14px"
  round: "50%"
spacing:
  xs: "4px"
  sm: "8px"
  md: "14px"
  lg: "20px"
  xl: "24px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.surface-0}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 14px"
    height: "34px"
  button-primary-hover:
    backgroundColor: "{colors.ink-hover}"
  button-ghost:
    backgroundColor: "{colors.surface-0}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: "0 14px"
    height: "34px"
  button-ghost-hover:
    backgroundColor: "{colors.surface-1}"
  button-danger:
    backgroundColor: "transparent"
    textColor: "{colors.danger}"
    rounded: "{rounded.control}"
    padding: "0 10px"
    height: "34px"
  button-danger-hover:
    backgroundColor: "{colors.danger-wash}"
  icon-button:
    backgroundColor: "transparent"
    textColor: "{colors.ink-quiet}"
    rounded: "{rounded.control-sm}"
    size: "30px"
  chip:
    backgroundColor: "{colors.surface-0}"
    textColor: "{colors.ink-2}"
    typography: "{typography.caption}"
    rounded: "{rounded.control-sm}"
    padding: "0 9px"
    height: "26px"
  input:
    backgroundColor: "{colors.surface-0}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    padding: "0 11px"
    height: "34px"
  list:
    backgroundColor: "{colors.surface-1}"
    rounded: "{rounded.list}"
    width: "280px"
  card:
    backgroundColor: "{colors.surface-0}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.card}"
    padding: "9px 11px 10px 12px"
  label-pill:
    typography: "{typography.pill}"
    rounded: "{rounded.pill}"
    padding: "0 7px"
    height: "20px"
  menu:
    backgroundColor: "{colors.surface-0}"
    rounded: "{rounded.panel}"
    padding: "6px"
  menu-item-hover:
    backgroundColor: "{colors.surface-2}"
  sheet:
    backgroundColor: "{colors.surface-0}"
    width: "500px"
  toast:
    backgroundColor: "{colors.ink}"
    textColor: "#f2f2f2"
    rounded: "{rounded.toast}"
    padding: "9px 9px 9px 14px"
  drop-slot:
    backgroundColor: "{colors.accent-wash}"
    rounded: "{rounded.card}"
---

# Design System: Trello Clone (planning board)

## Overview

**Creative North Star: "The Neutral Instrument"**

The board is a precision tool on a desk in daylight: a quiet grey field, white cards resting on pale columns, and near-black ink. Everything structural (ground, lists, cards, controls, chrome) is drawn from one neutral scale running from pure white to #111111. Colour is reserved for information. Labels carry their meaning in tinted pills, and a single chartreuse accent marks what is live: the save-state ring, the slot a dragged card will land in, a file dragged over the cover dropzone, and text selection.

Density is Trello-quick rather than airy: 280px columns, 8px gaps between cards, 34px controls, 14px body text. Depth is soft and physical (hairlines plus low, diffuse shadows), and motion is short and eased with one curve. The signature behaviours are the lifted drag card, which tilts and grows slightly under a deeper shadow while its neighbours reflow, and the save ring, which is hollow while the board differs from the file and fills when they match.

The build rejects a coloured wallpaper behind floating tiles and any brand colour washed across surfaces. The ground stays grey and the chrome stays neutral.

**Key Characteristics:**
- One neutral scale for all structure; colour only where it carries information.
- A single chartreuse accent, always meaning "live" or "landing here".
- Satoshi at three weights (400, 500, 700), with tabular figures for counts and status.
- 1px hairlines and soft, diffuse shadows; radii from 6px to 14px that grow with the size of the container.
- Solid near-black primary action; white hairline ghosts for everything secondary.

## Colors

A cool-neutral grey ramp carries everything, with one chartreuse signal and ten quiet label tints.

### Primary
- **Live Chartreuse** (accent): the save ring's stroke and fill, and nothing decorative. Its companions do the same job at lower volume: **Chartreuse Wash** (accent-wash) fills the drop slot, a card targeted by a file drop and the active dropzone; **Chartreuse Edge** (accent-line) is the dashed or solid border of those states; **Selection Chartreuse** (accent-sel) is the `::selection` background.

### Neutral
- **Desk Grey** (ground): the board's ground, lit by a soft white radial glow from the upper left and a 5% micro-noise texture.
- **Paper White** (surface-0): cards, inputs, menus, the card sheet, ghost buttons.
- **Column White** (surface-1): lists, the top bar, the label editor, the cover dropzone, ghost hover.
- **Pale Grey** (surface-2) and **Hover Grey** (surface-3): menu item hover, cover backgrounds, the sheet title hover (surface-2), and the board title hover (surface-3).
- **Hairline** (line), **Card Hairline** (line-card), **Firm Hairline** (line-strong), **Hover Hairline** (line-hover): borders from quietest to firmest. Lists and menus take `line`, cards `line-card`, controls `line-strong`, and controls step to `line-hover` on hover.
- **Muted Ink** (muted): counts, status text, field labels, hints, menu icons.
- **Quiet Ink** (ink-quiet): icon buttons and "Add a card" at rest.
- **Secondary Ink** (ink-2): chip text, unsaved status, ghost "Add list".
- **Ink** (ink) and **Ink Hover** (ink-hover): text, the primary button, the toast, focus outlines.

### Semantic
- **Danger** (danger) on **Danger Wash** (danger-wash): destructive buttons and menu items only.

### Label tints
Ten families named after Trello's colours (green, yellow, orange, red, purple, blue, sky, lime, pink, black), so imported boards keep their meaning. Each has a pale background, a dark ink for the pill text, and a saturated dot for swatches, picker dots and the unnamed label bar.

### Named Rules
**The Information-Only Colour Rule.** Hue appears only where it says something: a label, the save state, a drop target, danger. Every surface, border and control that is not one of those stays on the neutral ramp.

**The Live Accent Rule.** Chartreuse means "live now" or "this lands here". It never decorates, never fills a resting surface, and never sits on a button background. It shows as the save ring inside the black button, or as a wash plus edge on a target.

## Typography

**Display Font:** Satoshi (embedded woff2, 400/500/700), with ui-sans-serif and system-ui fallbacks
**Body Font:** Satoshi
**Label/Mono Font:** Satoshi; numerals switch to tabular figures in counts and save status

**Character:** One geometric grotesk at three weights. Hierarchy comes from weight and a small size range (11.5px to 22px), not from a second face.

### Hierarchy
- **Headline** (700, 22px, 1.25, -0.015em): the card title in the sheet.
- **Title** (700, 20px, 1.2, -0.015em): the board title in the top bar and the empty-state heading. Drops to 17px below 640px.
- **List title** (700, 14px, 1.3): list headers.
- **Body** (400, 14px, 1.45): card titles, inputs, general text.
- **Body long** (400, 14px, 1.6): the description textarea.
- **Label** (500, 13.5px; 13px on small buttons): buttons, menu items, "Add a card", the dropzone heading.
- **Caption** (500 or 400, 12px to 13px): chips, save status, counts, field labels, keyboard hints, menu sub-lines.
- **Pill** (500, 11.5px, 0.005em): label pills on cards.

### Named Rules
**The Three Weights Rule.** Use only 400, 500 and 700, the three embedded cuts. Bold is reserved for titles (board, list, card sheet); controls speak at 500.

**The Tabular Count Rule.** Counts and save status use `font-variant-numeric: tabular-nums` so they don't shift width when the numbers change.

## Layout

The app is a two-row grid: a 56px top bar and a full-height board. The top bar puts the mark, the inline-editable board title and the file chip on the left, and the save status, Open (ghost), Save (primary) and an overflow menu on the right. The board is a horizontal row of 280px lists with 14px gaps and 20px/24px/24px padding, scrolling sideways, and it ends with a dashed ghost "Add list" column. Inside a list, cards stack with 8px gaps, with 8px side padding and a footer holding "Add a card". Lists cap at full height and scroll their cards internally.

The card sheet is a right-docked dialog 500px wide (full width on small screens) with a hairline-separated head, a scrolling body with 24px gaps between sections, and a foot.

Below 760px the save status text hides (the ring stays). Below 640px the file chip hides, Open becomes icon-only, the title drops to 17px, the board padding tightens to 14px/12px with 10px gaps, and lists widen to `100vw - 52px` with mandatory horizontal scroll-snap, one list per screen.

## Elevation & Depth

The system is a hybrid: hairlines define every edge, and soft, diffuse shadows add physical weight that grows with how far an object has risen from the ground. Shadows are always tinted from ink (rgba 17,17,17), always offset downward, and never hard-edged.

### Shadow Vocabulary
- **Card rest** (`0 1px 2px rgba(17,17,17,.05)`): cards and the composer at rest.
- **Card hover** (`0 6px 16px -6px rgba(17,17,17,.14), 0 1px 2px rgba(17,17,17,.05)`): a card under the pointer.
- **List** (`0 1px 2px rgba(17,17,17,.04), 0 14px 30px -24px rgba(17,17,17,.22)`): columns, which sit just above the ground.
- **Pop** (`0 12px 28px -12px rgba(17,17,17,.24), 0 2px 6px rgba(17,17,17,.06)`): menus and the file drop hint.
- **Lift** (`0 16px 30px -12px rgba(17,17,17,.30), 0 4px 10px -4px rgba(17,17,17,.10)`): the dragged card.
- **Sheet** (`-20px 0 40px -24px rgba(17,17,17,.28)`) over a 20% ink backdrop; **Toast** (`0 14px 34px -12px rgba(17,17,17,.45)`).
- **Focus halo** (`0 0 0 3px rgba(17,17,17,.07)`) with an ink border on focused text fields.

### Named Rules
**The Rise With Intent Rule.** The shadow deepens only with the object's state: rest, hover, popover, lift. A surface never wears a deeper shadow than its role calls for.

## Shapes

Corners are gently rounded and scale with the container: 6px label pills, 7px inline title targets, 8px small controls and chips, 9px standard controls, 10px cards and the composer, 11px toasts, 12px menus and sheet panels (label editor, cover, dropzone), 14px lists. Swatches, picker dots and the save ring are full circles. Borders are 1px hairlines. Dashed borders mark potential space (the quiet "Sample board" chip, "Add list", the cover dropzone, and the drop slot at 1.5px). Card covers bleed to the card edges at 16:9 above a hairline.

## Components

### Buttons
Precise and quiet; one solid black voice per surface.
- **Shape:** gently rounded (9px; 8px on the 30px small size), 34px tall, 14px side padding, label type at 500.
- **Primary:** ink background, white text, hover to ink-hover. The Save button carries the save ring (12px circle, 2px accent stroke) ahead of its label.
- **Ghost:** Paper White with a Firm Hairline border; hover moves the border to Hover Hairline and the fill to Column White.
- **Danger:** transparent, Danger text, Danger Wash on hover.
- **Link:** underlined secondary ink with a hairline-coloured underline that turns to the text colour on hover.
- **Icon button:** 30px (or 34px) square, transparent, Quiet Ink; hover takes a 6% ink tint, and expanded takes 8%.
- **Active / Disabled:** press scales to 0.98; disabled drops to 45% opacity.
- **Focus:** 2px ink outline at 2px offset on every focusable element.

### Chips
- **Style:** 26px, Paper White, hairline border, 8px radius, caption type in Secondary Ink, with a 14px muted icon. Shows the open file name.
- **Quiet variant:** transparent with a dashed Firm Hairline border and muted text; marks the board as sample content.

### Cards / Containers
- **List:** Column White, hairline border, 14px radius, list shadow, 280px wide. The header is a bold title button with a muted tabular count and an overflow icon button, and it is the drag handle for reordering lists.
- **Card:** Paper White, Card Hairline border, 10px radius, rest shadow; hover firms the border and takes the hover shadow. Body padding 9px 11px 10px 12px; label pills sit above the title with 4px gaps, and a muted meta row with 14px icons marks a description.
- **Cover:** optional full-bleed 16:9 image on Pale Grey. A broken image reads "Image unavailable" in muted caption.

### Label Pill (signature)
20px tall, 6px radius, the family's pale background and dark ink, pill type. A label with no name renders as a 34px by 8px bar in the family's dot colour. In the sheet, label toggles are 30px hairline buttons with a 9px dot; pressed ones take the family's tint and lose the border.

### Inputs / Fields
- **Style:** Paper White, Firm Hairline border, 9px radius (8px small), 34px tall; placeholders in a mid grey (#707070). The description textarea is 10px radius at the long body line height and grows with its content.
- **Focus:** border turns to ink with the 3px focus halo. Inline-edited titles (board, list, sheet) are borderless until hover tints them and focus gives them the same ink border and halo.
- **Select:** 30px, hairline, custom chevron, with the same hover and focus.

### Composer
An inline card-shaped textarea (10px radius, rest shadow) that grows with content, followed by a primary "Add card" button, a close icon button and a muted keyboard hint aligned right.

### Menus and Swatches
- **Menu:** Paper White, hairline, 12px radius, 6px padding, pop shadow; opens with a 140ms fade-and-rise. Items are 34px rows at 500 with muted 16px icons, a Pale Grey hover, an optional right-aligned keyboard hint or muted sub-line, and hairline dividers. Danger items turn the text and icon red.
- **Swatches:** 28px circles in the label dot colours on a five-column grid, with a faint inset ring; the selected one gets a white gap and a 2px ink ring.

### Card Sheet
A right-docked dialog that slides in 28px with a fade over 260ms on the shared curve. Head: breadcrumb and a list select. Body: the headline title, then Labels, Description and Cover sections, each with a muted field label. The cover dropzone is a dashed 12px panel that turns to Chartreuse Wash with a solid Chartreuse Edge while a file is over it. Foot: delete (danger) and close.

### Toast
An ink pill-ended bar (11px radius) bottom-centre, light text, with underlined inline action buttons such as Undo. It rises 14px and fades in. Plain toasts carry no action.

### Drag: Ghost and Drop Slot (signature)
Pointer drag lifts the card into a fixed ghost that rotates 1.75deg, scales to 1.025 and takes the lift shadow, all over 180ms. The source leaves the flow. A drop slot the size of the card (or the list, when reordering lists) opens where it will land, filled with Chartreuse Wash inside a 1.5px dashed Chartreuse Edge. Neighbours reflow with a 200ms FLIP transform on the shared curve, and on release the ghost glides into the slot over 200ms.

### Save State (signature)
The ring is hollow while the board differs from the file and filled with accent once they match. The fill fades in over 250ms and pops through scale 0.55, 1.3, 1 over 420ms when a save completes. On wide screens a muted tabular status sits beside the button and steps to Secondary Ink while unsaved.

### Motion
One curve throughout: `cubic-bezier(.2, .8, .2, 1)`. Hover colour changes take 150ms, the press scale 100ms, popovers 140ms, the sheet 260ms and drag 180ms to 200ms. Under `prefers-reduced-motion`, all animation and transition durations collapse to near zero.

## Do's and Don'ts

### Do:
- **Do** build every surface, border and control from the neutral ramp, from Paper White (#ffffff) to Ink (#111111).
- **Do** reserve chartreuse for live state: the save ring, drop slots and drop targets, and text selection.
- **Do** keep one solid ink primary button per surface; everything else is a hairline ghost, a link or an icon button.
- **Do** use soft, ink-tinted, downward shadows that deepen with state (rest, hover, pop, lift).
- **Do** use dashed hairlines for space that can be filled (add list, dropzone, drop slot, sample marker).
- **Do** use tabular figures for counts and save status.
- **Do** use the shared curve `cubic-bezier(.2, .8, .2, 1)` and keep motion under 300ms, except the 420ms save-ring pop.

### Don't:
- **Don't** put a brand or accent colour on a resting surface, a ground, or a button fill; the ground stays Desk Grey.
- **Don't** use label tints for chrome; they belong to labels only.
- **Don't** use Satoshi weights other than 400, 500 and 700; only those three are embedded.
- **Don't** use hard-edged or zero-blur offset shadows; depth here is diffuse.
- **Don't** add a second typeface; hierarchy comes from weight and size within Satoshi.
