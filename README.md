# Definitions for LuaTeX

Definitions for [LuaTeX](https://www.luatex.org)

TeXLuaCATS-Repository: https://github.com/TeXLuaCATS/LuaTeX (upstream)

LuaCATS-Repository: https://github.com/LuaCATS/tex-luatex (downstream)

## About the documented project

LuaTeX is a greatly extended version of pdfTeX using Lua as an embedded
scripting language. The LuaTeX project’s main objective is to provide an
open and configurable variant of TeX while at the same time offering
substantive backward compatibility.

LuaTeX uses Unicode (as UTF-8) as its default input encoding, and is
able to use modern (OpenType and TrueType) fonts (for both text and
mathematics).[^ctan]

[^ctan]: https://www.ctan.org/pkg/luatex

* PDF-Manual: [luatex.pdf](http://mirrors.ctan.org/systems/doc/luatex/luatex.pdf)
* Repository: [gitlab.lisn.upsaclay.fr/texlive/luatex](https://gitlab.lisn.upsaclay.fr/texlive/luatex/)
* CTAN: [luatex](https://www.ctan.org/pkg/luatex)
* LICENSE: [GPL-2.0-or-later](https://gitlab.lisn.upsaclay.fr/texlive/luatex/-/blob/master/COPYING)

### References

* Corresponding C source code: [source/texk/web2c/luatexdir](https://gitlab.lisn.upsaclay.fr/texlive/luatex/-/tree/master/source/texk/web2c/luatexdir)
* Source file of the `LuaTeX` manual: [manual](https://gitlab.lisn.upsaclay.fr/texlive/luatex/-/tree/master/manual)
* Victor Eijkhout. “TeX by Topic” (1991, 2007): [TeXbyTopic.pdf](http://mirrors.ctan.org/info/texbytopic/TeXbyTopic.pdf)
* Donald Ervin Knuth. “The TexBook” (1984): [TeX-Source](https://ctan.org/tex-archive/systems/knuth/dist/tex/texbook.tex) [PDF](https://visualmatheditor.equatheque.net/doc/texbook.pdf)
* David Bausum. “TeX Reference Manual” (2002): [cseq.html](https://www.tug.org/utilities/plain/cseq.html)
* Donald Ervin Knuth. “TeX: The Program”: [tex.pdf](https://mirrors.ctan.org/info/knuth-pdf/tex/tex.pdf)
* Corresponding fontforge C source code: [github.com/fontforge/fontforge](https://github.com/fontforge/fontforge)
* Hàn Thế  Thành and others. The pdfTEX user manual, pdfTEX 1.40.27, February 12, 2025 [pdftex-a.pdf](http://mirrors.ctan.org/systems/doc/pdftex/manual/pdftex-a.pdf)

The description text can be or was taken from the official [LuaTeX
reference manual](https://gitlab.lisn.upsaclay.fr/texlive/luatex/-/tree/master/manual).
In the project folder
[resources/manual](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual)
you will find slightly edited `Lua` versions of the `LuaTeX` manual
sources.

1.  [Preamble](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/01_preamble.tex.lua)
2.  [Basic TEX enhancements](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/02_enhancements.tex.lua)
3.  [Modifications](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/03_modifications.tex.lua)
4.  [Using LUATEX](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/04_lua.tex.lua)
5.  [Languages, characters, fonts and glyphs](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/05_languages.tex.lua)
6.  [Font structure](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/06_fonts.tex.lua)
7.  [Math](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/07_math.tex.lua)
8.  [Nodes](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/08_nodes.tex.lua)
9.  [LUA callbacks](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/09_callbacks.tex.lua)
10. [The TEX related libraries](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/10_tex.tex.lua)
11. [The graphic libraries](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/11_graphics.tex.lua)
12. [The fontloader](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/12_fontloader.tex.lua)
13. [The HarfBuzz libraries](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/13_harfbuzz.tex.lua)
14. [The backend libraries](https://github.com/TeXLuaCATS/LuaTeX/blob/main/resources/manual/14_backend.tex.lua)
