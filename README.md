# UNC PhD Dissertation LaTeX Template (Sample)

This repository provides a working dissertation scaffold based on the UNC dissertation class/style files included in this project.

## Files

- `UNC_dissertation.tex`: Main build entry point.
- `uncdissertation.cls` and `uncdissertation.sty`: Formatting logic.
- `ch1.tex`, `ch2.tex`, `ch3.tex`: Main chapter content files.
- `appA_Chapter1.tex`, `appA_Chapter2.tex`, `appA_Chapter3.tex`: Appendix content files.
- `Bibliography.bib`: BibTeX database.
- `ETDGuide2013.pdf`: Local submission guideline reference.

## Build

Run the following from the repository root:

```bash
pdflatex UNC_dissertation.tex
bibtex UNC_dissertation
pdflatex UNC_dissertation.tex
pdflatex UNC_dissertation.tex
```

If your environment has `latexmk`, you can also run:

```bash
latexmk -pdf UNC_dissertation.tex
```

## What is included

- Front matter: title page, copyright, abstract, acknowledgments.
- Table of contents, list of tables, and list of figures.
- Three chapter placeholders with sample text.
- Three appendices (one per chapter).
- Chicago-style bibliography and sample economics references.

## Customization checklist

1. Replace all placeholder titles and names on the title page.
2. Replace sample abstract and chapter text with dissertation content.
3. Update tables/figures and cross-references.
4. Expand or prune bibliography entries.
5. Rebuild and verify pagination, margins, and required section order before submission.

## Notes on guideline alignment

This template keeps the required dissertation structure sequence used by UNC submissions: front matter, manuscript chapters, appendices, and references. Always validate final formatting against the latest Graduate School requirements before filing.
