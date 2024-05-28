# Module Instruction:
Part 1: Numerical Method in PDE
Part 2: Gaussian Kernel Regression and Bayesian Optimization
Part 3: Monte Carlo Simulation
Part 4: Optimization

## Problem Set

### Part 1:Numerical Solving 3D Broadwell Equations:

#### 1.1 Problem
Consider the following 3D equations defined on $\Omega=(0,1)\times(0,1)\times(0,1)$:

$$\frac{\partial{F_1}}{\partial{x}}=\sigma(\frac{1}{6}\sum_{i=1}^{6}F_i-F_1)$$

$$-\frac{\partial{F_2}}{\partial{x}}=\sigma(\frac{1}{6}\sum_{i=1}^{6}F_i-F_2)$$

$$\frac{\partial{F_3}}{\partial{y}}=\sigma(\frac{1}{6}\sum_{i=1}^{6}F_i-F_3)$$

$$-\frac{\partial{F_4}}{\partial{y}}=\sigma(\frac{1}{6}\sum_{i=1}^{6}F_i-F_4)$$

$$\frac{\partial{F_5}}{\partial{z}}=\sigma(\frac{1}{6}\sum_{i=1}^{6}F_i-F_5)$$

$$-\frac{\partial{F_6}}{\partial{z}}=\sigma(\frac{1}{6}\sum_{i=1}^{6}F_i-F_6)$$

The boundary conditions are:

$$F_1(-1,y,z)=F_b(y,z),\quad F_3(x,-1,z)=F_b(x,z),\quad F_5(x,y,-1)=F_b(x,y)$$

$$F_2(1,y,z)=F_4(x,1,z)=F_6(x,y,1)=0$$

Where:

$$
F_b(p,q)=\begin{cases}
    1, & \text{if } |p|\le 0.2 \text{  and  } |q| \le 0.2 \\
    0, & \text{otherwise}
\end{cases}
$$

Solve this system of equations numerically for $\sigma=0.1,1,10,100$

#### 1.2 Numerical Scheme and Result

Please refer to the PDF report in Part 1


### Part 2: Kernel Regression and Bayesian Optimization

### Part 4:Optimization

#### Q1: Geometric Programming
A monomial is a function $f:R^n \rightarrow R$ of the following form:
$$f(x_1,x_2,...,x_n)=c_1x_1^{a_1}x_2^{a_2}...x_n^{a_n}$$
Here $x_i>0,a_i \in R, c>0$

#### Q2:Compressed Sensing

$$
\min_X\quad||X||_*
$$
