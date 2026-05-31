# RiSE Lecture Notes (LaTeX)

Typeset lecture notes for the **Robotics & State Estimation (RiSE)** tutorials.
Built from the RiSE lecture-note template (adapted from the UDel RPNG tech-report template).

One `\section` per lecture; add lectures by creating `sections_main/NN_lectureNN.tex` with a
top-level `\section{Lecture N: ...}` and `\input{}`-ing it from `rise_notes.tex`.

## Build

```bash
latexmk -pdf rise_notes.tex
```

The rendered `rise_notes.pdf` is tracked in this folder so the notes are viewable on GitHub.

## Layout

```
rise_notes.tex                  # preamble + document structure + custom math commands
rise_notes.pdf                  # rendered output (tracked)
sections_main/00_titlepage.tex  # course cover page + table of contents
sections_main/01_lecture01.tex  # Lecture 1 content
libraries/library.bib           # shared bibliography
libraries/extras.bib            # per-note extra references
figures/                        # images (RiSE_v1.png logo, placeholder)
```
