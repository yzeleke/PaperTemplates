all: dissertation

dissertation:
	pdflatex dissertation
	bibtex dissertation
	pdflatex dissertation
	pdflatex dissertation

dependencies: dissertation
	pdflatex -recorder dissertation

.PHONY: clean
clean:
	rm -f dissertation.pdf dissertation.ps dissertation.fls *.aux *.log *.bbl *.blg *.lof *.lot *.toc *.out *.fdb_latexmk
