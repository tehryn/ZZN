all: zzn.pdf

zzn.pdf: zzn.tex
	pdflatex zzn.tex
#	bibtex zzn.aux
	pdflatex zzn.tex
	pdflatex zzn.tex

clean:
	rm -f zzn.bbl zzn.log zzn.aux zzn.blg zzn.pdf zzn.toc
