# LaTeX Makefile
FILE=stepan-bambula-dp-2016

all: pdf

pdf:
	pdflatex $(FILE)
	bibtex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)

clean:
	rm -f *~ *.aux *.log *.out *.toc *.bbl *.blg *.lof *.lot *.backup

distclean:
	make clean
	rm -f $(FILE).pdf
