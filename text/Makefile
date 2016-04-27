FILE=stepan-bambula-dp-2016

all: pdf

pdf:
	pdflatex $(FILE)

clean:
	rm -f *~ *.aux *.log *.out *.toc

distclean:
	make clean
	rm -f $(FILE).pdf
