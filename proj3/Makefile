filename=proj3

all:
	latex ${filename}.tex
	latex ${filename}.tex
	dvips -t a4 ${filename}.dvi
	ps2pdf ${filename}.ps

zip:
	zip xhavli47-fit ${filename}.tex Makefile
	
clean:
	rm ${filename}.{aux,dvi,log,ps}