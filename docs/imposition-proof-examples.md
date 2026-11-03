# Original imposition proof examples

Use these small, original test specifications to evaluate page order and dimensions. They are arithmetic and physical acceptance examples, not evidence that every listed application has passed them. They intentionally omit production artwork and machine-specific tolerances. Use the printer's approved stock, margins, marks and finishing instructions.

## Eight-page saddle-stitched booklet

Create eight reading-order pages, numbered 1–8, each with a large upward arrow and a clear spine/fore-edge label. Select a left-bound, two-pages-per-side saddle-stitch layout without additional cover pages or blanks.

Eight finished pages require **two physical sheets**, printed on both sides: `8 ÷ 4 = 2`. This conventional left-to-right pairing is a useful reference:

| Physical sheet | Front pair | Back pair |
| --- | --- | --- |
| Outer | 8 · 1 | 2 · 7 |
| Inner | 6 · 3 | 4 · 5 |

The table specifies page pairing, not a universal printer-feed or reverse-face rotation instruction. Select duplex orientation in the application and test it on the actual device. Some workflows display the back viewed through the sheet; others show it directly.

**Accept only after:** nesting, folding and checking pages 1–8 in reading order; every upward arrow points correctly; the intended finished dimensions are retained; inner pages have acceptable margins after the agreed trim. Use stock-specific creep when required. An eight-page test with thin paper does not qualify a thick booklet.

The distinction between reading-order source pages and imposed booklet spreads is also described in [PDFImpose's booklet explanation](https://pdfimpose.com/make/stapled-booklets) and [JustImpose's booklet guide](https://justimpose.com/guides/booklet-imposition-page-order).

## Twenty-four numbered pieces, cut and stack

Create 24 single-sided source pages numbered 1–24. Assume a two-by-two grid, **six printed sheets**, four equal positions, no copies, no blanks and no reversed pile. Positions below are viewed face-up in reading order: top-left, top-right, bottom-left, bottom-right.

| Sheet | Top-left | Top-right | Bottom-left | Bottom-right |
| --- | --- | --- | --- | --- |
| 1 | 1 | 7 | 13 | 19 |
| 2 | 2 | 8 | 14 | 20 |
| 3 | 3 | 9 | 15 | 21 |
| 4 | 4 | 10 | 16 | 22 |
| 5 | 5 | 11 | 17 | 23 |
| 6 | 6 | 12 | 18 | 24 |

Keep sheet 1 at the top of the pile. After cutting, the four piles read 1–6, 7–12, 13–18 and 19–24 from top to bottom. Gather the piles in that order to obtain 1–24. Arithmetic: `24 ÷ 4 = 6` sheets; each pile has six pieces.

**Accept only after:** physically cutting and gathering every number without duplication or omission. Face-down output, reversed stacking, a different cutting route, duplex pieces or inserted blanks can require a different setup. Change one assumption and repeat the proof. Sequential N-up would instead place 1–4 on sheet 1; that does not produce the same four sequential piles.

## Business-card fit with bleed and gaps

This is a geometric example, not a printer specification. Assume portrait A4 `210 × 297 mm`, an outside exclusion margin of `10 mm` on every edge, an `85 × 55 mm` finished card, `3 mm` bleed on every side, and a separate `3 mm` gap **between complete bleed rectangles**.

| Item | Calculation | Result |
| --- | --- | --- |
| Available rectangle | `(210 − 20) × (297 − 20)` | `190 × 277 mm` |
| One complete bleed rectangle | `(85 + 2×3) × (55 + 2×3)` | `91 × 61 mm` |
| Two columns including one extra gap | `2×91 + 1×3` | `185 mm` |
| Four rows including three extra gaps | `4×61 + 3×3` | `253 mm` |
| Pieces per sheet | `2×4` | `8` |

The eight-up unrotated grid fits the assumed rectangle because `185 ≤ 190` and `253 ≤ 277`. A centered grid has `12.5 mm` from the physical left/right sheet edge to the outside bleed boundary and `22 mm` at top/bottom. Its trim-to-trim gap is `3 + 3 + 3 = 9 mm`: two neighboring bleed allowances plus the separate gap. **Do not add another 6 mm if your application's gutter setting already means trim-to-trim distance.** Read how the particular control is defined.

This is a fit example, not a claim of the maximum possible yield; rotation, mixed orientations, machine margins or another sheet could change it. Marks require space too: the example has not assigned a mark length or offset. Confirm they clear the bleed and fit both the sheet and the printer's imageable area before accepting the layout.

**Accept only after:** exporting at 100%, measuring a trimmed proof at `85 × 55 mm`, checking genuine artwork across each bleed band, inspecting all marks, and confirming the correct back lies behind each front. Print one already-imposed PDF page per sheet face. Applying the printer dialog's N-up or booklet option again can shrink or reorder an already-prepared layout.
