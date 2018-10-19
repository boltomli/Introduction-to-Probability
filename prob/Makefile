LATEX = lualatex

all:	prob.tex
	$(LATEX) prob
	makeindex prob.idx
	$(LATEX) prob
	evince prob.pdf

clean:
	rm -f *~ *.aux *.log *.dvi *.idx *.ilg *.ind *.toc *.gz

dist:
	tar -cvvzf prob.tar.gz *.tex figures zzz Makefile
