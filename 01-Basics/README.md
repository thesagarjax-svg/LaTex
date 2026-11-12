# 01 – Basics of LaTeX

Welcome to your first LaTeX lesson! This section is for complete beginners. You do not need any previous experience.

## 1. What is LaTeX?

LaTeX (pronounced "LAY-tek" or "LAH-tek") is a document preparation system. It helps you create neatly formatted documents such as reports, assignments, articles and books.

Instead of formatting every part of a document by hand, you write instructions called **commands**. LaTeX uses those instructions to produce the finished document, usually as a PDF.

## 2. How does LaTeX work?

There are three basic steps:

1. **Write:** Create a text file ending in `.tex`. This file contains your LaTeX instructions.
2. **Compile:** Ask a LaTeX program to process the file. This is called compiling.
3. **View:** Open the resulting PDF to see the formatted document.

The `.tex` file is the source file. The PDF is the finished output.

## 3. Understand the structure of a LaTeX document

A basic LaTeX document has three main parts:

- **Document class:** Tells LaTeX what kind of document you are creating.
- **Preamble:** The area before the document begins. It contains setup instructions, such as the title and author.
- **Document body:** The area between `\\begin{document}` and `\\end{document}`. This is where the content that appears in your document goes.

Here is a small example:

```latex
\\documentclass{article}

\\title{My First Document}
\\author{Your Name}
\\date{\\today}

\\begin{document}

\\maketitle

Hello! This is my first LaTeX document.

\\end{document}
```

### What do these commands mean?

- `\\documentclass{article}` chooses the article document type.
- `\\title{...}` sets the document title.
- `\\author{...}` sets the author's name.
- `\\date{\\today}` inserts the current date.
- `\\begin{document}` marks the start of the document body.
- `\\maketitle` displays the title, author and date.
- `\\end{document}` marks the end of the document.

A **command** is an instruction that usually begins with a backslash (\\). Curly braces `{ }` often hold the information that a command needs.

## 4. Headings, sections and subsections

Headings organise a document and make it easier to read.

- `\\section{...}` creates a main section.
- `\\subsection{...}` creates a smaller section inside a main section.
- `\\subsubsection{...}` creates an even smaller heading.

Example:

```latex
\\section{Introduction}
This is the introduction.

\\subsection{Background}
This is background information.

\\section{Conclusion}
This is the conclusion.
```

Think of a section as a main chapter heading and a subsection as a heading within it.

## 5. Lists

LaTeX can create two common types of lists.

### Unordered list (bullet points)

Use the `itemize` environment when the order of the items does not matter.

```latex
\\begin{itemize}
    \\item Apples
    \\item Bananas
    \\item Oranges
\\end{itemize}
```

The result is a bullet-point list.

### Ordered list (numbered items)

Use the `enumerate` environment when the items should appear in order.

```latex
\\begin{enumerate}
    \\item Open your editor.
    \\item Write your LaTeX code.
    \\item Compile the document.
\\end{enumerate}
```

The result is a numbered list.

An **environment** is a section of LaTeX code that starts with a `\\begin{...}` command and ends with a matching `\\end{...}` command.

## 6. Text formatting

You can change how text looks using formatting commands.

| Appearance | LaTeX command |
|---|---|
| **Bold text** | `\\textbf{Bold text}` |
| *Italic text* | `\\textit{Italic text}` |
| Underlined text | `\\underline{Underlined text}` |
| Monospaced text | `\\texttt{Monospaced text}` |

Monospaced text uses characters that take up the same amount of horizontal space. It is often useful for showing commands or code.

## 7. Where can I practise?

You can use [Overleaf](https://www.overleaf.com/), an online LaTeX editor. You can write and compile LaTeX in your browser.

1. Open Overleaf and create a free account.
2. Choose **New Project → Blank Project**.
3. Open the main `.tex` file.
4. Type or paste a lesson example.
5. Click **Recompile** to view the PDF output.

## 8. Lessons in this folder

- `introduction.tex` — Your first LaTeX document.
- `text_formatting.tex` — Bold, italic, underline and monospaced text.
- `headings_and_sections.tex` — Titles, sections and subsections.
- `lists.tex` — Bullet-point and numbered lists.
- `compiled_output.pdf` — Rendered document output, without LaTeX source code.

The `.tex` files are the editable source examples. The PDF is for viewing the compiled result.

## 9. Practice exercises

Try these small activities:

1. Change the title and author in `introduction.tex`.
2. Add one more sentence to the introduction.
3. Add a new subsection in `headings_and_sections.tex`.
4. Add two more items to each list in `lists.tex`.
5. Format a sentence in bold and another in italics.
6. Compile your files and look at the PDF output.

**Beginner note:** Take your time and try changing one command at a time. You do not need to learn everything at once. This first lesson focuses on document basics and does not cover mathematics or equations.
