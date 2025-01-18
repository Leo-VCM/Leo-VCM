Particle Swarm Optimization (PSO)
This is a Python implementation of the Particle Swarm Optimization (PSO) algorithm. In computational intelligence, PSO is a method used to optimize an objective function. It is a stochastic search method, which, unlike many other optimization algorithms, does not compute gradients. PSO is commonly applied to problems where the variables take uniform values.

Linear Regression Gradient Descent
Variables
A few variables need to be initialized at the beginning of the algorithm:

n_pop: Population count
max_iter: Maximum number of iterations
v_max: Maximum velocity value
x(i): The particle's position
v(i): The particle's velocity
p(i): The particle's best position found so far
f(i): The particle's best function value found so far
s_best: The position of the best particle in the swarm
s_fbest: The best function value of the best particle in the swarm
f_best: The best objective value of the function
The best objective value of the function is not always present and is not used in all variations of the algorithm.

How It Works
PSO works by iteratively improving a candidate solution from a population of particles (swarm) by moving these particles around. Each particle is aware of its best position in the search space, and the best position found by the swarm is also known. Based on these assumptions, the swarm is expected to move toward the best solutions (positions). To update the position of each particle, the following formula is used:
