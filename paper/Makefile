.PHONY: all clean
.DEFAULT_GOAL := paper.pdf

mkfile_dir :=$(realpath $(dir $(firstword $(MAKEFILE_LIST))))

all: paper.pdf

# assummes the docker image from https://github.com/biohackrxiv/bhxiv-gen-pdf is available
paper.pdf: paper.md paper.bib
	docker run --rm -it -v $(mkfile_dir):/work -w /work biohackrxiv/gen-pdf:local gen-pdf

clean: 
	rm -f paper.pdf
