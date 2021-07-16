LaTeX-template
===
[Latest PDF Version](releases/latest/download/latex-template.pdf)
[![Build LaTeX](actions/workflows/build.yml/badge.svg)](actions/workflows/build.yml)

Template for a reproducable LaTeX workflow using texlive, latexmk, make and automated builds.

This can be either used for normal documents or for beamer slides.
Please look into the comments of `main.tex` to see how to setup beamer. 

# Building
To produce the output to `build/main.pdf` simply run
```sh
make
```

To use continuous building (i.e. while working on the document) use 
```sh
make work
```

# Dependencies 
You need 
- texlive 
- make
