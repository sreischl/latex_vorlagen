
.PHONY: all clean pdflatex cleanall

all: clean pdflatex

pdflatex:
	pdflatex brief.tex

clean:
	rm -f brief.aux
	rm -f *.log

cleanall: clean
	rm -f brief.pdf
