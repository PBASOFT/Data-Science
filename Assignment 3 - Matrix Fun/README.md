Matrix Fun

```diff
- work in progress
```

## Task 1
Given the two following matrices: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?A&space;=&space;\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}&space;B&space;=&space;\begin{pmatrix}&space;-1&space;&&space;4\\&space;3&space;&&space;8&space;\end{pmatrix}" title="A = \begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix} B = \begin{pmatrix} -1 & 4\\ 3 & 8 \end{pmatrix}" />

Python with Numpy:

<img src="./images/create_matrices.png" width="700"/>

**(a)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;A^{T}" title="A^{T}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?A^{T}&space;=&space;\begin{pmatrix}&space;3&space;&&space;2\\&space;1&space;&&space;6&space;\end{pmatrix}" title="A^{T} = \begin{pmatrix} 3 & 2\\ 1 & 6 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1a.png" width="700"/>


**(b)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;B^{T}" title="B^{T}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?B^{T}&space;=&space;\begin{pmatrix}&space;-1&space;&&space;3\\&space;4&space;&&space;8&space;\end{pmatrix}" title="B^{T} = \begin{pmatrix} -1 & 3\\ 4 & 8 \end{pmatrix}" />

 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:
 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1b.png" width="700"/>
  
  
**(c)** Find AB (matrix multiplication). Compare with simple multiplication
(using * instead of @ in Python). Can you see what is the difference?

 - Using * on two matrices in python => elementwise multiplication:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}&space;*&space;\begin{pmatrix}&space;-1&space;&&space;4\\&space;3&space;&&space;8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;3*-1&space;&&space;1*4\\&space;2*3&space;&&space;6*8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;-3&space;&&space;4\\&space;6&space;&&space;48&space;\end{pmatrix}" title="\begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix} * \begin{pmatrix} -1 & 4\\ 3 & 8 \end{pmatrix} = \begin{pmatrix} 3*-1 & 1*4\\ 2*3 & 6*8 \end{pmatrix} = \begin{pmatrix} -3 & 4\\ 6 & 48 \end{pmatrix}" />

 - Using @ on two matrices in python => dot product:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}&space;@&space;\begin{pmatrix}&space;-1&space;&&space;4\\&space;3&space;&&space;8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;3*-1&plus;1*3&space;&&space;3*4&plus;1*8\\&space;2*-1&plus;6*3&space;&&space;2*4&plus;6*8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;0&space;&&space;20\\&space;16&space;&&space;56&space;\end{pmatrix}" title="\begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix} @ \begin{pmatrix} -1 & 4\\ 3 & 8 \end{pmatrix} = \begin{pmatrix} 3*-1+1*3 & 3*4+1*8\\ 2*-1+6*3 & 2*4+6*8 \end{pmatrix} = \begin{pmatrix} 0 & 20\\ 16 & 56 \end{pmatrix}" />

   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1c.png" width="900"/>
  
  
**(d)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;AB^{T}" title="AB^{T}" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?AB^{T}&space;=&space;\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="AB^{T} = \begin{pmatrix} 0 & 16\\ 20 & 56 \end{pmatrix}" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1d.png" width="700"/>


**(e)** Compare <img src="https://latex.codecogs.com/gif.latex?\inline&space;AB^{T}" title="AB^{T}" /> and <img src="https://latex.codecogs.com/gif.latex?\inline&space;A^{T}B^{T}" title="A^{T}B^{T}" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?AB^{T}&space;=&space;\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="AB^{T} = \begin{pmatrix} 0 & 16\\ 20 & 56 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?B^{T}A^{T}=\begin{pmatrix}&space;-1&space;&&space;3\\&space;4&space;&&space;8&space;\end{pmatrix}&space;\begin&space;{pmatrix}&space;3&space;&&space;2\\&space;1&space;&&space;6&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;-1\cdot&space;3&plus;3\cdot&space;1&space;&&space;-1\cdot&space;2&plus;3\cdot&space;6\\&space;4\cdot&space;3&plus;8\cdot&space;1&space;&&space;4\cdot&space;2&plus;8\cdot&space;6&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="B^{T}A^{T}=\begin{pmatrix} -1 & 3\\ 4 & 8 \end{pmatrix} \begin {pmatrix} 3 & 2\\ 1 & 6 \end{pmatrix} = \begin{pmatrix} -1\cdot 3+3\cdot 1 & -1\cdot 2+3\cdot 6\\ 4\cdot 3+8\cdot 1 & 4\cdot 2+8\cdot 6 \end{pmatrix} = \begin{pmatrix} 0 & 16\\ 20 & 56 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1e.png" width="700"/>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?AB^{T}=\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="AB^{T}=\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?B^{T}A^{T}=\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="B^{T}A^{T}=\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" />


