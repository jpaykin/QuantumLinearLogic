quantum.pdf: quantum.tex preamble.tex category.tex
	pdflatex $<
	bibtex $(basename $<)
	pdflatex $<
	pdflatex $<

clean:
	rm quantum.pdf quantum.aux