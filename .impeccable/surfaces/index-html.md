---
version: 1
slug: "index-html"
primary_target: "index.html"
related_targets: []
---

# Surface brief: index.html (planning board)

Scope: the whole app, one self-contained page. Visitor mode: Operate.

Audience and job: one person planning their own project (first board: a drone build). They capture cards, move them across lists, add notes, labels and sometimes an image, and keep the board as a JSON file they open and save.

Constraints: single HTML file, no build. Card fields limited to title, description, labels, one optional image. JSON round-trips everything, images included (data URLs). Sample content is illustrative and labelled as sample.

## Direction contract

THESIS: A planning board in one neutral scale where only information carries colour: labels, the save state, and the dragged card's landing slot. It refuses Trello's blue wallpaper with floating white tiles, and the SaaS habit of washing every surface in a brand colour.

OWN-WORLD: A seven-step grey scale from #FAFAFA to #111111 over a soft radial ground with micro-noise. One chartreuse accent, used only for "live" (the save-state ring, the drop slot, text selection). Satoshi at 400/500/700 with tabular numerals. 1px hairlines, 10 to 14px radii, soft offset shadows. Solid near-black primary button carrying the accent ring; hairline ghost secondaries. Labels are quiet tinted pills named after Trello's colours.

STORY: The user opens their JSON (or starts from the sample), scans lists left to right, drags cards between stages, opens a card to edit its notes, labels and cover, and saves back to the same file. The Save button always says whether the file matches the board.

FIRST VIEWPORT: A 56px top bar: board title (20px, 700) and file name on the left; Open (ghost) and Save (solid black, accent ring, status text) on the right. Below, lists as 280px columns from the left edge on the grey ground, white cards with optional full-bleed covers, a ghost "Add list" column closing the row. The primary action is Save, top right.

FORM: Neutral Instrument, from the dealt catalog challenger digital-design-canon-monochrome-product-marketing, chosen by the user over the assigned direction (candidate 4 of the grounded list, Mission Plan); seed key eed65291. Signature interaction: pointer drag with a lifted card, FLIP reflow of its neighbours, and the save ring turning from hollow (unsaved) to filled (saved).

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance

## Unresolved

- Due dates and checklists are out of scope until asked for.
- Light theme only; the use scene is a desk in daylight.
