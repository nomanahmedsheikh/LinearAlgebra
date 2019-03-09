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

In Physics, people would love to see `f` as a function of time instead of `x`. And that's not the end of it.
They will also represent frequencies in the radian form. Let me do it for you step by step:
 
<img src="{{site.latex}};f(t)= a_0 + \sum_{f=1}^{\infty}{[a_fcos(ft) + b_fsin(ft)]}" title="latex"/>

<img src="{{site.latex}};\Rightarrow f(t)=a_0 + \sum_{k=1}^{\infty}{[a_kcos(2{\pi}kt) + b_ksin(2{\pi}kt)]}" title="latex"/>

### But How does it connect with Linear Algebra?
It does. Consider a vector space consisting of all possible periodic functions. Each vector (or point) in that space represents a period function.
We saw above that we can expand a period function using fourier series which is nothing but a linear combination of smartly chosen periodic functions.
This set of smartly chosen function form a basis of this vector space. And since there are infinite number of them, dimensionality of this space is also infinite.

Infact, I will go on and say that this basis is infact an orthogonal basis. But wait!!! _What does orthogonality of two functions mean?_

#### Orthogonal Functions
We say two vectors are orthogonal to each other if there dot product is zero. Therefore, we need to find something that is analogous to dot product of vectors.

_What is dot product?_ Point wise multiplication at all positions. That's how we define dot of two function.

<img src="{{site.latex}};f^Tg = \int_{0}^{2{\pi}}{f(x)g(x)dx} = 0" title="latex"/>

Period is <img src="{{site.latex}};2{\pi}" title="latex"/> for all the functions in our basis. 


## Continuous Fourier Transform

sdjgkls


## Discrete Fourier Transform


## Fast Fourier Transform

