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


Python with Numpy:

<img src="./images/1a.png" width="700"/>


**(b)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;B^{T}" title="B^{T}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?B^{T}&space;=&space;\begin{pmatrix}&space;-1&space;&&space;3\\&space;4&space;&&space;8&space;\end{pmatrix}" title="B^{T} = \begin{pmatrix} -1 & 3\\ 4 & 8 \end{pmatrix}" />

 Python with Numpy:
 
 <img src="./images/1b.png" width="700"/>
  
  
**(c)** Find AB (matrix multiplication). Compare with simple multiplication
(using * instead of @ in Python). Can you see what is the difference?

 - Using * on two matrices in python => elementwise multiplication:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}&space;*&space;\begin{pmatrix}&space;-1&space;&&space;4\\&space;3&space;&&space;8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;3*-1&space;&&space;1*4\\&space;2*3&space;&&space;6*8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;-3&space;&&space;4\\&space;6&space;&&space;48&space;\end{pmatrix}" title="\begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix} * \begin{pmatrix} -1 & 4\\ 3 & 8 \end{pmatrix} = \begin{pmatrix} 3*-1 & 1*4\\ 2*3 & 6*8 \end{pmatrix} = \begin{pmatrix} -3 & 4\\ 6 & 48 \end{pmatrix}" />

 - Using @ on two matrices in python => dot product:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?\begin{pmatrix}&space;3&space;&&space;1\\&space;2&space;&&space;6&space;\end{pmatrix}&space;@&space;\begin{pmatrix}&space;-1&space;&&space;4\\&space;3&space;&&space;8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;3*-1&plus;1*3&space;&&space;3*4&plus;1*8\\&space;2*-1&plus;6*3&space;&&space;2*4&plus;6*8&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;0&space;&&space;20\\&space;16&space;&&space;56&space;\end{pmatrix}" title="\begin{pmatrix} 3 & 1\\ 2 & 6 \end{pmatrix} @ \begin{pmatrix} -1 & 4\\ 3 & 8 \end{pmatrix} = \begin{pmatrix} 3*-1+1*3 & 3*4+1*8\\ 2*-1+6*3 & 2*4+6*8 \end{pmatrix} = \begin{pmatrix} 0 & 20\\ 16 & 56 \end{pmatrix}" />

   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="./images/1c.png" width="900"/>
  
  
**(d)** Find <img src="https://latex.codecogs.com/gif.latex?\inline&space;AB^{T}" title="AB^{T}" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?AB^{T}&space;=&space;\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="AB^{T} = \begin{pmatrix} 0 & 16\\ 20 & 56 \end{pmatrix}" />

Python with Numpy:

<img src="./images/1d.png" width="700"/>


**(e)** Compare <img src="https://latex.codecogs.com/gif.latex?\inline&space;AB^{T}" title="AB^{T}" /> and <img src="https://latex.codecogs.com/gif.latex?\inline&space;A^{T}B^{T}" title="A^{T}B^{T}" />

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?AB^{T}&space;=&space;\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="AB^{T} = \begin{pmatrix} 0 & 16\\ 20 & 56 \end{pmatrix}" />


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://latex.codecogs.com/gif.latex?B^{T}A^{T}=\begin{pmatrix}&space;-1&space;&&space;3\\&space;4&space;&&space;8&space;\end{pmatrix}&space;\begin&space;{pmatrix}&space;3&space;&&space;2\\&space;1&space;&&space;6&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;-1\cdot&space;3&plus;3\cdot&space;1&space;&&space;-1\cdot&space;2&plus;3\cdot&space;6\\&space;4\cdot&space;3&plus;8\cdot&space;1&space;&&space;4\cdot&space;2&plus;8\cdot&space;6&space;\end{pmatrix}&space;=&space;\begin{pmatrix}&space;0&space;&&space;16\\&space;20&space;&&space;56&space;\end{pmatrix}" title="B^{T}A^{T}=\begin{pmatrix} -1 & 3\\ 4 & 8 \end{pmatrix} \begin {pmatrix} 3 & 2\\ 1 & 6 \end{pmatrix} = \begin{pmatrix} -1\cdot 3+3\cdot 1 & -1\cdot 2+3\cdot 6\\ 4\cdot 3+8\cdot 1 & 4\cdot 2+8\cdot 6 \end{pmatrix} = \begin{pmatrix} 0 & 16\\ 20 & 56 \end{pmatrix}" />


Python with Numpy:

<img src="./images/1e.png" width="700"/>