# Space Probe Simulator

A physics engine-based simulator designed to model and optimize a space mission to Saturn's moon, Titan. This project integrates numerical methods, control systems, and trajectory planning to simulate the mission from Earth to Titan and back, ensuring fuel efficiency and safe landing.

## Features

* Trajectory Simulation: Simulates the probe's journey through the solar system using numerical ODE solvers:

  * Euler Method
  * Runge-Kutta Method (4th Order)
  * Verlet Method

* Closed-Loop Control: Implements a PID-based controller to stabilize and guide the lander during descent on Titan.

* Wind Modeling: Simulates Titan's stochastic wind patterns for realistic landing conditions.

* Graphical User Interface: Visualizes the solar system, trajectory, and landing using JavaFX.

## Required Software

* Java SE 8 (recommended, as it comes with JafaFX) or higher
* JavaFX (can be installed from https://openjfx.io) [Note: Separate install of JavaFX requied for Java SE versions != 8]

## Usage

* Launch the simulation by running `App.java`
* Use the GUI controls to:
  * Navigate between celestial body views
  * Adjust simulation speed

## Contributors

- Benjamin Gauthier
- Gunda Karnite
- Simon Köhl
- Hemachandra Konduru
- Michelle Lear
