all:
	pandoc -o content.tex content.md
	pdflatex wrapper
	pdflatex wrapper
	bibtex wrapper
	pdflatex wrapper
	pdflatex wrapper

clean:
	rm -f *.aux *.bbl *.blg *.log *.out
