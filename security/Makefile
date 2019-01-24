.PHONY: all
all: security.pdf

SRC=			preamble.tex abstract.tex contents.tex security.bib

security.pdf: security.tex ${SRC}

.PHONY: clean
clean:
	${RM} security.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
