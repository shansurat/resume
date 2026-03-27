# Resume — Kristian Mark "Shan" Surat

[View Resume (PDF)](resume.pdf)

My personal resume, built with LaTeX using the [moderncv](https://ctan.org/pkg/moderncv) package.

## Requirements

- A LaTeX distribution (e.g. [TeX Live](https://www.tug.org/texlive/) or [MiKTeX](https://miktex.org/))
- `moderncv` package (included in most full TeX Live installations)

## Build

> [!IMPORTANT]
> Use `pdflatex`, **not** `pdftex`. This is a LaTeX document and plain TeX will not work.

```bash
pdflatex resume.tex
```

The output will be `resume.pdf` in the same directory.
