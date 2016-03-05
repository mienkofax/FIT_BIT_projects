#
#Projekt:	ITY 3.projekt 
#Autor:		Peter Tisovcik - xtisov00@stud.fit.vutbr.cz
#Datum:		31.3.2015
#

NAME=proj3

all:
	latex $(NAME) .tex
	latex $(NAME) .tex   
	dvips -sPAPERSIZE=a4 $(NAME).dvi
	ps2pdf -sPAPERSIZE=a4 $(NAME).ps
clean:
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log

cleanall:	
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).pdf $(NAME).out

