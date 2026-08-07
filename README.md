# More seeds yield more shoots, but not higher per-seed establishment in a clam-mediated seagrass restoration experiment

This repository contains the data, code, and manuscript files for a manuscript in preparation for submission to *Frontiers in Marine Science*. It is intended to provide a reproducible record of the analyses and manuscript development.

## Repository structure

```text
├── data/               # Data and metadata
├── docs/               # References, templates, and manuscript drafts
│   └── drafts/         # Previous and coauthor-reviewed versions
├── output/             # Quarto-rendered files (not tracked by Git)
├── photos/             # Photographs used in the methods figure
├── submissions/        # Files associated with formal submissions
├── _quarto.yml         # Quarto project configuration
├── seed-density-ms.qmd # Main manuscript and analyses
└── seed-density-si.qmd # Supplementary information
```

## Reproducibility

The manuscript and supplementary information are written in Quarto, with analyses conducted in R. The analysis-ready data and associated metadata are in `data/`.

The main manuscript can be rendered from the project root with:

```bash
quarto render seed-density-ms.qmd
```

and the supplementary information with:

```bash
quarto render seed-density-si.qmd
```

Rendered files are written to `output/`, which is not tracked by Git.

## Manuscript history

Git tracks changes to the manuscript, analyses, and data. `docs/drafts/` contains selected earlier and coauthor-reviewed manuscript versions.

At each formal submission, the submitted PDF and DOCX files will be archived in `submissions/` and the corresponding repository state tagged in Git. This preserves the exact data, code, and manuscript source associated with each submitted version.
