# Rank of a Matrix: General Case

Now, just as it happened with two by two matrices, the rank is a measure of how non singular three by three matrices. And its geometric meaning is very similar to that for two by two matrices. Follow along with me and I'll show you how the rank works for larger matrices.

## Rank of a Matrix

So in order to define the rank of a three by three matrix and look at the system of three equations and three unknowns that you've been looking at so far. And let's focus on what equations bring new information to the table. And by not bringing any information to the table, I mean an equation that is already a linear combination of the other equations in the system. 

<img src="./images/Screenshot_2023-06-11_at_7.30.41_PM.png" width="70%" />

### System 1

So in system 1 you can check out all the equations are linearly independent, there's no way to obtain one out of the other two. Therefore the system has three equations and all of them are new pieces of information, so it has three pieces of information. 

<img src="./images/Screenshot_2023-06-11_at_7.31.34_PM.png" width="70%" />

The number of independent equations is the rank, so this system has rank 3 and by convention we say that the matrix has rank 3. 

### System 2

Now let's take a look at system 2, and this can be done in different ways, but one way to look at it is to realize that the second equation is the average of the first and the third. 

<img src="./images/Screenshot_2023-06-11_at_7.32.17_PM.png" width="70%" />

So you can think of the first and the third to be the new pieces of information, and the second one doesn't bring anything new to the table. And if you do this in a different order, you can get different things, but you will always get that there's 3 equations and 2 pieces of information. Because the system has rank 2 and thus the matrix is defined to have rank 2. 

### System 3

System 3 is simpler since the first equation is new, but the second one is twice the first one. So it depends on it and the third one is also three times the first one, so it depends on the first one as well. 

<img src="./images/Screenshot_2023-06-11_at_7.32.35_PM.png" width="70%" />

And so we have three equations and one piece of information, the system therefore has rank 1 and so does the matrix. 

### System 4

And as usual system 4 is the simplest one, no equation brings anything new to the table because no equation tells you anything about a, b and c. 

<img src="./images/Screenshot_2023-06-11_at_7.32.57_PM.png" width="70%" />

So you have 3 equations, 0 piece of information and the matrix has rank 0. There is a question, it seems that calculating the rank is not that easy. So is there a simpler way to calculate the rank? And the answer is yes, and it has to do with the row echelon form for matrix.

## Question

- Is there an easier way to calculate the rank?
- Answer: Yes! It has to do with the row echelon form of the matrix.

