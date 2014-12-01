Reports
=======

This repository contains the source code for our project reports.
They are written in latex and should be able to be compiled by most standard distributions.

To compile in Texmaker set Quick Build to:
```
pdflatex -synctex=1 -interaction=nonstopmode %.tex|bibtex %.aux|bibtex %.aux|makeglossaries %|pdflatex -synctex=1 -interaction=nonstopmode %.tex|pdflatex -synctex=1 -interaction=nonstopmode %.tex|evince %.pdf
```
