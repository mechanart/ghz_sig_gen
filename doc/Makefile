all: 	block_diagram 	gsg_hw_specification

block_diagram:
		latex block_diagram.tex; dvips block_diagram.dvi; ps2pdf block_diagram.ps 

gsg_hw_specification:
		latex gsg_hw_specification.tex
		dvips gsg_hw_specification.dvi
		ps2pdf gsg_hw_specification.ps

clean: 
		rm -f *.dvi *.ps *.pdf *.log *.toc *.aux
