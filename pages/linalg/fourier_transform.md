---
title: Fourier Transform
sidebar: linalg_sidebar
permalink: linalg_fourier_transform.html
folder: linalg
---
## Fourier Series
It says that any periodic function can be written as a linear combination of sines and cosines of different frequencies.
Say _f(x)_ is my periodic function. It can be expanded using fourier series as follows:

<img src="{{site.latex}};f(x)=a_0 + a_1cos(x) + b_1sin(x) + a_2cos(2x) + b_2sin(2x) + ..." title="latex"/>

<img src="{{site.latex}};\Rightarrow f(x)= a_0 + \sum_{f=1}^{\infty}{[a_fcos(fx) + b_fsin(fx)]}" title="latex"/>

In Physics, people would love this as a function of time instead of `x`. And that's not the end of it.
They will also represent frequencies in the radian form. Let me do it for you step by step:
 
<img src="{{site.latex}};f(t)= a_0 + \sum_{f=1}^{\infty}{[a_fcos(ft) + b_fsin(ft)]}" title="latex"/>

<img src="{{site.latex}};\Rightarrow f(x)=a_0 + \sum_{k=1}^{\infty}{[a_kcos(2{\pi}kt) + b_ksin(2{\pi}kt)]}" title="latex"/>

## Continuous Fourier Transform

sdjgkls


## Discrete Fourier Transform


## Fast Fourier Transform

