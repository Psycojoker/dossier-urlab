# Requirements

Latex et le package "texlive-latex-extra" dans debian.

Sous debian et dérivées:

    sudo apt-get install texlive-base texlive-latex-extra texlive-lang-french texlive-fonts-recommended

N'hésitez pas à ne pas prendre les packages -doc qui prennent plein de places et ne servent à rien.

# Compilation

Faire 2 fois (une fois pour la table des matières):

    pdflatex urlab.tex

ou

    make

Si make est installé.
