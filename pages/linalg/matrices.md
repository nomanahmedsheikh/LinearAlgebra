---
title: Matrices
sidebar: linalg_sidebar
permalink: linalg_matrices.html
folder: linalg
---

## What is Matrix?
Well, we all know what a matrix is. Or perhaps, how does a matrix look like. For those who don't, this is what a 2x3 matrix looks like

<img src="https://latex.codecogs.com/svg.latex?\Large&space;\textbf{A} = \begin{bmatrix} 1 & 1 & 3 \\ 1 & 2 & 1 \end{bmatrix}" title="latex"/>

I will use a bold-faced character (such as **A**) to denote a matrix throughout the material. 

**How to not look at a Matrix?**

If you search for definition of a matrix on web, most of the articles defines matrix as a "Rectangular arrangement of numbers". 
This means that our matrix **`A`** is a collection of 6 numbers arranged in a certain fashion.
This is a very naive way of looking at matrices. And I _do not want you_ to look at matrices in such a fashion. 

*Matrices are more than a mere collection of numbers*

  
## Interpreting a Matrix
In Linear Algebra, we have many different ways of interpreting a matrix. But two of them are very commonly used:
- Column Way
- Row Way

I will describe in detail what `Column Way` means and what does it represent. 
Once we grasp it effectively, details about `Row Way` will follow immediately.

### Column Way
As I mentioned earlier, do not look at a matrix as a collection of numbers. 

Look at matrix as a **collection of vectors**.
Where each column of a matrix is nothing but a vector in a coordinate space. 
And we all know that a vector represents a point in coordinate system.
And therefore a matrix is a collection of points represented by its columns. 

In our little matrix **A** above, we have three columns which is equivalent to having three points in some space.
Each column has length 2, which means each point will lie in a two dimensional space.
Also, if our matrix has real values in it, we call that space **ℝ<sup>2</sup>**.

Lets draw these columns in our ℝ<sup>2</sup> space

<img src="images/linalg/matrices_01.png" title="columns" style="height:300px;">

And now we would love to call **A** as an ordered collection of 3 points in 2D space.

### Row Way
Similar to our column way, you can look at a matrix a collection of vectors represented by rows of the matrix.
For our matrix **A**, each vector has 3 components and will represent points in 3D space also called as ℝ<sup>3</sup>.
**A** will correspond to a collection of two points namely `(1,1,3)` and `(1,2,1)`.

This is how these rows look like in ℝ<sup>3</sup>

<img src="images/linalg/matrices_02.png" title="columns" style="height:300px;">


These two ways of interpreting a matrix may sound a little unintuitive at first.
But it will help us long time in our journey into Linear Algebra :slightly_smiling_face 



