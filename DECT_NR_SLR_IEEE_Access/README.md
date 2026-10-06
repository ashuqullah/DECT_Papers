# DECT-2020 NR Survey — Computer Networks

## Main document
Compile `main.tex`.

## Layout
The project starts directly in the Elsevier five-page, two-column journal layout:

```latex
\documentclass[5p,twocolumn]{elsarticle}
```

## Required files
- `main.tex`
- `acronyms.tex`
- `references.bib`
- `sections/*.tex`
- figures placed in `figures/`

## Local compilation
```bash
latexmk -pdf main.tex
```

If glossary files are later printed in the manuscript, use:
```bash
makeglossaries main
latexmk -pdf main.tex
```

## Notes
- The current abstract is a placeholder.
- `references.bib` is a placeholder and should be replaced with the complete survey bibliography.
- The author order and email addresses should be confirmed before submission.
