# worksheets

to generate html:

`xsltproc -xinclude /path/to/mathbook/xsl/mathbook-html.xsl /path/to/filename.xml`

That puts the html files in the pwd

to generate LaTeX:

`xsltproc /path/to/mathbook/xsl/mathbook-latex.xsl /path/to/filename.xml > filename.tex`

That puts the LaTeX files in the pwd

