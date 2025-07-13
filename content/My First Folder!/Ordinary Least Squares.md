Good evening everyone. 

Let's consider a set of points in two dimensional space:

$S = \{(x_n, y_n) \mid n \in \{1, 2, \ldots, N\}\}$ 

In an ideal world, there would be a line of the form $y = mx$ where we could align each point. As we are well aware, this is rarely the case.

To solve this problem, we introduce ordinary least squares!

Note that our linear equation will have two parameters. To avoid confusion with letter names, we will label our parameters $\beta_0$ and $\beta_1$  which denote our y-intercept and slope respectively. 

We can then take a line through each point to obtain a singular equation:

  $y = \beta_1 x_i + \beta_0$,  where $i \in [0, n]  (i \in \mathbb{N})$

We will have N of these equations for each $x_i$, since our $\beta$ parameters are representing the parameters for a unique line to fit the inputs, or regressors, $x$.

Writing out the full system of equations leads to a compact matrix formulation:



