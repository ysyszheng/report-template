A simple latex report template
==============================

This is a simple latex report template. It is based on the [ctexart](http://www.ctex.org/HomePage) class.

Motivation
----------
经常需要用latex写report, 但是每次都要重新写一遍模板, 比较繁琐. 于是写了这个模板, 可以直接使用.

为什么不使用现有的轮子: 写report只需要简单的排版, 但是现有的模板大多很复杂, 有些功能不需要, 反而会增加时间成本. 我喜欢简洁:D

Usage
------
[模板预览](https://ysyszheng.github.io/report-template/main.pdf).

1. 安装texlive, 以及ctex套件(或使用overleaf)
2. - 普通用户: 直接修改[main.tex](./main.tex)文件, 然后编译即可.
   - 开发者: 修改[main.tex](./main.tex)文件, 然后编译即可. 也可以修改[report.sty](./report.sty)与[header.tex](./header.tex)文件, 然后编译.

TODO
-----
- [x] 代码插入
- [x] 长表格旋转
- [x] 超链接样式
- [x] 特殊符号
- [ ] 其他功能(待补充)

Happy Coding!