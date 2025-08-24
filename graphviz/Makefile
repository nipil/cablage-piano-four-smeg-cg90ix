.PHONY: all

DEF = terre.dot four.dot plaques.dot
SVG = $(DEF:.dot=.svg)

all : $(SVG)

%.svg : %.dot
	dot -T svg -o ../images/$@ $<
