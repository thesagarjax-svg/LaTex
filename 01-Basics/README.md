# 01 – Basics of LaTeX

Welcome to your first LaTeX lesson! This section is for complete beginners. You do not need any previous experience.

Follow the topics **in the order shown below**. Each step builds on the previous one.

## Learning sequence

| Step | Topic | What you will learn | Example file |
|---|---|---|---|
| 1 | Introduction to LaTeX | What LaTeX is and how to create your first document | [introduction.tex](introduction.tex) |
| 2 | Text formatting | Bold, italic, underlined and monospaced text | [text_formatting.tex](text_formatting.tex) |
| 3 | Headings and sections | Organising a document with sections and subsections | [headings_and_sections.tex](headings_and_sections.tex) |
| 4 | Lists | Creating bullet-point and numbered lists | [lists.tex](lists.tex) |

After completing the four steps, open [compiled_output.pdf](compiled_output.pdf) to review the rendered examples.

## Step 1 — Introduction to LaTeX

LaTeX (pronounced "LAY-tek" or "LAH-tek") is a document preparation system. It helps you create neatly formatted documents such as reports, assignments, articles and books.

Instead of formatting every part of a document by hand, you write instructions called **commands**. LaTeX uses those instructions to produce the finished document, usually as a PDF.

### How does LaTeX work?

There are three basic steps:

1. **Write:** Create a text file ending in `.tex`. This file contains your LaTeX instructions.
2. **Compile:** Ask a LaTeX program to process the file. This is called compiling.
3. **View:** Open the resulting PDF to see the formatted document.

The `.tex` file is the source file. The PDF is the finished output.

### Understand the structure of a LaTeX document

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

**Practice:** Change the title and author in `introduction.tex`, then compile the file.

## Step 2 — Text formatting

You can change how text looks using formatting commands. Open [text_formatting.tex](text_formatting.tex) and try these commands:

| Appearance | LaTeX command |
|---|---|
| **Bold text** | `\\textbf{Bold text}` |
| *Italic text* | `\\textit{Italic text}` |
| Underlined text | `\\underline{Underlined text}` |
| Monospaced text | `\\texttt{Monospaced text}` |

Monospaced text uses characters that take up the same amount of horizontal space. It is often useful for showing commands or code.

**Practice:** Add a new sentence using each formatting command.

## Step 3 — Headings, sections and subsections

Headings organise a document and make it easier to read. Open [headings_and_sections.tex](headings_and_sections.tex).

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

**Practice:** Add another section and a subsection to the example file.

## Step 4 — Lists

LaTeX can create two common types of lists. Open [lists.tex](lists.tex).

### Unordered list (bullet points)

Use the `itemize` environment when the order of the items does not matter.

```latex
\\begin{itemize}
    \\item Apples
    \\item Bananas
    \\item Oranges
\\end{itemize}
```

### Ordered list (numbered items)

Use the `enumerate` environment when the items should appear in order.

```latex
\\begin{enumerate}
    \\item Open your editor.
    \\item Write your LaTeX code.
    \\item Compile the document.
\\end{enumerate}
```

An **environment** is a section of LaTeX code that starts with a `\\begin{...}` command and ends with a matching `\\end{...}` command.

**Practice:** Add two more items to each list.

## Where can I practise?

You can use [Overleaf](https://www.overleaf.com/), an online LaTeX editor. You can write and compile LaTeX in your browser.

1. Open Overleaf and create a free account.
2. Choose **New Project → Blank Project**.
3. Open the main `.tex` file.
4. Type or paste a lesson example.
5. Click **Recompile** to view the PDF output.

## Final practice checklist

- [ ] Complete Step 1 and compile your first document.
- [ ] Try all four text formatting commands.
- [ ] Create sections and subsections.
- [ ] Create both unordered and ordered lists.
- [ ] Open [compiled_output.pdf](compiled_output.pdf) and compare the examples.

**Beginner note:** Take your time and try changing one command at a time. You do not need to learn everything at once. This first lesson focuses on document basics and does not cover mathematics or equations.
