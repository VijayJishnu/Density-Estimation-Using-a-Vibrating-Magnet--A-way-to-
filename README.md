# Density-Estimation-Using-a-Vibrating-Magnet--A-way-to-reinterpretation
A method for estimating medium density using the frequency response of a vibrating magnet, modeled through geometry-dependent added mass and fluid–structure coupling.This work was developed independently and aims to pave the base for An effective model or reinterpretation of known physics
Overview
This repository presents an independent derivation and formulation of a method to estimate the density of a fluid using the change in oscillation period of a vibrating magnet.
When a rigid body oscillates in a fluid, it must accelerate a portion of the surrounding medium. This produces an effective increase in inertia, commonly known as added mass. The present work expresses this effect using a geometry-dependent coupling parameter and derives a simple relation between oscillation period and fluid density.
The formulation is intended for educational, analytical, and experimental use.

Physical Principle
A magnet oscillating in the Earth's magnetic field has a time period
[T = 2\pi \sqrt{\frac{I}{M B_h}},]
where
(I) — moment of inertia
(M) — magnetic moment
(B_h) — horizontal component of Earth’s magnetic field
When the magnet is immersed in a fluid, it entrains part of the surrounding medium. This increases its effective inertia and hence the oscillation period.

Effective Mass Model
The fluid contribution is modeled as
[m^* = m + n m_f]
where:
(m) = magnet mass
(m_f = \rho_f V) = mass of displaced fluid
(n) = dimensionless geometry-dependent coupling coefficient
The effective moment of inertia becomes:
[I^* = \frac{m^*(l^2 + b^2)}{12}]

Period Relation
Since the restoring magnetic torque remains unchanged:
[\frac{T_f^2}{T_{air}^2} = \frac{I^*}{I}]
which gives
[\frac{T_f^2}{T_{air}^2}
= 1 + n \frac{\rho_f}{\rho_m}]

Density Formula
Direct form
[\rho_f =
\left(\frac{T_f^2}{T_{air}^2} - 1\right)
\frac{\rho_m}{n}]

Reference-liquid elimination (recommended)
Using a known reference fluid:
[
\rho_{unknown}
= \frac{T_{unknown}^2 - T_{air}^2}
{T_{ref}^2 - T_{air}^2}
, \rho_{ref}
]
This version depends only on measured time periods.

Physical Interpretation
The parameter n represents hydrodynamic (added-mass) coupling.
It depends on geometry and flow configuration.
The formulation is consistent with the inertial term of the Navier–Stokes equations.
The approach is equivalent to classical added-mass theory but presented here in a compact, experimentally accessible form.

Applications
Density measurement of liquids
Undergraduate physics experiments
Demonstration of fluid–structure interaction
Oscillatory sensor modeling
Educational demonstrations of added mass

Assumptions
Small-amplitude oscillations
Weak damping
Incompressible fluid
Linear response regime
Constant geometry

References
H. Lamb, Hydrodynamics, Cambridge University Press (1932).
L. D. Landau & E. M. Lifshitz, Fluid Mechanics, Pergamon Press (1987).
G. K. Batchelor, An Introduction to Fluid Dynamics, Cambridge University Press (1967).
T. Sarpkaya & M. Isaacson, Mechanics of Wave Forces on Offshore Structures, Van Nostrand Reinhold (1981).
C. E. Brennen, Fundamentals of Multiphase Flow, Cambridge University Press (2005).

Notes on Originality
This work was derived independently and later recognized to be consistent with the classical concept of added mass in fluid mechanics. The contribution lies in its formulation for a vibrating-magnet system and its direct application to density estimation
