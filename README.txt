----------------------------------------------------------------
linalg --- Convenience macros for typesetting linear algebra
E-mail: eac@opmbx.org
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt
----------------------------------------------------------------

This package sets up various packages and defines a series of macros to aid
the writing of mathematical texts that contain algebraic notation.  It is
intended for the personal use of its author and it has only been tested with
the XeTeX engine.

To install this package in the user's directory tree on a Unix system do:

  xelatex linalg.dtx
  xelatex linalg.dtx
  ctanify -d `kpsewhich --var-value TEXMFHOME` -- \
    linalg.ins linalg.pdf README.txt

(Notice that xelatex is run twice.)


