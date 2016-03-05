#
#Projekt:	ITY 3.projekt 
#Autor:		Peter Tisovcik - xtisov00@stud.fit.vutbr.cz
#Datum:		31.3.2015
#

NAME=proj5

all:
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).nav $(NAME).snm $(NAME).toc

cleanall:	
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).nav $(NAME).snm $(NAME).toc $(NAME).pdf $(NAME).out