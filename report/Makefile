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

