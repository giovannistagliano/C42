# C42
A surface in PP_QQ^5 of degree 9 and sectional genus 2 with 5 nodes.

Load this file in Macaulay2 using: load "C42.m2"

If K is a field, the command S42(K) returns a pair (S,f) defined over K, 
where S is a surface in P^5 of degree 9 and sectional genus 2 with 5 nodes,
f:P^5-->Grass(1,4) is a rational map defined by the quadrics through a cubic scroll
and which sends the surface S to a smooth surface of degree 9 and sectional genus 2.

For more details on this surface see the paper https://arxiv.org/abs/1909.01263.

A random example of such a surface can also be obtained with the command 
```
surface specialCubicFourfold("C42",K) 
```
provided by the package SpecialFanoFourfolds.
