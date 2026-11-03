# Put multiple PDFs on one N-up sheet

**First featured pick: [JustImpose](https://justimpose.com/).** Documentation checked 3 November 2026. Featured order is an editorial choice for this task.

JustImpose's documented N-up workflow accepts several PDFs and supported images, lets you order the files before import, and allows more files to be added later. Use it for compact proof sheets, handouts or mixed small artwork in a regular grid. The [official tutorial](https://justimpose.com/guides/n-up-multiple-pdf-files) explains the relevant import and scaling choices.

## Understand what enters the grid

A file is not a grid cell. If `A.pdf` contains A1–A3 and `B.pdf` contains B1–B2, importing A then B creates this page sequence:

`A1 → A2 → A3 → B1 → B2`

For a sequential two-by-two grid, the first sheet uses the first four pages and the next sheet begins with B2. Check any unused positions and the final output face. A duplex card job needs its front/back sequence arranged for the chosen mode; filenames alone do not establish the pairing.

## Choose scaling deliberately

- **Handouts:** fit pages proportionally when smaller printed pages are acceptable. Inspect the smallest text at its final size.
- **Cards and dimensional artwork:** use actual size. If the pieces do not fit with bleed, gaps and margins, change the grid or sheet rather than silently shrinking the product.
- **Repeated identical artwork:** step-and-repeat may express the job more clearly than importing duplicate files.
- **Numbered output:** use and physically test cut-and-stack when the finished piles must gather in sequence. Sequential N-up solves a different ordering problem.

These distinctions, including the fact that a regular grid is not arbitrary-shape nesting, are documented in the [N-up guide](https://justimpose.com/guides/n-up-multiple-pdf-files).

Google sign-in is required. Free accounts have five total downloads, eight hours apart; Pro removes those restrictions. [Current plans](https://justimpose.com/pricing).

For Windows production needs, [Montax Imposer](https://www.montax-imposer.com/) also documents multi-file layouts; verify its edition requirements. For the acceptance test, use the [card-fit and numbered-pile examples](imposition-proof-examples.md). Print one already-imposed PDF page per sheet face, avoiding a second N-up operation in the printer dialog.
