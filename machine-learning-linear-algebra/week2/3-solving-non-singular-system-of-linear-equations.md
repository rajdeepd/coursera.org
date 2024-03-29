# Solving non-singular system of linear equations

You are now ready to learn something that has been lurking yet present in the previous lessons. 

## Solving system of Equations


In one of the first quizzes, you took a system of linear equations and found solution. In general, this is hard to do by simply looking at the equations. However, there exists a simple way to do this. In this video, you will learn a method or an algorithm that helps you find the solution to a system of linear equations and that is also able to tell you if the system is singular or non-singular. 

First, let's go back to how you solve the first system of equations. 

<img src="./images/Screenshot_2023-03-19_at_12.59.18_PM.png" width="80%" />

The one with equations a plus b equals 10, and a plus 2b equals 12. 

<img src="./images/Screenshot_2023-03-19_at_12.59.34_PM.png" width="70%" />

<img src="./images/Screenshot_2023-03-19_at_12.59.27_PM.png" width="70%" />

Recall that the scenario was that an apple and a banana cost 10 and an apple and two bananas cost 12. 

You figured out that since the second day you bought an extra banana, paid two more, then the extra banana must cost two. 

<img src="./images/Screenshot_2023-03-19_at_1.01.58_PM.png" width="70%" />

From this, and the fact that they both cost 10, you concluded that the apple must cost eight. Thus you went from the original system of equations to a solved system. One that is still a system of equations except that the equations are a equals 8 and b equals 2. 

The solved system is much simpler because each equation actually tells us the value of each of the variables. The goal is to take every system and turn it into a solved system. That is, if the system is non-singular and has exactly one solution. Now in order to get from the system to the solve system, you followed some process. This processes required manipulating the equations. Without noticing what you actually did in your head was to follow a specific process that involves manipulating, such as swapping equations, adding them, multiplying them by constants.

In this video, you'll see what this means more in detail. The first step in order to go from a system to a solved system is the following. Notice that in the system in the left, the equations both have a and b on them. You'd like to get to one in which the a and the b are isolated and they only appear in one equation each. The first step will be to look at the second equation and try to eliminate the variable a from it. But before you do that, it's important to know how one can manipulate equations. That is, take some linear equations and produce some other ones that are still true based on the original ones. One way to manipulate equations is to multiply them by a constant. For example, if an apple and a banana cost $10, how much would seven apples and seven bananas cost? Well, the answer is $70, as this is 7 times 10.

<img src="./images/Screenshot_2023-03-19_at_1.02.08_PM.png" width="70%" />

Equation a plus b equals 10 can be multiplied by 7 on both sides to get the equation 7a plus 7b equals 70. 

<img src="./images/Screenshot_2023-03-19_at_1.02.23_PM.png" width="70%" />

These equations carry the exact same information. Thus, the first one is true so is the second. Another way to manipulate equations is to add two equations. For example, if an apple and a banana cost $10 and two apples and three bananas cost $26, then how much are three apples and four bananas? Well, if you add these two equations, you get the 3 apples plus 4 bananas is equal to 32. If the two first equations are true, and so is there sum. 

--

Now I'll show you how to solve a harder system of equation in order for you to see how these manipulations are used. Here's a system of equations that you'll learn to solve. 

<img src="./images/Screenshot_2023-03-19_at_1.02.35_PM.png" width="70%" />

The equations are 5a plus b equals 17 and 4a minus 3b equals 6, and recall that your first goal in order to get to a solved system is to try to eliminate the variable a from the second equation in order to leave b by itself. The first step is not always necessary, but it will make your life easier. 

<img src="./images/Screenshot_2023-03-19_at_1.02.45_PM.png" width="70%" />

The step is to divide each equation by the coefficient of a in order for both of them to have a coefficient of one beside the a. If we do this, then new equations are a plus 0.2b equals 3.4, and a minus 0.75b equals 1.5. As you saw before, these are equivalent to the first two because all we did was multiply the entire equation left and right by a constant. 

<img src="./images/Screenshot_2023-03-19_at_1.02.51_PM.png" width="70%" />

Now in order to remove a from the second equation, one way is to subtract the first equation from the second one. Like this; we take the second equation, we subtract the first one, and we can do this component-wise, a minus a is 0a, minus 0.75b minus 0.2b is minus 0.95b and 1.5 minus 3.4 is minus 1.9. The resulting equation is minus 0.95b is equal to minus 1.9. Now we can divide by minus 0.95 at both sides to get that b is equal to 2. You have succeeded. You have found the value of b. In other words, you removed a from the first equation to get b equals 2 in your solved system. Now that you know that b equals 2, you can simply plug that into the first equation. The first equation says a plus 0.2b is 3.4, so a plus 0.2 times 2 is equal to 3.40. 0.2 times 2 is 0.4, so we have a plus 0.4 equals 3.4 and subtracting 0.4 from both sides, you get that a is equal to 3, and that is the value of the second variable. In a nutshell, that is how you solve a system of two equations and two variables. Now here's a small caveat. 



## What if one of the coefficients of a is zero?

<img src="./images/Screenshot_2023-03-19_at_1.04.07_PM.png" width="70%" />

Imagine that you are solving this new system with equations 5a plus b equals 17 and 3b equals 6, and you'd like to eliminate a from this equation. The first step is to divide both by the coefficient of a. For the first equation, this goes exactly as before. However, for the second equation, the coefficient of a is zero and you can't divide by zero. 

<img src="./images/Screenshot_2023-03-19_at_1.03.10_PM.png" width="70%" />

Are we doomed? Well, actually the doom turns into good luck. Check it out.

<img src="./images/Screenshot_2023-03-19_at_1.03.17_PM.png" width="70%" />

The equation says 3b equals 6. It already has a eliminated from it and actually implies that b is equal to 2 if you divide by 3 on both sides. 

<img src="./images/Screenshot_2023-03-19_at_1.05.47_PM.png" width="70%" />


This is the value of b already, and the second equation is already solved in the system.

<img src="./images/Screenshot_2023-03-19_at_1.08.14_PM.png" width="70%" />

In order to solve the first one, you proceed to do the same thing, replace on the first equation that b equals 2, get that a is equal to three, and bring it back as a solution. You're now ready for a quiz. Solve the following system of equations, 2a plus 5b equals 46 and 8a plus b equals 32. The solution to the system is a equals 3 and b equals 8. I invite you to verify that those values actually work for the equations.

## Quiz

<img src="./images/Screenshot_2023-03-19_at_1.08.02_PM.png" width="70%" />

<img src="./images/Screenshot_2023-03-19_at_1.05.58_PM.png" width="70%" />















