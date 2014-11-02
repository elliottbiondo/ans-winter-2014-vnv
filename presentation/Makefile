name=presentation
all: tex
tex:
	pdflatex ${name}.tex
	bibtex ${name}
	pdflatex ${name}.tex
	pdflatex ${name}.tex
clean:
	rm -f ${name}.pdf *.toc *.aux *.out *.log *.bbl *.blg *.log *.bak *.vrb *.nav *.snm *~ 

