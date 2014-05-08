paper.pdf: paper.tex preamble.tex what.tex when.tex where.tex why.tex how.tex
	pdflatex $<
	bibtex $(basename $<)
	pdflatex $<
	pdflatex $<

clean:
	rm quantum.pdf quantum.aux