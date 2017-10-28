DATA_DIR = data

english:
	cd data/ ; for f in coverletter_eng.tex; do xelatex $$f; done
	cd data/ ; for f in cvSebastian_en.tex; do xelatex $$f; done 
	mkdir -p output/ ; cd data/ ; cp cvSebastian_en.pdf ../output ; cp coverletter_eng.pdf ../output ; done

clean: 
	rm -rf $(DATA_DIR)/*.aux
	rm -rf $(DATA_DIR)/*.log
	rm -rf $(DATA_DIR)/*.out
	rm -rf $(DATA_DIR)/*.pdf
