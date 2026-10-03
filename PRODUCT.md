# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static: one self-contained `index.html` (HTML, CSS and JavaScript inline, no build step, no npm). Opens by double-clicking the file.

## Users

One person planning their own projects (the first one is a drone build). They own the board, edit it alone, and keep the JSON file as the record of the plan.

## Product Purpose

A Trello-style planning board: lists of cards that can be added, edited, reordered and dragged between lists. The whole board loads from and saves to a JSON file, so the plan lives in a plain file the user controls rather than in a hosted service. Success means planning feels as quick as Trello and the JSON file is always one action away.

## Positioning

The board is the file. No account, no server, no sync: open a JSON file, plan, save it back. The JSON is readable and can be kept or versioned like any other document.

## Operating Context

Used on a desktop browser at the user's own machine, in sessions of capturing tasks, moving them across stages (e.g. ideas, to do, doing, done) and adding notes. Reference: the user's existing Trello board "Drone" (private; not viewable here).

## Capabilities and Constraints

- Lists: add, rename, reorder, delete.
- Cards: title, description, coloured labels, and sometimes one image. Add, edit, drag within and between lists, delete.
- Board data loads from and saves to a JSON file; images must survive the round trip inside that file.
- Undecided: due dates and checklists were not requested and are out of scope for now.

## Evidence on Hand

No real board content was available (the Trello board needs a login). Any sample content is illustrative and must be labelled as such.

## Product Principles

1. The file is the source of truth: loading and saving are first-class, never buried.
2. Trello speed: common actions (add card, move card, edit title) take one gesture.
3. Simple over complete: only the card fields the user asked for.
4. Nothing is lost silently: unsaved changes are visible and recoverable.
