A simple latex report template
==============================

This is a simple latex report template. It is based on the [ctexart](http://www.ctex.org/HomePage) class.

Motivation
----------
I often need to use latex to write reports, but every time I have to re-modify the introduction area (requirepackage, setup, define, balabala...), which is cumbersome. So I wrote this template for easy reuse.

Why not use an existing template: writing a report only requires simple typesetting, but most of the existing templates are very complex, and some functions are not required, which will increase the time cost. I like simplicity :D

Usage
------
[Template preview](https://ysyszheng.github.io/report-template/main.pdf).

1. Install texlive, and the ctex suite (or use [overleaf](https://www.overleaf.com/))
2. - Ordinary users: directly modify the [main.tex](./main.tex) file, and then compile it.
   - Developer: Modify the [main.tex](./main.tex) file, and then compile. You can also modify [report.sty](./report.sty) and [header.tex](./header.tex) file, and then compile.

TODO
-----
- [x] code insertion
- [x] long table rotation
- [x] hyperlink styles
- [x] special symbol
- [ ] algorithm
- [ ] abstract & keywords
- [ ] Other functions (to be added)
