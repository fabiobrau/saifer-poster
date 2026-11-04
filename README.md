# A0 Poster Template

A0 portrait poster (`a0poster` class) with a coloured header, logo strip and rounded section boxes.

## Overleaf
1. New Project → Upload Project → select `poster-template.zip`.
2. Compiler: pdfLaTeX (default). Main document: `main.tex`.

## Files
- `main.tex` — content: title, authors, logos, boxes.
- `posterstyle.tex` — layout, colours, `posterbox` environment, header, code style.
- `bibliography.bib` — references.
- `pic/logos/` — institutional and funding logos.

## Usage
- Section box: `\begin{posterbox}[Title] ... \end{posterbox}`
- Two columns: wrap boxes in `\begin{multicols}{2} ... \end{multicols}`
- Accent colour: `\definecolor{postercolor}{HTML}{347b97}` in `main.tex`
- Put your figures in `pic/` and replace `example-image-a/b`.
- Remove `\nocite{*}` to list only cited references.
