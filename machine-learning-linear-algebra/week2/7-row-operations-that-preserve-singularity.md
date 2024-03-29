# Row operations that preserve singularity

Before we get into the whole row reduction process, it is important to note that the same manipulations that you use to solve systems of linear equations can be used in matrices. These are called row operations in a matrix and a very important property that they have is that they preserve the singularity of a matrix. In other words, if you apply them to a singular matrix, you get a singular matrix and if you apply them to a non-singular matrix, you get a non-singular matrix. In this video, you will learn more about these row operations

## Switching Rows

Now the first-row operation that you learn is switching rows. If you switch the positions of the two rows, you get the matrix with entries 4, 3, 5, and 1. 

<img src="./images/Screenshot_2023-05-07_at_9.36.30_AM.png" width="70%" />
<img src="./images/Screenshot_2023-05-07_at_9.37.05_AM.png" width="70%" />


I promise you that's in the original matrix, non-singular, then this one is also non-singular. How do I know this? Well, let's calculate the determinant. The determinant is 4 times 1 minus 3 times 5, which is minus 11, which is different than zero. It's non-singular. In fact, the determinant of the matrix obtained after switching rows like this, it's always a negative of the original determinant. The reason for this is that the diagonals change place so the one you're adding, you're now subtracting, and the one-year or subtracting now you're adding. 

<img src="./images/Screenshot_2023-05-07_at_9.37.33_AM.png" width="70%" />


Now instead of getting 15 minus 4, you get 4 minus 15, hence the minus 11. 

<img src="./images/Screenshot_2023-05-07_at_9.37.43_AM.png" width="70%" />

You can imagine that if the original determinant was a zero, then the resulting one would also be a zero, which means that if you apply this to a singular matrix, you've got a singular matrix. Unlike wise, if the original determinant was not zero, then the resulting was also not zero. Row switching preserves singularity or non-singularity of a matrix.

## Multiplying a row by a (non-zero) scalar

The next operation is multiplying a row by a non-zero scalar. 

<img src="./images/Screenshot_2023-05-07_at_10.29.42_AM.png" width="70%" />


Let's use the same matrix with determinant 11. Now, let's modify the first row. We're going to leave this second row by itself and the first row, we're going to multiply it by a number, say 10, to get 50,10. Now that's going to be the new first row. What's the determinant of the new modified matrix 50, 10, 4, 3? It's this and notice, that it is 10 times 11, 10 times the determinant of the original matrix. 

<img src="./images/Screenshot_2023-05-07_at_10.30.20_AM.png" width="70%" />

Because in each of the diagonals, you have taken exactly one element, the one on the top row, and multiplied it by 10 so the whole thing gets multiplied by 10. Now notice that the scalar has to be non-zero. In the scalar that 10 is non-zero, then this operation turns a non-zero determinant into non-zero determinant and a zero determinant into a zero determinant. Thus, this operation also preserves singularity and non-singularity

## Adding a row to another row

The final operation is to take a row and add it to another row,

<img src="./images/Screenshot_2023-05-07_at_2.19.53_PM.png" width="70%" />

for example, let's take the sum of the first and the second row, and that is 9, 4, so 9, 4 is going to be the top one of the rows in the matrix, and the bottom one is going to be the same. 

<img src="./images/Screenshot_2023-05-07_at_2.20.21_PM.png" width="70%" />

This new determinant is 9 times 3 minus 4 times 4, which is actually 11. 

<img src="./images/Screenshot_2023-05-07_at_2.21.02_PM.png" width="70%" />

Believe it or not, when you do this, you get the same determinant as the beginning. 

<img src="./images/Screenshot_2023-05-07_at_2.21.07_PM.png" width="70%" />

Proving this is slightly harder and you can find it in a written tandem in the resources of the class. But the most important part is that since the determinant stays the same after this operation, then this operation also preserves singularity and non-singularity just like the other ones.