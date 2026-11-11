# CONSORT Flow Diagram Builder

Build participant flow diagrams at journal print size and export them as SVG, PDF, or high-resolution PNG.

## What it does

- **Templates:** CONSORT 2010 two-arm and three-arm trials, an observational (STROBE-style) cohort with sequential exclusions, and a blank start. Template numbers are placeholders that add up; replace them or clear them all.
- **Flexible layout:** each row is one level of the diagram, with 1 to 4 boxes. A single-box row can have an exclusion box on its right. Optional phase labels (Enrollment, Allocation, Follow-Up, Analysis) run down the left side.
- **Count checks:** flags exclusion reasons that don't add up to their total, and rows whose counts don't match the row above after exclusions.
- **Print-ready output:** the figure is built in millimetres at the final size. Choose the width (one column, 1.5 columns, two columns, or custom), font (Arial/Helvetica or Times New Roman), font size, line weight, count format, and a black-and-white, greyscale, or UVA color theme.
- **Export:** SVG and PDF are vector files you can edit in Illustrator or Inkscape. PNG is exported at 300, 600, or 1200 dpi with the resolution recorded in the file.
- **Project files:** work saves automatically in your browser. Save a project as `.json` to share a diagram with the lab or reopen it later.

## How to use it

1. Download `index.html` and open it in Chrome, Edge, Firefox, or Safari.
2. Pick a template, then edit the boxes and counts.
3. Check the **Checks** panel, set the size and appearance, and export.

Everything runs in the browser, so no data leave your computer.

## Notes

- PDF export uses the standard Helvetica or Times fonts. The characters ≥, ≤, ≠, ≈, and − are supported; other symbols outside standard Western text print as "?" in the PDF. Use SVG or PNG for those.
- The Aptos font option works for SVG and PNG only, and only if Aptos is installed.
- The count checks can't know your study design, so treat them as a second pair of eyes.

## Reference

Schulz KF, Altman DG, Moher D; CONSORT Group. CONSORT 2010 statement: updated guidelines for reporting parallel group randomised trials. *BMJ*. 2010;340:c332. [doi:10.1136/bmj.c332](https://doi.org/10.1136/bmj.c332)

## Details

- **File:** `index.html` (self-contained; no internet connection needed)
- **Author:** Christopher Kuenze, PhD, ATC, FNATA
- **Last updated:** November 2026
