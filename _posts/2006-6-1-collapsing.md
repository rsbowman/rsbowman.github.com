---
layout: default
title: Collapsing Simplicial Complexes
categories:
   - mathematics
   - programming
---
Written in 2006, this program attempts to <a
href="http://en.wikipedia.org/wiki/Collapse_(topology)">collapse</a> a
<a href="http://en.wikipedia.org/wiki/Simplicial_complex">simplicial complex</a> (it's specialized to work on 3-complexes).  I wrote it to
examine a conjecture of Zeeman, which says roughly that the product of
a contractible 2-complex and the interval is collapsible.
Unfortunately, all I found out is that there are <b>a lot</b> of ways
to collapse a 3-complex.  The code was originally in Haskell, then in
optimized Python, and finally in heavily optimized C.

<a href="https://github.com/rsbowman/ASC">View the code on github.</a>