**(f)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;(A^{T})^{T}" title="(A^{T})^{T}" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?(A^{T})^{T}&space;=&space;\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}" title="(A^{T})^{T} = \begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1f.png" width="700"/>


**(g)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;AA^{T}" title="AA^{T}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?A&space;=&space;\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}" title="A = \begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix}" /> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://latex.codecogs.com/gif.latex?A^{T}&space;=&space;\begin{pmatrix}&space;3&space;&&space;2\\&space;1&space;&&space;6&space;\end{pmatrix}" title="A^{T} = \begin{pmatrix} 3 & 2\\ 1 & 6 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}\begin{pmatrix}&space;3&space;&&space;2\\&space;1&space;&&space;6&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;3\cdot&space;3&plus;1\cdot&space;1&space;&&space;3\cdot&space;2&plus;1\cdot&space;6\\&space;2\cdot&space;3&plus;6\cdot&space;1&space;&&space;2\cdot&space;2&plus;6\cdot&space;6&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;10&space;&&space;12\\&space;12&space;&&space;40&space;\end{pmatrix}" title="\begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix}\begin{pmatrix} 3 & 2\\ 1 & 6 \end{pmatrix} = \begin{pmatrix} 3\cdot 3+1\cdot 1 & 3\cdot 2+1\cdot 6\\ 2\cdot 3+6\cdot 1 & 2\cdot 2+6\cdot 6 \end{pmatrix} = \begin{pmatrix} 10 & 12\\ 12 & 40 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1g.png" width="700"/>



# Task 2

Given 

<img src="https://latex.codecogs.com/gif.latex?A=\begin{pmatrix}&space;2&space;&&space;1\\&space;3&space;&&space;2&space;\end{pmatrix}&space;B=\begin{pmatrix}&space;1&space;&&space;2\\&space;3&space;&&space;4&space;\end{pmatrix}" title="A=\begin{pmatrix} 2 & 1\\ 3 & 2 \end{pmatrix} B=\begin{pmatrix} 1 & 2\\ 3 & 4 \end{pmatrix}" />


**(a)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;AB" title="AB" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;2&space;&&space;1\\&space;3&space;&&space;2&space;\end{pmatrix}&space;\begin{pmatrix}&space;1&space;&&space;2\\&space;3&space;&&space;4&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;2\cdot&space;1&plus;1\cdot&space;3&space;&&space;2&space;\cdot&space;2&plus;1\cdot&space;4\\&space;3\cdot&space;1&plus;2\cdot&space;3&space;&&space;3\cdot&space;2&plus;2\cdot&space;4&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;5&space;&&space;8\\&space;9&space;&&space;14&space;\end{pmatrix}" title="\begin{pmatrix} 2 & 1\\ 3 & 2 \end{pmatrix} \begin{pmatrix} 1 & 2\\ 3 & 4 \end{pmatrix} = \begin{pmatrix} 2\cdot 1+1\cdot 3 & 2 \cdot 2+1\cdot 4\\ 3\cdot 1+2\cdot 3 & 3\cdot 2+2\cdot 4 \end{pmatrix} = \begin{pmatrix} 5 & 8\\ 9 & 14 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/2a.png" width="700"/>


