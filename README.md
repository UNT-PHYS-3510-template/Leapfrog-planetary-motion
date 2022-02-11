# Leapfrog algorithm and Planetary Motion
Assignment 1: In the leapfrog.ipynb Jupyter notebook or in a separate Python file, use the leapfrog ODE solver to check energy conservation on a simple harmonic oscillator. 
* Implement the differential equations to describe the motion of a simple harmonic oscillator. Implement them so that they can be used by either Euler, RK, or Leapfrog ODE solvers. 
* Compare the tajectory in phase space (plot $v$ vs. $x$) for the simple harmonic oscillator by using Leapfrog or a Runge Kutta algorithm.   
* Compare the total energy for the simple harmonic oscillator by using Leapfrog or a Runge Kutta algorithm.   

Assignment 2: In the asteroids.ipynb Jupyter notebook or in a separate Python file, simulate the motion of an asteroid orbiting the fourth Lagrange point of the Sun-Jupiter system.
* Following the example of the restricted three-body program of the textbook (Eqs. 4.56 and 4.57, Program 4.7) implement the equations of motion for the satellite in the presence of the Sun-Jupiter system. 
* Setup the correct units for the program and for the satellite. Find a set of initial conditions for the satellite to stay on a planar orbit around the L4 point. Use the appropriate ODE solver for the simulation.
* (Optional) Implement a more general 3D simulation of the three body problem, where the three objects can move according to Newton's law and gravitational forces. Using the initial conditions determined in the previous step, simulate the motion of the system in 3D. 