LaTeX package 'ifetex'
~~~~~~~~~~~~~~~~~~~~~~
Copyright (c) 2011-2022 by Martin Scharrer <martin.scharrer@web.de>
CTAN: http://www.ctan.org/pkg/ifetex
Code repository: https://github.com/MartinScharrer/ifetex/
Issue tracker: https://github.com/MartinScharrer/ifetex/issues

This small package provides the if-switch \ifetex which indicated whether
e-TeX is available or not.

The package can be loaded as LaTeX package using `\usepackage{ifetex}` or in
plainTeX using `\input ifetex`. In both cases it aborts silently if the \ifetex macro
is already defined.

The package currently test if \eTeXversion is defined as a primitive and
assumes e-TeX if so.

