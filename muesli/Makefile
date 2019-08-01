all: vortrag.tex
	pdflatex vortrag.tex
	rm -f *.aux *.log *.toc *.snm *.nav

pdf: all
	evince vortrag.pdf &

