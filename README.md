# LaTeX starter
A quick starter with some examples for LaTeX.

## Compile
Compile the document with the following command:
```bash
sh compile.sh
```
This contains the below commands:

1. Compile after changes:
    ```bash
    pdflatex doc.tex
    ```

2. Compile for Table of Contents:
    ```bash
    pdflatex doc.tex
    pdflatex doc.tex
    ```

3. Compile for Bibliography:
    ```bash
    pdflatex doc.tex
    bibtex doc
    pdflatex doc.tex
    pdflatex doc.tex
    ```

## Helpful links
- https://www.overleaf.com/learn

