# Matrix row-reduction

Now that you know how to find the solutions to linear equations by manipulating them, you pretty much know what matrix row reduction is. Matrix row reduction, also called the Gaussian elimination, consists of applying the exact same manipulations except to the rows of a matrix. In order to turn that matrix into a much more simplified form, from which you can extract lots of useful information. Let me show you how. We call them when you want to solve a system of linear equations, say the one with equations, 5a plus b equals 17 and 4a minus 3b equals 6. You first went through an intermediate step of removing the variable a from the bottom equation in order to calculate the value of b. Then you went through a step of replacing the value of b in the first equation in order to get the value of a. The solved system has equation a equals 3 and b equals 2


<img src="./images/Screenshot_2023-05-06_at_10.50.42_AM.png" width="70%" />


Now, what happens if you follow the same procedure but in the matrix of coefficients? Here's the matrix corresponding to the original system and recall that we can forget about the constant 17 and six and only pick up the coefficients 5, 1, 4, and minus 3 and here is the matrix corresponding to the intermediate system. Now you'll see this more in detail later, but for now bear with me. From the original matrix, you can get the matrix in the intermediate system by applying some row manipulations. An important feature of this matrix is that it has ones in the main diagonal and zeros underneath the diagonal. This form of matrix is called row echelon form and finally, some more manipulation will get you to the matrix with ones in the diagonal and zeros everywhere. Why is it the matrix corresponding to the system above? Because you can see the system of equations a equals 3 and b equals 2 as a system of equations, 1a plus 0b equals 3 and 0a plus 1b equals 2, from which this matrix with entries 1, 0, 0, and 1 stems. 

The first matrix, the one in the middle, is called a row echelon form and this one over here is called the reduced row echelon form. 

<img src="./images/Screenshot_2023-05-06_at_10.52.12_AM.png" width="70%" />
<img src="./images/Screenshot_2023-05-06_at_10.52.55_AM.png" width="70%" />

This one will be introduced more later, but for now, let's focus on the row echelon form one as it gives us a lot of useful information of the matrix. Now what happens if you have a singular system of equations such as the one you've seen in the beginning. As you've seen before, this system can be manipulated and turned into this system over here, where the first equation is the same, but the second one is an obvious 0 equals 0. Thus the original matrix can be manipulated and turned into the matrix with entries 1, 1, 0, and 0. This is also a row echelon form. Here's another example from the quiz on the last video. In this system, you have the equations, 5a plus b equals 11 and 10a plus 2b equals 22. Notice that subtracting twice the first equation from the second one, you get the trivial equation, 0 equals 0, indicating that the system is singular. In the matrix we've gone from this one over here with entries 5, 1, 10, and 2 to this one with entries 1, 0.20 and 0, and that one is the row echelon form.

<img src="./images/Screenshot_2023-05-06_at_10.59.11_AM.png" width="70%" />
<img src="./images/Screenshot_2023-05-06_at_10.59.51_AM.png" width="70%" />

## Row Echleon form

Finally, let's look at this very singular system of equation 0 equals 0 and 0 equals 0. The system can not be manipulated any further, so the row echelon form of this matrix is actually itself. The general way that a matrix in row echelon form looks like is the following. On the main diagonal, we have a bunch of ones followed by perhaps a bunch of zeros. You could potentially have all ones, but you could also have all zeros. Below the diagonal, everything is a zero, to the right of the ones any number is allowed and finally to the right of the zeros, everything must be zero. 

<img src="./images/Screenshot_2023-05-06_at_11.03.59_AM.png" width="70%" />
<img src="./images/Screenshot_2023-05-06_at_11.04.10_AM.png" width="70%" />
<img src="./images/Screenshot_2023-05-06_at_11.06.31_AM.png" width="70%" />
<img src="./images/Screenshot_2023-05-06_at_11.07.01_AM.png" width="70%" />

Following these rules in the case of 2 by 2 matrices, only three things may happen. You have 2, 1s in the diagonal. You have 1, 1 in the diagonal or you have 0, 1s in the diagonal. These are the ones you've seen earlier in the video.