wustl_thesis
============

A LaTeX template for generating thesis documents for Washington University. 

Authors
-------
Original version by Long Duan in 1996. Subsequent updates by Greg Hackmann 2005-2008 and David Lu in 2014.

Quick Start
-----------
If you already know your way around LaTeX pretty well, check out [minimal.tex](minimal.tex) 
which generates [this pdf](minimal.pdf). The only file you will need to build this is 
[wuthesis.cls](wuthesis.cls). You will need to renew a bunch of commands to get
your name/information to be input into the template. 


Step By Step
------------
A more thorough example is given in [thesis.tex](thesis.tex), which shows specifically
which commands need to be renewed. Along with [setup.tex](setup.tex), 
[demo_content.tex](demo_content.tex) and [citations.bib](citations.bib), it generates
the [this pdf](thesis.pdf). It also requires you to download [wuthesis.cls](wuthesis.cls)

Note: If you don't want to build your document with the entire front matter, you can switch
out which setup file you use (uncomment `\input{fake_setup}` and comment out `\input{setup}`
which will instead create a [much simpler title page](light_thesis.pdf). 


