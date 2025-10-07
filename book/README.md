# 📖 Course Book

This directory contains the comprehensive course book and supporting materials for CS25 Large Foundation Models.

## Contents

### Main Book
- `book.tex` - Main book source file
- `book.pdf` - Compiled book (ready to read)
- `chapters/` - Individual book chapters

### Supporting Materials
- `figures/` - All course figures, diagrams, and images
- `references/` - Bibliography and reference materials
  - `references.bib` - BibTeX bibliography file

## Book Structure

The book provides a comprehensive treatment of Large Foundation Models covering:

1. **Mathematical Foundations** - Core mathematical concepts
2. **Algorithmic Implementations** - Practical algorithms and methods
3. **Applications** - Real-world applications and use cases
4. **Advanced Topics** - Cutting-edge research and developments

## Usage

### Reading the Book
- **PDF Version**: Open `book.pdf` for the complete compiled book
- **Source Files**: Use `book.tex` and `chapters/` for customization

### Compilation
To compile the book from source:
```bash
pdflatex book.tex
bibtex book
pdflatex book.tex
pdflatex book.tex
```

## Prerequisites

- LaTeX distribution (TeX Live, MiKTeX, etc.)
- Required LaTeX packages for mathematical typesetting
- BibTeX for bibliography management
