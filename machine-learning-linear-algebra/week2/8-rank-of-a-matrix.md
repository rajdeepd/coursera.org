# Rank of a Matrix

## Introduction

Throughout the last few videos, there has been a concept that you've seen yet still have not been formally introduced to.




## Image Compression - Reducing Ranks

It is the notion of the rank of a matrix which in some way measures how much information that matrix or its corresponding system linear equations is carrying. Follow along with me and see how to define and calculate the rank. One great application of ranking machine learning is an image compression. 

<img src="./images/Screenshot_2023-05-14_at_2.34.46_PM.png" width="70%" />



Take a look at this image, it's very crisp, but it also uses a lot of storage because every pixel intensity has to be stored as a number. Could you store this image or perhaps a slightly blurrier version of it using significantly less space. 

<img src="./images/Screenshot_2023-05-14_at_2.38.13_PM.png" width="70%" />

The answer is yes. And this is the main topic of this video which is the rank of a matrix. It turns out that pixelated images are matrices and the rank of matrix is related to the amount of space that is needed to store that corresponding image. This particular image has ranked 200, which is quite high. There's a very powerful technique on singular value decomposition or SVD in short, which can reduce the rank of a matrix while changing it as little as possible. You can see as video applied here to reduce a heavy image of ranked 200 into images of rank 1, 2, 5, 15 and 50. Notice how the images of rank 15 and 50 are very similar to the original and we take a lot less space to store. So recall that in systems of sentences, there was a notion of how much information the system carried

## System of Information

Let's look at three systems of sentences. System 1, with sentences, the dog is black and the cat is orange. System 2 with sentences, the dog is black and the dog is black. 

<img src="./images/Screenshot_2023-05-14_at_2.45.38_PM.png" width="70%" />

And system 3 with sentences the dog and the dog notice that system 1 has two sentences and it carries two pieces of information. System 2 also has two sentences, but they're the same. So this system carries only one piece of information and system 3, well, it has two sentences, but it carries no information regarding the color of the animals. So it carries zero pieces of information, recall that your goal is to determine the color. So the amount of information a system of sentences carries is defined as the rank of the system. The system 1 has ranked 2, system 2 has ranked 1 and system 3 has ranked 0. 


## System of Equations

Next you'll see how this notion applies to matrices and this corresponding systems of linear equations. Now, let's go back to the three systems of equations from the previous videos. As you've already seen, the first system has two equations and each equation brings something new to the table. Some new piece of information. That's why you're able to narrow down the solutions to one point. The first equation narrows down to a line and the second one narrows them down to a point that the system has two pieces of information. This is how the rank of the system is defined. So the rank is 2, the second system has two equations, but recall that the second equation was the same as the first one. Therefore the system really only carries one piece of information which is the first equation. This is why you're able to narrow down the set of solutions to a line, but that's as far as you can get. Thus, the rank of the system is defined as one, and finally the third system has two equations. But they carry no information as any number a and b satisfy these equations. Does the system carries zero pieces of information and its rank is defined to be 0. 

<img src="./images/Screenshot_2023-05-14_at_2.46.25_PM.png" width="70%" />

And now on to define the rank of matrix, since its system of information has a corresponding matrix and the rank of the matrix is defined as the rank of the corresponding system of equations. Thus the matrix corresponding to the first system has ranked 2. The one corresponding to the second system has ranked 1, and the one corresponding to the third system has ranked 0. 

## Rank and solutions to the System

Now there's a special relationship between the rank of a matrix and its solution space. 

<img src="./images/Screenshot_2023-05-14_at_2.48.31_PM.png" width="70%" />

Recall that the solution space for each of these matrices is the set of solutions to the system of equations when the constants are zero. So for the first one recall that the solutions are only a=0 and b=0. So that's a point and the dimensional solution space is 0 because the dimension of a point is 0. For the second one, the set of solutions was some line and a line has dimension 1. So the dimension of the solution space was 1. And for the third one, well every a and b works here because any point a and b is a solution to that system. Therefore the solution space is a plane and it has dimension 2. So what happens here in all three cases is that the rank is equal to 2. 

## Rank of a Matrix

<img src="./images/Screenshot_2023-05-14_at_2.54.08_PM.png" width="70%" />

The number of rows in the matrix minus the dimension of the solution space. This is always the case for 2 by 2 matrix. And in general, as you'll see later, this rank and solution space always and then dimensional solution always add to the number of rows in the matrix. 

## Rank and Singularity


<img src="./images/Screenshot_2023-05-14_at_3.21.30_PM.png" width="70%" />

Notice also the first matrix is non-singular and the other two are singular. So a matrix is non-singular if and only if it has full rank, namely if the rank is equal to the number of rows. This is the same as saying that a system of equations is non-singular if it carries as many pieces of information as equations it has, meaning that you carry the maximum amount of information possible. Thus that this equation brings a new piece of information to the table and there's no redundancy between equations. 

## Quiz

<img src="./images/Screenshot_2023-05-14_at_3.22.32_PM.png" width="70%" />

And now you're ready for a quiz for this quiz, please determine the rank of the same two matrices you've seen recently and the solutions are in. 
<img src="./images/Screenshot_2023-05-14_at_3.22.52_PM.png" width="70%" />

<img src="./images/Screenshot_2023-05-14_at_3.23.08_PM.png" width="70%" />
<img src="./images/Screenshot_2023-05-14_at_3.23.21_PM.png" width="70%" />
<img src="./images/Screenshot_2023-05-14_at_3.23.34_PM.png" width="70%" />
<img src="./images/Screenshot_2023-05-14_at_3.23.53_PM.png" width="70%" />
<img src="./images/Screenshot_2023-05-14_at_3.24.08_PM.png" width="70%" />

So since the first one has a solution space of dimension 0, the rank is 2, and the second one has a solution space of dimension 1, so the rank is 1. Notice that the first matrix is non-singular and the second one is singular.