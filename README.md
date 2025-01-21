# Chaos and Conservation: Evaluating Integrators for the Three-Body Problem
The complex and chaotic nature of the gravitational three body problem allows us to gain valuable insight into different integration schemes. By implementing integrators for the three body problem, we can evaluate errors and show how symplectic integrators locally conserve energy. However, we see that higher order methods implemented in routines like ode78, while not preserving H(p,q), naturally, give the most accurate trajectories.
