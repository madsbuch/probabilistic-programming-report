# PL and ML Report

Download PDF [here](https://github.com/madsbuch/probabilistic-programming-report/raw/master/main.pdf).

This report is discontinued as is. It is continued as an online book on
[learn.madsbuch.com](http://learn.madsbuch.com/u/dashboard/books).

Building:

    pdflatex -shell-escape main.tex
    bibtex main.aux
    pdflatex -shell-escape main.tex

## Template README

This is Elsevier's new document class for typeset journal articles, elsarticle.cls.  It is accepted for submitted articles, both in Elsevier's electronic submission system and elsewhere.

elsarticle.cls is based upon the standard LaTeX document class article.cls. It uses natbib.sty for bibliographic references.

Bugs and problems with elsarticle.cls may be reported to the developers of the class via elsarticle@river-valley.com.  For all other enquiries please contact Elsevier author support at support@elsevier.com

The following are the main files available:
- elsarticle.cls, the class file
- elsdoc.pdf, the user documentation
- elsarticle-template-num.tex, general template file for numerical references
- elsarticle-template-harv.tex, general template file for name-year references
- elsarticle-num.bst, bibliographic style for numerical references
- elsarticle-harv.bst, bibliographic style for name-year references
- elsarticle-num-names.bst, bibliographic style for numerical references with author-year citation
- model*.bst - bibliographic style files for Elsevier standard reference styles
- elsarticle-template-*.tex - manuscript templates for the above reference styles
- numcompress.sty - an additional package required for use with reference style models 3, 3a, 4 and 6.

Copyright 2007-2010, Elsevier. Bugs, feature requests, suggestions and comments may be mailed to elsarticle@river-valley.com. elsarticle.cls, related documentation and supporting packages are released under the LATEX Project Public Licence, either version 1.3 or any later version. This work has the LPPL maintenance status 'author-maintained'.
