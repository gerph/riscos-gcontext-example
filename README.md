# RISC OS GContext example code

This repository contains some example code showing how you might use
the [GContext library](https://github.com/gerph/riscos-gcontext).
It demonstrates the creation of contexts, the use of font handles
to render font strings (0-terminated and explicitly sized), and the
distinction between the width of text (xoffset + r-bearing) and the
xoffset of the baseline position. It also shows the use of rectangles
to demonstrate how the graphics operations can be used.

The CI for the repository also shows how the GContext library can
be pulled in to build in CI. The Makefile shows how you reference
the C library.
