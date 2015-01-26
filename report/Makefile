
report.pdf: report.tex
	latexmk -pdf report.tex

pvc: report.tex
	latexmk -pvc -pdf report.tex

wordcount:
	texcount -inc report.tex -1

clean:
	latexmk -CA
