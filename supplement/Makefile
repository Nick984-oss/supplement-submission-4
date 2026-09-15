SHELL := /bin/sh
TEX := Supplementary_Material.tex

.PHONY: pdf clean

pdf:
	latexmk -lualatex -interaction=nonstopmode -halt-on-error $(TEX)

clean:
	latexmk -C $(TEX)
