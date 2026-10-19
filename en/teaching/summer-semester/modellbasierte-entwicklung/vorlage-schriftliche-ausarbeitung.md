---
title: "Template for the written elaboration of the seminar"
---

# Template for the written elaboration of the seminar

The [ACM Style LaTeX template](https://www.acm.org/publications/proceedings-template) must be used for the written elaboration. You can decide for yourself whether to use the single-column (*acmlarge*) or double-column (*acmtog*) LaTeX template. Please note that the required number of pages differs for the same content.

To edit and typeset LaTeX documents, we recommend [MiKTeX](https://miktex.org/) (which includes the editor *TeXworks*).

To use the template, first copy one of the usage samples `sample-acmlarge.tex` or `sample-acmtog.tex` from the samples folder of the ACM Style LaTeX template into a new folder. Also copy the file `sample-base.bib`, which contains the bibliography. Then rename the copied files, e.g. according to the title of your paper. The name of the bib file must also be adapted within the tex file (search for the text sample-base).

## ACM copyright

In the `\documentclass` in your LaTeX document, also set the `nonacm` option to remove the information that is unnecessary in this seminar, such as DOI links and ACM copyright. Use *one* of the following lines:

`\documentclass[acmlarge,nonacm]{acmart} % One column`

`\documentclass[acmtog,nonacm]{acmart} % Two columns`

## Language setting

Depending on the language in which you write the elaboration, the `babel` package must be configured so that language-dependent functions such as automatic hyphenation work correctly. Place *one* of the following lines after `\documentclass[...]{...}`:

`\usepackage[ngerman]{babel} % German (new orthography)`

`\usepackage[english]{babel} % English`

## Author details

The following information about you should be provided: full name, university and student email address. All other author details (address etc.) can be omitted.

## Bibliography

Bibliography/Citations should use the numeric ACM style. To do this, replace the line `\citestyle{...}` with the following line:

`\citestyle{acmnumeric}`

## Code listings

To show programm/pseudo code, use the [Listings](https://www.overleaf.com/learn/latex/Code_listing#Using_listings_to_highlight_code) package. Be sure to specify the programming language correctly so that the syntax is highlighted properly (if the programming language used is supported).

## Mathematical formulas

Use the [Math-Mode](https://www.overleaf.com/learn/latex/Display_style_in_math_mode) for any formulas.

---

[⇐ Back to the Seminar Model-based Engineering](/en/teaching/summer-semester/modellbasierte-entwicklung/)
