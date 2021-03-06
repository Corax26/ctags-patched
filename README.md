ctags-patched
=============

Ctags with some improvements.

This is a fork of [Ctags](http://ctags.sourceforge.net/) based on Ctags 5.8.

I'm the author of all the modifications below, unless otherwise specified.

It contains the following improvements (in chronological order):
* C++: support for C++11 new using semantics (typedef): [patch #84](http://sourceforge.net/p/ctags/patches/84/)
* C++: constructors and bug fixes [patch #77](http://sourceforge.net/p/ctags/patches/77/) [not from me, thanks lyokha]
* C/C++: don't add a macro tag when an #undef directive is encountered (seriously, why #undef should yield a macro tag?)
* C++: support for C++11 typed enums (enum E : char {...};)
* C++: support for C++11 enum classes
* Ada: add Ada support using GNU Ada Project's [ada.c](http://sourceforge.net/p/gnuada/code/HEAD/tree/trunk/tools/ctags/ada.c)
