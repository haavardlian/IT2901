.PHONY: rapport.pdf rapport.gls all clean

all: rapport.pdf

rapport.pdf: rapport.tex
	latexmk -f -quiet -pdf -pdflatex="pdflatex -interactive=nonstopmode" -use-make rapport.tex

rapport.gls:
	makeglossaries rapport

clean:
	latexmk -quiet -CA

