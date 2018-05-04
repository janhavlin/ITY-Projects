filename=proj5

all:
	pdflatex ${filename}

vlna:
	vlna -v KkSsVvZzOoUuAaIi ${filename}.tex
	
zip:
	zip xhavli47-fit ${filename}.tex Makefile automat.eps
	
clean:
	rm ${filename}.{aux,dvi,log,ps}