# Michael Wadman - CV

Heavily inspired by [Awesome-CV](https://github.com/posquit0/Awesome-CV), used more as a LaTeX learning experience.  
A LaTeX cheat sheet that I wrote can be found [in my Gists](https://gist.github.com/mwadman/a3443e3a6e5ceac57ac4961d6c607e0e).

## To Build

### Required Packages

#### Ubuntu/Debian

```bash
sudo apt-get install -y texlive texlive-latex-extra latexmk texlive-fonts-extra lacheck chktex
```

#### Arch

```bash
sudo pacman -Syu texlive-core texlive-latexextra texlive-fontsextra
```

### Syntax Check/Lint

```bash
lacheck MichaelWadman_CV.tex
chktex MichaelWadman_CV.tex
```

### Generate PDF

```bash
pdflatex MichaelWadman_CV.tex
```

If generating this for an application submission, remember to change (and uncomment) the `\phone` variable.
