# Build Beamer from main.tex using XeLaTeX (for Korean text support)
all: main.pdf

main.pdf: main.tex themes/simplus/beamerthemesimplus.sty bib/references.bib
	latexmk -xelatex -interaction=nonstopmode -synctex=1 main.tex

clean:
	latexmk -C

.PHONY: all clean
