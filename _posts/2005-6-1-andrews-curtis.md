---
layout: default
title: The Andrews-Curtis Conjecture
categories:
   - mathematics
   - programming
---
The <a
href="http://en.wikipedia.org/wiki/Andrews%E2%80%93Curtis_conjecture">Andrews-Curtis
conjecture</a> is a fascinating conjecture with deep connections to
topology.  I started thinking about this problem in 2003 not knowing
much about the math, but eager to use a computer to verify some
examples.  In 2006 my colleague Stephen McCaul and I published our
results on using an IBM zSeries mainframe to look for examples in <a
href="http://projecteuclid.org/euclid.em/1175789740">Fast Searching
for Andrews-Curtis Trivializations</a>.  In 2005 I specialized our
code to work with an in-memory hashtable, speeding it up by several
orders of magnitude.

[View the C code at github.](https://github.com/rsbowman/ac-mem)
