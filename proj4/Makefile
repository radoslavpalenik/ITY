build:
	latex proj4.tex
	bibtex proj4.aux
	latex proj4.tex
	latex proj4.tex
	dvips -sPAPERSIZE=a4 proj4.dvi
	ps2pdf proj4.ps
clean:
	rm -f proj4.{pdf,ps,out,dvi,log,aux,bbl,blg}
zip:
	zip xpalen05-fit.zip proj4.tex czechiso.bst proj4.bib Makefile
