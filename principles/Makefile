.PHONY: all
all: principles.pdf

SRC=			preamble.tex abstract.tex contents.tex principles.bib

principles.pdf: principles.tex ${SRC}

.PHONY: clean
clean:
	${RM} principles.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