**(b)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;BA" title="BA" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;1&space;&&space;2\\&space;3&space;&&space;4&space;\end{pmatrix}\begin{pmatrix}&space;2&space;&&space;1\\&space;3&space;&&space;2&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;1\cdot&space;2&plus;2\cdot&space;3&space;&&space;1\cdot&space;1&plus;2\cdot&space;2&space;\\&space;3\cdot&space;2&plus;4\cdot&space;3&space;&&space;3\cdot&space;1&plus;4\cdot&space;2&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;8&space;&&space;5\\&space;18&space;&&space;11&space;\end{pmatrix}" title="\begin{pmatrix} 1 & 2\\ 3 & 4 \end{pmatrix}\begin{pmatrix} 2 & 1\\ 3 & 2 \end{pmatrix} = \begin{pmatrix} 1\cdot 2+2\cdot 3 & 1\cdot 1+2\cdot 2 \\ 3\cdot 2+4\cdot 3 & 3\cdot 1+4\cdot 2 \end{pmatrix} = \begin{pmatrix} 8 & 5\\ 18 & 11 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/2b.png" width="700"/>


# Task 3

The inverse of a matrix  <img src="https://latex.codecogs.com/gif.latex?\inline&space;A=\begin{pmatrix}&space;a&space;&&space;b\\&space;c&space;&&space;d&space;\end{pmatrix}" title="A=\begin{pmatrix} a & b\\ c & d \end{pmatrix}" /> is found by 

<img src="https://latex.codecogs.com/gif.latex?\inline&space;A^{-1}=\frac{1}{ad-bc}\begin{pmatrix}&space;d&space;&&space;-b&space;\\&space;-c&space;&&space;a&space;\end{pmatrix}" title="A^{-1}=\frac{1}{ad-bc}\begin{pmatrix} d & -b \\ -c & a \end{pmatrix}" />

As seen in listing 1, the inverse of a matrix can be found easily with numpy
(after having imported numpy.linalg.inv) by: inv(A).
Using the same matrices from Task 2:

**(a)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;A^{-1}" title="A^{-1}" />

<img src="https://latex.codecogs.com/gif.latex?A^{-1}=\frac{1}{2\cdot&space;2-1\cdot&space;3}\begin{pmatrix}&space;2&space;&&space;-1\\&space;-3&space;&&space;2&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;1\cdot&space;2&space;&&space;1\cdot&space;-1\\&space;1\cdot&space;-3&space;&&space;1\cdot&space;2&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;2&space;&&space;-1\\&space;-3&space;&&space;2&space;\end{pmatrix}" title="A^{-1}=\frac{1}{2\cdot 2-1\cdot 3}\begin{pmatrix} 2 & -1\\ -3 & 2 \end{pmatrix} = \begin{pmatrix} 1\cdot 2 & 1\cdot -1\\ 1\cdot -3 & 1\cdot 2 \end{pmatrix} = \begin{pmatrix} 2 & -1\\ -3 & 2 \end{pmatrix}" />



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/3a.png" width="600"/>


**(b)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;B^{-1}" title="B^{-1}" />

<img src="https://latex.codecogs.com/gif.latex?\inline&space;B^{-1}=\frac{1}{1\cdot&space;4-2\cdot&space;3}\begin{pmatrix}&space;4&space;&&space;-2\\&space;-3&space;&&space;1&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;-0,5\cdot&space;4&space;&&space;-0,5\cdot&space;-2\\&space;-0,5\cdot&space;-3&space;&&space;-0,5\cdot&space;1&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;-2&space;&&space;1\\&space;1,5&space;&&space;-0,5&space;\end{pmatrix}" title="B^{-1}=\frac{1}{1\cdot 4-2\cdot 3}\begin{pmatrix} 4 & -2\\ -3 & 1 \end{pmatrix} = \begin{pmatrix} -0,5\cdot 4 & -0,5\cdot -2\\ -0,5\cdot -3 & -0,5\cdot 1 \end{pmatrix} = \begin{pmatrix} -2 & 1\\ 1,5 & -0,5 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python with Numpy:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/3b.png" width="600"/>


**(b)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;AA^{-1}" title="AA^{-1}" />

