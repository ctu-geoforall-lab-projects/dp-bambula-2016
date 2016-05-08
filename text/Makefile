# LaTeX Makefile
FILE=stepan-bambula-dp-2016
DIAGRAM=diagram

all: pdf

pdf:
	pdflatex $(DIAGRAM)
	pdflatex $(FILE)
	bibtex $(FILE)
	pdflatex $(FILE)
	pdflatex $(FILE)

clean:
	rm -f *~ *.aux *.log *.out *.toc *.bbl *.blg *.lof *.lol *.lot *.backup, *.sta

distclean:
	make clean
	rm -f $(FILE).pdf
	rm -f $(DIAGRAM).pdf
