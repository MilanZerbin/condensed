# condensed
Condensed Mathematics: Learners Diary

## how to collaborate

 - [ ] Clone the repo, optionally create your own branch
 - [ ] Define yourself a color command in "ourcolors.sty"
 - [ ] Add your contributions to "condensed.tex", mark with your color

## build 

We use bibtex with biber backed. Thus to build all references correctly use the path
```
pdflatex --shell-escape condensed.tex
biber condensed
pdflatex --shell-escape condensed.tex
pdflatex --shell-escape condensed.tex
```


