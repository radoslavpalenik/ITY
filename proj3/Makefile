build:
	latex proj3 < proj3.tex
	dvips proj3.dvi
	ps2pdf -sPAPERSIZE=a4 proj3.ps
	latex proj3 < proj3.tex
	dvips proj3.dvi
	ps2pdf -sPAPERSIZE=a4 proj3.ps
clean:
	rm -f proj3.{pdf,ps,out,dvi,log,aux}
zip:
	zip xpalen05-fit.zip proj3.tex *.eps *.sty Makefile