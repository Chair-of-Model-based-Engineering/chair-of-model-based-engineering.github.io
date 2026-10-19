---
title: "Vorlage für die schriftliche Ausarbeitung des Seminars"
---

# Vorlage für die schriftliche Ausarbeitung des Seminars

Für die schriftliche Ausarbeitung muss das [ACM Style LaTeX Template](https://www.acm.org/publications/proceedings-template) verwendet werden. Sie können selbst entscheiden, ob Sie das einspaltige (*acmlarge*) oder zweispaltige (*acmtog*) LaTeX Template verwenden. Bitte beachten Sie, dass die geforderte Seitenzahl sich dabei bei gleichem Inhalt unterscheidet.

Um LaTeX-Dokumente zu bearbeiten und zu setzen, empfehlen wir [MiKTeX](https://miktex.org/) (darin ist der Editor *TeXworks* enthalten).

Zur Verwendung kopieren Sie zunächst eines der Verwendungsbeispiele `sample-acmlarge.tex` oder `sample-acmtog.tex` aus dem `samples`-Ordner des ACM Style LaTeX Templates in einem neuen Ordner. Kopieren Sie außerdem die Datei `sample-base.bib`, welche das Literaturverzeichnis (Bibliographie) enthält. Benennen Sie dann die kopierten Dateien um, z.B. gemäß des Titels Ihrer Ausarbeitung. Der Name der `bib`-Datei muss auch innerhalb der `tex`-Datei angepasst werden (suchen Sie dazu nach dem Text `sample-base`).

## ACM-Copyright

Setzen Sie in der `\documentclass` in Ihrem LaTeX Dokument zusätzlich die Option `nonacm`, um die in diesem Seminar unnötigen Informationen wie DOI-Links und ACM Copyright zu entfernen. Verwenden Sie *eine* der folgenden Zeilen:

`\documentclass[acmlarge,nonacm]{acmart} % Einspaltig`

`\documentclass[acmtog,nonacm]{acmart} % Zweispaltig`

## Spracheinstellung

Abhängig von der Sprache, in der Sie die Ausarbeitung schreiben, muss die `babel`-Package eingestellt werden, damit sprachabhängige Funktionen wie die automatische Silbentrennung korrekt funktionieren. Plazieren Sie *eine* der folgenden Zeilen hinter `\documentclass[...]{...}`:

`\usepackage[ngerman]{babel} % Deutsch (neue Rechtschreibung)`

`\usepackage[english]{babel} % Englisch`

## Autorangaben

Folgende Angaben über Sie sollten angegeben werden: vollständiger Name, Universität und studentische E-Mail-Adresse. Auf alle anderen Autorangaben (Anschrift etc.) kann verzichtet werden.

## Literaturverzeichnis

Literaturverzeichnis/Quellenangaben sollten den *numerischen ACM Style* verwenden. Ersetzen Sie dazu die Zeile `\citestyle{...}` durch folgende Zeile:

`\citestyle{acmnumeric}`

## Code-Listings

Um Programm-/Pseudocode zu zeigen, verwenden Sie die [Listings](https://www.overleaf.com/learn/latex/Code_listing#Using_listings_to_highlight_code)-Package. Achten Sie auf die korrekte Angabe der Programmiersprache, damit die Syntax korrekt hervorgehoben wird (wenn die verwendete Programmiersprache unterstützt wird).

## Mathematische Formeln

Verwenden Sie für jegliche Formeln den [Math-Mode](https://www.overleaf.com/learn/latex/Display_style_in_math_mode).

---

[⇐ Zurück zum Seminar Modellbasierte Entwicklung](/de/teaching/summer-semester/modellbasierte-entwicklung/)
