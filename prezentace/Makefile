# LaTeX Makefile
FILE=dp-prezentace

all: pdf

pdf:
	pdflatex $(FILE)

clean:
	rm -f *~ *.aux *.log *.out *.toc *.bbl *.blg *.nav *.snm *.backup *.vrb

distclean:
	make clean
	rm -f $(FILE).pdf
