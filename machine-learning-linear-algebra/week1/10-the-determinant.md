# The determinant

Now it turns out that there is a much faster way to tell if a matrix is singular or non singular and in this video you will learn it. It's called the determinant and it is a quick formula that returns a 0 if the matrix is singular and a number different from 0 if the matrix is non singular. Take a look back at the matrix in the previous example and let's focus on the singular matrix on the right. In this matrix, you can multiply the first row by 2 to obtain the second row, and therefore the rows are linearly dependent. In contrast for the non singular matrix on the left, there's no number that you can multiply the first row by to get the second row because the rows are linearly independent. 

<img src="./images/Screenshot_2023-02-12_at_8.34.33_PM.png" width="100%" />

Let us look at this more carefully, the matrix has entries a, b, c, and d then the matrix is singular. 

<img src="./images/Screenshot_2023-02-12_at_8.35.13_PM.png" width="100%" />

If there exists a number k for which the first row times k is equal to the second row, that means ak equal c, and bk equals d for the same value of k. This is equivalent to c over a equals d over b equals k and that's the same thing, forgetting about k, that ad is equal to bc or equivalently ad minus bc equals 0. 

<img src="./images/Screenshot_2023-02-12_at_8.40.01_PM.png" width="100%" />
<img src="./images/Screenshot_2023-02-12_at_8.40.50_PM.png" width="100%" />

This value of ad minus bc is very important, we're going to call it the determinant of the matrix, so the determinant of the matrix is ad minus bc. And by construction this determinant is 0 if the matrix is singular and non 0 if it's non singular.

Now way I like to look at the determinant is like this, ad is the product of the numbers in the main diagonal and bc Is the product of the numbers in the anti diagonal.

## Determinant and Singularity

So let's calculate the determinants of these two matrices in the ongoing example and see what you get. The first matrix has determinant 1 times 2 minus 1 times 1 which is 1 and the second one 1 times 2 minus 2 times 1 which is 0. So notice that the first matrix, which is non singular, has a determinant of one which is non 0, and the second matrix which is singular, has a determinant of 0. This is no coincidence this is always going to be the case, non singular matrices have non 0 determinants, they don't need to be 1 but they're non 0 and singular matrices have 0 determinant. To summarize the determinant of a matrix with entries a, b, c, and d is ad minus bc and it is 0 precisely when the matrix is singular and non 0 when the matrix is non singular. 

## Quiz

<img src="./images/Screenshot_2023-02-12_at_8.41.05_PM.png" width="100%" />

o now you're ready for a quiz in problem 1, you have two matrices and you're asked to find their determinants. And in problem 2, determine if the matrices are singular on non singular based on the results of problem 1. 

## Solution

And the answers are for the first matrix, the product of the terms in the main diagonal is 5 times 3 which is 15.

<img src="./images/Screenshot_2023-02-12_at_8.44.39_PM.png" width="100%" />

The practical terms in the main anti diagonal is 1 times minus 1, which is minus 1, and the difference is 15 minus, minus 1, which is 15 plus one, which is 16. Since the determinant is different from 0 than the matrix is non singular. For the second matrix determinants is 2 times 3 minus 1 times minus 6, so the 3 minuses that's one minus, so the determinant is 6 minus 6, which is precisely 0. Since the determinant is 0, then the matrix is singular.