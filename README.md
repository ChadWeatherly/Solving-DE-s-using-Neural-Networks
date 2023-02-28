# Solving Differential Equations using Neural Networks

As part of an undergraduate research course, I spent a semester working briefly on solving First-Order Differential Equations (ODE's) using neural networks. We found that since neural networks are universal approximators, they were able to successfully mimic the analytical solution and with much lower error than Euler's method, and once trained, were computationally efficient.

Here are some results for 1st-order ODE's:

$df / dt = -0.23 * f(t)$

$f_0 = 2$

![ode-1](nn-ode-1.png)

Logistic Differential Equation

$df / dt = f(t) (1 - f(t))$

$f_0 = 10$

![ode-2](nn-ode-2.png)

$y = -2xy$

$f_0 = 1$

![ode-3](nn-ode-3.png)


