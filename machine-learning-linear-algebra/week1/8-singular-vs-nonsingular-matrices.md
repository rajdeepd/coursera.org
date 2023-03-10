# Singular vs Non Singular Matrices

So, now that you know that the constants in the system of linear equations are not important in order to determine if the system is singular or non-singular, you're about to jump into one of the most important and fundamental objects of linear algebra, the matrix. 

<img src="./images/Screenshot_2023-02-12_at_9.39.20_AM.png" width="100%" />

Matrices have lots of very important properties and they arise from many different places in math. In this case, they will arise from the coefficients in the systems of equations in a very natural way. Let us go back to the two systems of equations you previously saw. Recall that systems 2 and 3 collapse into one system when you turn the constants into zero. Now, since the constants are zero, you can forget about them. If you take the coefficients of a and b and now put them in a two by two shaped box, which is called an array or a matrix. That's the matrix corresponding to the system. So, the matrix corresponding to the first system is the one with entries 1 1 1, and 2. Why these numbers? Because the first equation, a+b can be considered the equation 1 times a plus 1 times b does the 1 and the 1. And equation, a+2b can be considered the equation 1 times a plus 2 times b does the 1 and the 2. So, in this matrix, each row corresponds to each equation and each column to the coefficient of each one of the variables. In this case, a for the left column and b for the second column.

<img src="./images/Screenshot_2023-02-12_at_9.39.52_AM.png" width="100%" />

Similarly, the matrix corresponding to the second system is this one with entries 1 1 2, and 2. So, a matrix simply an array of numbers inside a rectangle. These ones are simple as they're in a two by two rectangle. 

<img src="./images/Screenshot_2023-02-12_at_9.41.38_AM.png" width="100%" />

But later in the course, you're going to see larger matrices. And matrices just like systems of linear equations can also be singular or non-singular. Since the first system is non-singular because it has a unique solution, then we say that its corresponding matrix is non-singular. And since the second system is singular, as it has infinitely many solutions, we say that its corresponding matrix is singular. Of course, there are quicker ways to tell if the matrix is singular or non-singular. We have without having to find the solutions to its corresponding systems of equations, as you will see in the next video.