filename=proj3

all:
	latex ${filename}.tex
	latex ${filename}.tex
	dvips -t a4 ${filename}.dvi
	ps2pdf -sPAPERSIZE=a4 ${filename}.ps

zip:
	zip xhavli47-fit ${filename}.tex Makefile oniisan.eps oniisan2.eps etiopan.eps algorithm2e.sty
	
clean:
	rm ${filename}.{aux,dvi,log,ps}