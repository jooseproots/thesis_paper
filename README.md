# Thesis Project

This repository contains my thesis project written in LaTeX.

## Project Structure

- `NATO_thesis.tex` - Main LaTeX source file
- `chapters/` - Directory containing thesis chapters
- `images/` - Directory containing images and figures used in the thesis
  - Including UvA logo (`uva_logo.jpg`)

## Building the Document

To build the PDF from the LaTeX source, you'll need a LaTeX distribution installed (such as TeX Live or MiKTeX). The project uses `latexmk` for building, `biblatex`/`biber` for references.

You can build the document using:

```bash
latexmk -pdf NATO_thesis.tex
```

This will generate `NATO_thesis.pdf` along with various auxiliary files.

## Generated Files

- `NATO_thesis.pdf` - The final compiled document
- `*.aux` - Auxiliary files used by LaTeX
- `*.fdb_latexmk` - LaTeX build database
- `*.fls` - File list generated during compilation
- `*.log` - Log file containing compilation information
- `*.synctex.gz` - SyncTeX file for source-PDF synchronization