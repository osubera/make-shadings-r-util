# make-shadings-r-util
make.shadings.R is a util function for R statistics

This was first published at code.google.com repository, and moved here, github.com.

make.shadings
http://code.google.com/p/cowares-excel-hello/source/browse/trunk/util_r/

Copyright (C) 2013 Tomizono
Fortitudinous, Free, Fair, http://cowares.nobody.jp
http://paidforeveryone.wordpress.com/

generate shading patterns of specified number
output a list of density vector and angle vector

density=NA and angle=NA : default : no shadings, generates two NULLs
density=T or angle=T : shadings with automatic range
density=10 : use the number as fixed density and genrates auto angles
angle=30 : use the number as fixed angle and generates auto densities
density=c(3, 20) : generates densities between 3 and 20 lines per inch
angle=c(30, 90) : generates angles between 30 and 90 degree

densities are shuffled by fixed shuffling variable
