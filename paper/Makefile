all: pdf clean
	open paper.pdf

pdf: paper.tex
	latexmk -f -pdf -quiet paper.tex
	
clean:
	 rm *.aux *.bbl *.blg *.fdb_latexmk *.fls *.log *.out