FILE=main

.PHONY: fast clean

# Dica: pode-se usar batchmode ao invés de nonstopmode.

fast:
	pdflatex -interaction=nonstopmode -halt-on-error $(FILE).tex 
	pdflatex -interaction=nonstopmode -halt-on-error $(FILE).tex
	pdflatex -interaction=nonstopmode -halt-on-error $(FILE).tex
	make clean
	
clean:
	rm -rf *.aux *.bbl *.toc *.out *.log *.nls *.nlo *.snm *.nav \
               *.lof *.lot *.blg *.ilg *.synctex.gz
	rm -rf */*.aux */*.bbl */*.toc */*.out */*.log */*.snm */*.nav \
               */*.nls */*.nlo */*.lof */*.lot */*.blg */*.ilg */*.synctex.gz
	rm -rf *~ */*~
