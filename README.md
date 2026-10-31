# Post-Infection Analysis of RAM Artifacts and System Logs for Detection Engineering

[![View PDF](https://img.shields.io/badge/View-PDF-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://alehshehda.github.io/DF-project/DF-project.pdf)
[![Download PDF](https://img.shields.io/badge/Download-PDF-success?style=for-the-badge&logo=github&logoColor=white)](https://github.com/alehshehda/DF-project/releases/download/latest/DF-project.pdf)

Project documentation for the **Digital Forensics** course (*Informatyka śledcza*) at Wrocław University of Science and Technology, Faculty of Information and Communication Technology (Cybersecurity).

## Authors

- Aleh Shehda (272277)
- Aliaksei Lapachuk (276711)

**Supervisor:** dr inż. Robert Czechowski

## Repository Structure

```text
main.tex                              main LaTeX document file
.github/
  workflows/
    compile.yml                       automated PDF build and release workflow
config/
  metadata.tex                        document metadata and optional section toggles
  theme-pwr.tex                       WUST visual theme and colors
preamble/                             packages, page styles, macros, and table settings
frontmatter/
  titlepage.tex                       title page layout
  abbreviations.tex                   list of abbreviations and acronyms
chapters/
  1_wprowadzenie.tex                  Introduction, research problem, scope, and methodology
bib/
  references.bib                      BibTeX bibliography database
  plabbrv-fixed.bst                   Polish bibliography style
images/                               figures and diagrams
logos/                                university logos
```

## Build

The document is automatically compiled to `DF-project.pdf` and published to GitHub Releases and GitHub Pages via the GitHub Actions CI/CD workflow (`.github/workflows/compile.yml`) on every push to `main`.

