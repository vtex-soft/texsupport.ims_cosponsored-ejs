# EJS

## DESCRIPTION

LaTeX author support files for IMS co-sponsored journal: 
[Electronic Journal of Statistics (EJS)](https://imstat.org/journals-and-publications/electronic-journal-of-statistics/)

## NOTE ON NEW VERSION (v2) – March 20, 2025

As of 2025-03-20, the class file has been updated:

-   Margins have been reduced.
-   The document class option changed from `ejs` to `ejsv2`.

While `ejs` still works for backward compatibility, it is now considered legacy and may be removed in future versions. 
New documents should use `ejsv2`.

## FILE LIST

-   `ejs-sample.tex` - sample article for EJS (source file)
-   `ejs-sample.pdf` - sample article for EJS (PDF compiled)
-   `figure1.eps`, `figure1.pdf` - sample figures for `ejs-sample.pdf`
-   `LICENSE` - a copy of the LaTeX Project Public License
-   `README.md` - this file itself!
-   `imsart.cls`, `imsart.sty` - LaTeX style files
-   `acmtrans-ims.bst`, `imsart-nameyear.bst`, `imsart-number.bst` - BibTeX style files

## INSTRUCTIONS FOR EJS AUTHORS

-   You only need `imsart.cls`, `imsart.sty`, `ejs-sample.tex`, and `ejs-sample.pdf`
-   Take the time to read `ejs-sample.pdf`
-   Copy `ejs-sample.tex` into `yourname.tex`
-   Edit `yourname.tex` (update metadata and the content of the paper)
-   Use `acmtrans-ims.bst`, `imsart-nameyear.bst`, `imsart-number.bst` BibTeX styles to prepare bibliography file. 
    More information can be found [here](http://www.bibtex.org/Using/) 
    or [here](https://www.latex-tutorial.com/tutorials/bibtex/).
-   Be sure to have `imsart.cls`, `imsart.sty` in the same directory (or any dir scanned for `cls`)
-   Compile `yourname.tex` to generate `yourname.pdf` with a `pdflatex` or `lualatex` program and check the result
-   More detailed instructions for authors are available on Internet: https://imstat.org/journals-and-publications/electronic-journal-of-statistics/

## TROUBLESHOOTING

-   To remove frame from the text box use document class option `noshowframe`, e.g:

        \documentclass[ejsv2,noshowframe]{imsart}

## BUG REPORTS

Please submit bug reports and/or feature requests
at [GitHub page](https://github.com/vtex-soft/texsupport.ims_cosponsored-ejs/issues) or 
[latex-support@vtex.lt](mailto:latex-support@vtex.lt).
