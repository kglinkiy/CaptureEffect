all: ax.pdf

ax.pdf: ax.tex biblio.bib
	pdflatex $<
	pdflatex $<
	bibtex ax
	bibtex ax
	pdflatex $<
	pdflatex $<

clean:
	rm *.aux *.log *.bbl *.blg main.pdf *.synctex.gz *.out
