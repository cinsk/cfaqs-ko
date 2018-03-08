
C FAQs in Korean
================

This is the source files for the Korean version of C Programming FAQ,
the official FAQ from Usenet `comp.lang.c` which is written by Steve
Summit <scs@eskimo.com>.

The original version (in English) can be found at

        http://c-faq.com/
        (previously)  http://www.eskimo.com/~scs/



To build the output, you need recent version of Latex and latex2html.
Long time ago, I tested in following environment:

        Gentoo Linux:
          dev-texlive/texlive-latex-2017
          dev-texlive/texlive-langkorean-2017
          dev-tex/latex2html-2015
      
        Mac:
          MacTeX-2017           http://www.tug.org/mactex/
          latex2html 2018       (via 'brew install latex2html')

Note that latex2html from homebrew has an issue,
[25024](https://github.com/Homebrew/homebrew-core/issues/25024).



If you want to contribute for new contents/errta, read the RULES file
Once you're prepared, simply run 'make' to build PDF and HTML output.

    $ make
    


If you want to contribute for new contents/errta, read the RULES file
first, then send me an e-mail (cinsky at gmail.com) to describe the
problem or new contents, or give me a pull request.

