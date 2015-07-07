all: arbiter.jpg fifo.jpg crossbar.jpg

%.pdf : %.tex
	pdflatex $<

%.jpg : %.pdf
	convert -density 1000 $< $@

clean:
	rm -rf *.aux *.log *.pdf

cleanAll:
	rm -rf *.aux *.log *.pdf *.jpg
