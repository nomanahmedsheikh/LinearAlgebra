---
title: Spaces and Subspaces
sidebar: linalg_sidebar
permalink: linalg_spaces_subspaces.html
folder: linalg
---

## Vector Space
It is a hypothetical universe (or space) where our vectors lie. 
Not every random space can be called a vector space.
It has to satisfy certain conditions before we can call it a vector space.

A space is called as `Vector Space` if it satisfies these two properties:
1. **Addition**: Sum of two vectors in a vector space should lie in the same vector space.
If **u** and **v** lie in vector space 𝕍, then **u** + **v** also lies in 𝕍.
2. **Scalar Multiplication**: Multiplication by a real scalar should lie inside the same vector space.
If **u** lies in 𝕍, then c**u** also lies in 𝕍.

### Examples
1. ℝ<sup>2</sup>: all two dimensional real vectors form a vector space which is also known as the x-y plane. 
Consider any set of two dimensional vectors such as `(3,2)`, `(0,0)` or `(π, e)`. 
Sum of these vectors will be a two dimensional real vector. Similarly, scalar multiplication of these two vectors gives a vector in ℝ<sup>2</sup>.

2. ℝ<sup>n</sup>: all column vectors with n components

Now, let me give you an example of something that is not a vector space. 
Consider _first quadrant of the x-y plane_. This is not a vector space. Why??
- Well, it satisfies the addition property
- But it fails for multiplication property. If we multiply any vector in first quadrant with a negative scalar, we would end up in third quadrant.

More formally we can say that the space mentioned in the above example is **closed** with respect to additions but it is not closed with respect to scalar multiplication.

> A space qualifies as a vector space if it is closed with respect to addition as well as scalar multiplication.   


## Subspaces
_Can we find a portion or subset of vector space that is itself a vector space?_
Lets try:
- Suppose we start with <img src="https://latex.codecogs.com/svg.latex?\Large&space;\begin{bmatrix} 3 \\ 2\end{bmatrix}" title="latex"/> in ℝ<sup>2</sup>.
All scalar multiplication of this vector will give us a line.
- Any two point on that line will add up to give another point on the same line.
- Therefore, this line is a vector space also called as **subspace of ℝ<sup>2</sup>**.
- Note that its not the same as ℝ. Here vectors have 2 components.

<img src="images/linalg/spaces_subspaces_01.png" title="subspace" style="height:200px;">

> Any line not passing through origin (or zero vector) will not be a vector space. Zero vector has to be present.

### Examples
Lets think of some obvious subspaces of ℝ<sup>2</sup>

1. All of the ℝ<sup>2</sup> space itself. Well, why not!!! A vector space is a subspace of itself.
2. Any line passing through `(0,0)` is also a subspace of ℝ<sup>2</sup>.
3. Zero Vector alone. This is also a subspace which consists of only one vector i.e. zero vector.



_Now that we know what vector spaces and subspaces mean, we can now bring matrices in the movie.
Next topic will describe the multiple vector spaces that a matrix represent._ 
