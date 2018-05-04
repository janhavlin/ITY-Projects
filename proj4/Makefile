filename=proj4

all:
	latex ${filename}.tex
	bibtex ${filename}.aux
	latex ${filename}.tex
	latex ${filename}.tex
	dvips -t a4 ${filename}.dvi
	ps2pdf -sPAPERSIZE=a4 ${filename}.ps

zip:
	zip xhavli47-fit ${filename}.tex Makefile citace.bib czplain.bst

vlna:
	vlna -v KkSsVvZzOoUuAaIi ${filename}.tex
	
clean:
	rm ${filename}.{aux,dvi,log,ps,blg,bbl}