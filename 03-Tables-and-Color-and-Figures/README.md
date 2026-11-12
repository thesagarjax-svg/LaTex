# Tables, Color, and Figures

This chapter introduces the basics of creating tables, adding color, and inserting and referencing figures in LaTeX. It is designed for beginners and includes explanations, code examples, and a complete mini example.

## Topics covered

1. **Creating a basic table** — Use the `tabular` environment, column alignment, cell separators (`&`), and row breaks (`\\`).
2. **Improving tables with booktabs** — Create cleaner tables with `\\toprule`, `\\midrule`, and `\\bottomrule`.
3. **Adding color to text** — Load `xcolor` and use `\\textcolor`.
4. **Highlighting table rows and cells** — Use `\\rowcolor` and `\\cellcolor`.
5. **Including an image** — Use `graphicx`, `\\includegraphics`, the `figure` environment, captions, and labels.
6. **Figure placement and resizing** — Explore placement options such as `[htbp]` and width settings.
7. **Referencing figures and tables** — Use `\\label` and `\\ref` to refer to numbered objects.
8. **Complete mini example** — Combine a colored heading, a table, and a simple TikZ illustration.

## Files

- [LaTeX source](explanation.tex)
- [Compiled PDF](compiled_output.pdf)

## How to compile

Compile the source with pdfLaTeX:

```bash
pdflatex explanation.tex
```

Run the command again if needed to update cross-references.

## Requirements

The chapter uses packages including `xcolor`, `graphicx`, `array`, `booktabs`, `caption`, and `tikz`. These are included in most standard LaTeX distributions, such as TeX Live and MiKTeX.
