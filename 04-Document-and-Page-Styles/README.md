# Module 04: Document Design and Page Formatting

This module introduces the tools and techniques used to organize and customize the appearance of LaTeX documents. You will learn how to build a well-structured document, adjust page layouts, format headings, control text positioning, and manage references with BibTeX.

## 📁 Files Included

| File | Description |
|---|---|
| `document-structure.tex` | Examples of document classes, title pages, abstracts, and section organization |
| `document-structure.pdf` | Compiled output demonstrating document structure |
| `page-styles.tex` | Examples of margins, page numbering, headers, footers, spacing, and text positioning |
| `page-styles.pdf` | PDF output showing different page formatting techniques |
| `refs.bib` | Sample bibliography database containing reference entries |

## 📚 Topics Covered

### 1. Building a LaTeX Document

- Understanding the purpose of document classes such as `article`, `report`, and `book`
- Selecting font sizes and paper dimensions
- Adding document titles, author details, and dates
- Generating a title section with `\maketitle`
- Creating an abstract
- Arranging content with sections and subsections

### 2. Page Layout and Formatting

- Applying page styles with `\pagestyle`
- Using built-in styles: `plain`, `empty`, and `headings`
- Changing page dimensions and margins with `geometry`
- Designing custom headers and footers using `fancyhdr`
- Adjusting paragraph indentation and spacing
- Adding horizontal and vertical gaps
- Controlling page flow with `\newpage` and `\pagebreak`

### 3. Personalizing Document Appearance

- Modifying section heading styles
- Applying colors to document elements with `xcolor`
- Adjusting list layouts with `enumitem`
- Creating a consistent visual format throughout a document

### 4. Text Boxes and Position Control

- Keeping text together using `\mbox`
- Preventing page breaks with the `samepage` environment
- Placing text inside fixed-width blocks using `\parbox`
- Adjusting the vertical position of content with `\raisebox`
- Managing manual line breaks

### 5. Managing References with BibTeX

- Preparing a separate `.bib` bibliography file
- Understanding common BibTeX entry types
- Citing sources with `\cite`
- Selecting a bibliography format with `\bibliographystyle`
- Displaying references using `\bibliography`

## 🧰 LaTeX Packages Used

The examples in this module introduce the following packages:

- `geometry` — Configure page dimensions and margins.
- `fancyhdr` — Customize running headers and footers.
- `xcolor` — Add colors to text and document elements.
- `sectsty` — Change the appearance of section headings.
- `enumitem` — Customize lists and their spacing.
