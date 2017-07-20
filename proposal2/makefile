# Makefile for Chris's thesis proposal

all :
	pdflatex proposal.tex
	bibtex proposal
	pdflatex proposal.tex
	pdflatex proposal.tex

quick : 
	pdflatex proposal.tex

quick2:
	pdflatex proposal.tex
	pdflatex proposal.tex

clean :
	rm *.aux *.bbl *.blg *.log *.toc *.out
