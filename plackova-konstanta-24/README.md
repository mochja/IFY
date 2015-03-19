# How to build final PDF
```
$ gnuplot ify24.gnu
$ pdflatex ify24.tex
$ pdflatex -shell-escape -halt-on-error ify24-main.tex
```

`latex ify24.tex && dvips -E -o ify24.eps ify24.dvi && eps2pdf ify24.eps` in case of fire.
