---
layout: assignment
title: "Chapter 2 notebook"
---

# Exercises based on Vandermeer and Goldberg
**Due 05 MARCHy**

### 2.1
Given the projection matrix:
$$\begin{bmatrix}
0 & 1 & 4 \\
0.7 & 0 & 0 \\
0 & 0.2 & 0
\end{bmatrix}$$
begin with 10 individuls in the first age class and project the population 15 times. Plot the total population over time. Verbally describe what patterns you may see in the data.

### 2.2
From the data in exercise 2.1, plot the logarithm (your favorite base) of the population density over time.

### 2.3
From the projection in exercise 2.1, plot the population densities of the age categories over time. Compare the pattern with the results of exercise 2.1.

### 2.4
Given the projection matrix
$$\begin{bmatrix}
0   & 3   & 8   & 1 \\
0.7 & 0   & 0   & 0 \\
0   & 0.3 & 0   & 0 \\
0   & 0   & 0.1 & 0
\end{bmatrix}$$
supopose the population is introduced onto an island with 10 of the oldest individuals. Project the population 20 times, and graph the total number over time.

### 2.5
Using the projection matrix in exercise 2.4, suppose the population is introduced onto an island with 10 of the third-oldest age category. Project the population 20 times, and graph the total number over time. Compare to the results of exercise 2.4.

### 2.6
Using the results from exercise 2.5, calculate the ratio of the number of individulas in age category 2 to those in category 2, and plot the ratio over time. Do the same for age categories 4 and 3. What do you notice?

### 2.7
Consider the following projection matrix representing a population with five age classes:
$$\begin{bmatrix}
0 & 5 & 3 & 2 & 1 \\
0.9 & 0 & 0 & 0 & 0 \\
0 & 0.3 & 0 & 0 &  \\
0 & 0 & 0.1 & 0 & 0 \\
0 & 0 & 0 & 0.05 & 0
\end{bmatrix}$$
Begin with a population distributed as 0, 0, 0, 0, 10 individuals respectively across age classes. Project the population 20 times units and plot the total number over time (it's probably easiest to plot density on a logrithmic scale).

### 2.8
Repeat exercise 2.7, but begin with 80, 16, 5, 1, and 1 individuals. Compare the results with the results from exercise 2.7.

### 2.9
Using the projection matrix from exercise 2.4, begin with a population vector of 674, 263, 47, 3 (the stable age distribution), and project the population 10 time units. Plot the natural log of the total population density against time. Then calculate the rate of natural increase from this graph.

### 2.10
### 2.10 (I did it for you)
Using the same projection matrix as in exercise 2.9, multiply the matrix by itsef 10 times. Recall that you estimated the intrinsic rate of natural increase as 0.5603 in exercise 2.9. Verify equation 8 by calculating the vector $\mathbf{N}_{t+1}$ from $\mathbf{P}^{10}\mathbf{N}_t$ and then from $\lambda ^10\mathbf{N}_t$, using the stable age distribution for $\mathbf{N}_t$ and then plotting the two calculations against one another. I have done it below:
```{r, fig.width = 4, fig.height = 4}
proj.mat.n <- proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%proj.mat4%*%N0_2.9
lambda.n <- exp(slope*10)*N0_2.9
plot(x = proj.mat.n, y = lambda.n, las = 1, xlab = "Density using (projection matrix)^n", ylab = "Density using lambda^n", cex = 2, pch = 16)
  lines(x = proj.mat.n, y = lambda.n)
```
As proved in the book, $\mathbf{P}^n\mathbf{N}_t = \lambda ^n\mathbf{N}_t$. **Nothing to do here, but it's needed to evaluate eqn. 8 and for exercise 2.11.**

### 2.11

### 2.12

### 2.13

### 2.14

### 2.15

### 2.16

### 2.17

### 2.18

### 2.19
