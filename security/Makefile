.PHONY: all
all: security.pdf

SRC=			preamble.tex abstract.tex contents.tex security.bib

security.pdf: security.tex ${SRC}


.PHONY: all
all: README.md

README.md: video.md reading.md
	${CAT} $^ > $@

reading.md: abstract.tex
	pandoc -s -t markdown_strict \
		-o $@ --bibliography security.bib $^


.PHONY: clean
clean:
	${RM} security.pdf reading.md


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
