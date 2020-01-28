# worksheets

This repository is a work in progress.
It collects my efforts to rewrite the worksheets I have made for use as active learning and inquiry based learning materials.
I originally created them as LaTeX documents, and here they are presented as PreTeXt documents.

From the xml, they can generate html, LaTeX, and other formats.

to generate html:

`xsltproc -xinclude /path/to/mathbook/xsl/mathbook-html.xsl /path/to/filename.xml`

That puts the html files in the pwd

to generate LaTeX:

`xsltproc -xinclude /path/to/mathbook/xsl/mathbook-latex.xsl /path/to/filename.xml > filename.tex`

That puts the LaTeX files in the pwd

The worksheets for MATH 142 Calculus &amp; Analytical Geometry II are live as webpages accessible on my [webpage](https://billkronholm.com/math142/).
