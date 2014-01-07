# My LaTeX resume

This is a fork of the great work done by [Cies Breijs](https://github.com/cies/resume). I already wrote my master thesis in LaTeX, so naturally I am now writing my resume in it as well. I decided to remix an existing project in this case. I like its overall look very much, it has this nice "research paper" quality to it.

## Generating the PDF

XeLaTeX is a version of Latex with great font rendering fuctionality (unicode, bidi,
special font features).  Since my resume uses 'lower case numerals' it
looks slightly better with XeLaTeX.

In recent Ubuntu versions you simply clone this project, change
directory to the root of the project and do:

        sudo apt-get install texlive-xetex texlive-latex-recommended tex-gyre ttf-linux-libertine
        ./pdflatex *-resume.pdf

For Arch Linux, install these packages:

        sudo pacman -S texlive-core texlive-bin tex-gyre-fonts texlive-latexextra ttf-linux-libertine

If all went well an updated version of the PDF is found in your current
working directory, alongside a bunch of `.log` and `.aux` files that
you can safely ignore.

## Terms of sharing

Feel free to use, copy, fork, share, study and/or modify it because the LaTeX source code of the `resume.sty` file is [MIT](http://en.wikipedia.org/wiki/MIT_License) licensed.

The text of my resume in the `cmeury-resume.tex` file is [CC-NC-ND](http://creativecommons.org/licenses/by-nc-nd/3.0/) licensed.
