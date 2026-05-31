# RiSE Lecture-Note Template

LaTeX template for **Robotics & State Estimation (RiSE)** lecture notes.
Adapted from the UDel RPNG tech-report template.

## Usage

1. Copy this folder into a lecture directory, e.g. `lectures/02-rotation-lie/`.
2. Edit `sections_main/00_titlepage.tex` — set the lecture number, title, and instructor.
3. Write content as new files in `sections_main/` and `\input{}` them from `main.tex`.
4. Delete `sections_main/02_examples.tex` (it's a LaTeX cheat-sheet) once you start real content.

## Build

```bash
latexmk -pdf main.tex      # or: pdflatex; bibtex main; pdflatex; pdflatex
```

## Layout

```
main.tex                       # preamble + document structure + custom math commands
sections_main/00_titlepage.tex # cover page + table of contents (EDIT per lecture)
sections_main/01_introduction.tex
sections_main/02_examples.tex  # LaTeX patterns reference — delete when writing notes
sections_appendix/             # optional appendices
libraries/library.bib          # shared bibliography
libraries/extras.bib           # per-note extra references
figures/                       # images (drop a figures/rise_logo.png to replace the logo)
```
