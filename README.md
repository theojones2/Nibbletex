This repository contains two programs written to allow the Nibbleblog blogging engine to work with LaTeX.

1. Nibbletex: A plugin that uses the MathJax library to allow your blog to use LaTeX math expressions (in the nibblebloglatex folder).
2. Nibblegen: A script to convert LaTex text to html usable in Nibbleblog (forked from the latex2wp project and in progress).Changes so far include modifications to the output of LaTeX2WP so it is more compatiable with Nibbleblog. Additionaly, it was modified to act like a filter.The documentation has not yet been updated but to convert a .tex file to HTML use

cat example.tex | python2 nibblegen.py > example.html

Both are free software under the GPL3. 