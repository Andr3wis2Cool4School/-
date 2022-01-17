# Notes one

## The column Space of a Matrix

**A Matrix**: just a square or a rectangle of numbers.

$$A_0 = \begin{bmatrix}
  1 & 3 & 2 \\
  4 & 12 & 2 \\
  2 & 6 & 4 
  \end{bmatrix}$$ 

>All the rows are in the same direction. row are times.
>All the columns are in the same direction. columns are times.

---

$$A_1 = \begin{bmatrix}
        1 & 4 & 2 \\
        4 & 1 & 3 \\
        5 & 5 & 5
        \end{bmatrix}$$

Add row 1 and row 2 will get row 3.

> Here we see this is a matrix of rank two. 


A side note: **Rank (秩)**


## Column space of $A$ / All combinations of columns

**Matrix $\times Vectors$**

$$Ax = \begin{bmatrix}
       1 & 4 & 5 \\
       3 & 2 & 5 \\
       2 & 1 & 3
       \end{bmatrix} \begin{bmatrix}
                      x_1 \\
                      x_2 \\
                      x_3 
                      \end{bmatrix} = \begin{bmatrix} 
                                       1 \\
                                       3 \\
                                       2 \end{bmatrix} x_1 + \begin{bmatrix}
                                                             4 \\
                                                             2 \\
                                                             1 \end{bmatrix}x_2 + 
                                                             \begin{bmatrix}
                                                             5 \\
                                                             5 \\
                                                             3 \end{bmatrix}x_3$$ 

This is the **Linear combination** of columns of $A$.