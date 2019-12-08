# Michael Wadman - CV

[![Build Status](https://travis-ci.org/mwadman/CV.svg?branch=master)](https://travis-ci.org/mwadman/CV)

Heavily inspired by [Awesome-CV](https://github.com/posquit0/Awesome-CV), used more as a LaTeX learning experience.  
A LaTeX cheat sheet that I wrote can be found [in my Gists](https://gist.github.com/mwadman/a3443e3a6e5ceac57ac4961d6c607e0e).

## To Build

First, install the required packages.  
On Ubuntu, these are as follows:

```bash
sudo apt-get install -y texlive texlive-latex-extra latexmk texlive-fonts-extra
```

Next, simply generate the PDF using `pdflatex`:

```bash
pdflatex MichaelWadman_CV.tex
```

If generating this for an application, remember to change (and uncomment) the `\phone` variable.

