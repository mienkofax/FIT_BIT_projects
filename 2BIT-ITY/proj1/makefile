#
#Projekt:	ITY 1.projekt 
#Autor:		Peter Tisovcik - xtisov00@stud.fit.vutbr.cz
#Datum:		24.2.2015
#

NAME=proj1

all:
	latex $(NAME) .tex
	latex $(NAME) .tex   
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps
clean:
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log

cleanall:	
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).pdf $(NAME).out

