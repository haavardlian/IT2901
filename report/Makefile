PHONY: rapport all clean

all: rapport

rapport: rapport.tex
	latexmk -pdf -pdflatex="pdflatex -interaction=batchmode -interactive=nonstopmode" -use-make rapport.tex

clean:
	latexmk -CA

