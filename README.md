Simple LaTeX Tutorial
=====================

I made this tutorial for a friend to help persuade her into using LaTeX for
writing documents. Anyone can use it, but it is aimed at people who have never
used LaTeX before.  

The tutorial is the file latex-tutorial.tex. In other words, the source code is
the documenation.

Compiling on the command line:
------------------------------

Any LaTeX application will compile the tutorial, but if you want to compile it
in a terminal, run the following commands:   
$ pdflatex latex-tutorial.tex  
$ bibtex latex-tutorial.aux  
$ pdflatex latex-tutorial.tex  
$ pdflatex latex-tutorial.tex  

That should make a pdf file with the proper figure and citation labels.
