DATA_DIR = data

all:
	cd data/ ; for f in coverletter_en.tex; do xelatex $$f; done
	cd data/ ; for f in cv_en.tex; do xelatex $$f; done 
	mkdir -p output/ ; cd data/ ; mv cv_en.pdf ../output ; mv coverletter_en.pdf ../output ; done

clean: 
	rm -rf $(DATA_DIR)/*.aux
	rm -rf $(DATA_DIR)/*.log
	rm -rf $(DATA_DIR)/*.out
	rm -rf $(DATA_DIR)/*.pdf
