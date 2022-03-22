LaTeX-template
===
[Latest PDF Version](https://github.com/The-Ludwig/latex-template/releases/latest/download/latex-template.pdf)
[![Build LaTeX](https://github.com/The-Ludwig/latex-template/actions/workflows/build.yml/badge.svg)](https://github.com/The-Ludwig/latex-template/actions/workflows/build.yml)

Template for a reproducable LaTeX workflow using texlive, latexmk, make and automated builds.

**Remember to replace the paths in this README.md file, so you use your own badges**

This can be either used for normal documents or for beamer slides (see below).

# Building
To produce the output to `build/main.pdf` simply run
```sh
make
```

To use continuous building (i.e. while working on the document) use 
```sh
make work
```

# Beamer
You can also use this template to produce slides with `beamer`.
For that simply rename `main_beamer.tex` to `main.tex`. 
You can delete `header.tex` and the original `main.tex`. 

# Matplotlib
In order to make python's [matplotlib](https://matplotlib.org/) produce plots 
which are compatible with the style of this latex template (fonts, using `siunitx`, etc), 
there is a `matplotlibrc` file and `matplotlib_header.tex`. Simply copy these files 
to where you run python. 

## Note
Your plots will take a longer time to produce with this.

# Dependencies 
You need 
- texlive 
- make

# Credits
As with all of my LaTeX stuff: Since I learned it thanks to the [PeP Toolbox Workshop](https://toolbox.pep-dortmund.org/)
you will proably find a lot of copied code from their workshop. If you want to learn LaTeX and speak German, have a look at their awesome resources! :)
