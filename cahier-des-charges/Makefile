all: pdf

pdf:
	pdflatex -output-directory=output main.tex
	mv -f ./output/main.pdf ./GR4_Cahier_des_charge.pdf

clear:
	rm -f output
