# Linear Dependence and Independence

In this video, I will show you a way to tell if a matrix is singular or non singular directly without having to solve the system of linear equations. But first, let us look back at systems of sentences, recall that a system of sentences is singular if the second sentence carries the same information as the first one. 

<img src="./images/Screenshot_2023-02-12_at_9.50.05_AM.png" width="100%" />

Similarly, a system of equation is singular if the second equation carries the same information as the first one, this is the concept of linear dependence. 

<img src="./images/Screenshot_2023-02-12_at_9.50.12_AM.png" width="100%" />

Let's look back at the two systems of linear equations that you've seen so far with this corresponding matrices and let's focus on the singular system on the right. 

<img src="./images/Screenshot_2023-02-12_at_9.50.29_AM.png" width="100%" />
The reason this system is singular is because the second equation is a multiple of the first one in particular is two times the first one. That means if we take the left hand and the right hand and multiply everything by two in the first equation, you get the second equation. Now, if you look at the corresponding matrix, then the second row is a multiple off the first one.

<img src="./images/Screenshot_2023-02-12_at_9.50.47_AM.png" width="100%" />

And by that we mean that if you take every element in the first row and multiply them all by two, you get the second row. That means that the second row can be obtained from the first one, so the second row is dependent of the first one. 

<img src="./images/Screenshot_2023-02-12_at_9.51.27_AM.png" width="100%" />

Notice that you can also say that the first row is dependent on the second one by taking the second row and multiplying everything by a half. So in any way either one depends on the other one or the other one depends on the one, they're both dependent, so they're linearly dependent. In contrast in the non-singular system on the left, the second equation is not a multiple of the first one, or vice versa.

<img src="./images/Screenshot_2023-02-12_at_9.51.44_AM.png" width="100%" />

There's no constant that I can multiply the first equation to get the second equation or vice-versa. This is why the system is non singular each equation tells you something completely different. So in the corresponding matrix the same thing happens, no row is a multiple of the other one. I cannot take a number and multiply one row entirely by the number to get the other row. That means the rows are linearly independent.

As you may imagine the same thing happens with columns and rows and one can define these concepts of linear dependency between rows and between columns. And they determine the singularity and non singularity of the matrix.