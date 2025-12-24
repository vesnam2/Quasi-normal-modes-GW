## Quasi-Normal Modes of a Scalar Field on a Schwarzschild Black Hole

This repository contains the code developed during a summer school (Petnica Summer Institute) project focused on the **time-domain evolution of a scalar field propagating on a Schwarzschild black hole background.**

The project studies quasi-normal modes (QNMs), which describe the characteristic damped oscillations arising from perturbations of black holes. These modes are important in black hole perturbation theory and gravitational-wave physics.

## Background

Starting from the covariant wave equation for a scalar field on a curved spacetime, the problem is specialized to the Schwarzschild metric. After performing a spherical harmonic decomposition, the dynamics reduce to a 1+1 dimensional wave equation in the tortoise coordinate with an effective potential.

The numerical evolution is performed in the time domain using finite-difference methods, allowing the study of:

- Wave propagation near the event horizon
- Absorbing boundary conditions
- Late-time ringdown behavior
- Extraction and fitting of quasi-normal mode frequencies and damping times

## Features

Time-domain integration of the scalar wave equation

Implementation of tortoise coordinates

Gaussian initial perturbations

Visualization of wave evolution

Fitting of quasi-normal modes with damped sinusoids

## Goals

Understand black hole perturbations in a simplified (scalar) setting

Observe quasi-normal ringing and decay

Numerically extract QNM parameters

Build intuition relevant for gravitational perturbations (Regge–Wheeler / Zerilli equations)

## Technologies

Python

NumPy / SciPy

Matplotlib
