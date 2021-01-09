TARGETS = further-mathematics.tex
LATEXMK = latexmk
XELATEX = xelatex
all:
	$(XELATEX) $(TARGETS) && $(XELATEX) $(TARGETS)
clean:
	$(LATEXMK) -CA
.PHONY: all clean
