MAIN = the-zoo
LATEX-CMD = xelatex
BIBTEX-CMD = biber

.PHONY: FORCE

main: ${MAIN}.tex
	latexrun --latex-cmd ${LATEX-CMD} --bibtex-cmd ${BIBTEX-CMD} ${MAIN}.tex


.PHONY: clean

clean:
	latexrun --clean-all
