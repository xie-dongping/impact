all: impact.pdf abstract.pdf

impact.pdf: impact.tex impact.bib
	pdflatex impact.tex
	bibtex impact
	pdflatex impact.tex
clean:
	rm *.aux *.bbl *.blg *-blx.bib *.log *.out *.run.xml

abstract.pdf: abstract.tex impact.bib
	pdflatex abstract.tex
	bibtex abstract
	pdflatex abstract.tex
