TARGET = lvee2014_lapa_ansible.pdf
NAME = lvee2014_lapa_ansible
%.pdf: %.tex
	pdflatex -interaction=nonstopmode $<
	pdflatex $<

tex: $(TARGET)

.PHONY : clean
clean:
	rm $(NAME).vrb $(NAME).aux $(NAME).log $(NAME).nav $(NAME).out $(NAME).snm $(NAME).toc

