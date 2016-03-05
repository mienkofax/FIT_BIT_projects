#
#Projekt:	ITY 2.projekt 
#Autor:		Peter Tisovcik - xtisov00@stud.fit.vutbr.cz
#Datum:		11.3.2015
#

NAME=proj2

all:
	latex $(NAME) .tex
	latex $(NAME) .tex   
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps
clean:
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log

cleanall:	
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).pdf $(NAME).out

