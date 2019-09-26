CSULB M.S. Thesis Template
==============

M.S. thesis template at California State University Long Beach (CSULB) for the Department of Physics and Astronomy

History
------

- (2016-01-09) Updated style sheets to support bold titles instead of underlines
- (2019-08-04) Simplified main file


How to Use
------

Use `git` to clone the M.S. thesis template:

    git clone https://github.com/thomasgredig/MSthesis-template

As the compiler use `miktex` with the appropriate GUI, on Mac that would probably be `TeXShop` and on Windows, it would be `WinShell`. If you do not want to worry about compilers
you can use the [OverLeaf environment](http://www.overleaf.com) online and upload these files. Moreover, for tables an online generator is
really useful, such as [TableGenerator](http://www.tablegenerator.com).

Steps:
+ configure `myConfig.tex`
+ try to compile `MS-thesis.tex`
+ add figures into folders `FIGS`
+ add bibliography file (export from Zotero)
+ Complete the files in the manuscript folder
+ compile.


Additional Tools
----

You can find more tips on how to write a compelling M.S. thesis using the [Gredig Lab Guidelines](https://github.com/thomasgredig/MSthesis-Guidelines). If the Bibliography file needs to be shortened, then use [LaTeX Trim BibTeX Utility](https://github.com/thomasgredig/LaTeX-trim-BibTeX). You should cite other M.S. thesis work, whenever you are using their work. Here is an automated way to generate the bibliography items, using the [ProQuest Citation Generator](https://github.com/thomasgredig/MSthesis-ProQuest-Cite).
