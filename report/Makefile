.PHONY: rapport.pdf rapport.gls rapport.bbl all clean

all: rapport.pdf

rapport.pdf: rapport.tex
	latexmk -f -quiet -pdf -pdflatex="pdflatex" -use-make rapport.tex

rapport.gls:
	makeglossaries rapport
	
rapport.bbl:
	bibtex rapport

clean:
	latexmk -quiet -CA
	rm -f rapport.bbl
	rm -f rapport.glg
	rm -f rapport.glo
	rm -f rapport.gls
	rm -f rapport.ist
	rm -f rapport.lol
	rm -f rapport.tdo

