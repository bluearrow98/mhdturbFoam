# mhdturbFoam
An incompressible, turbulent OpenFOAM solver for magnetohydrodynamic flows

1. This file needs to be copied to the solver directory inside electromagnetics sub-folder.
2. Once copied, compile the solver and it is ready to use.

Note: This is a transient solver for MHD turbulent flow with only minor changes to mhdFoam. For certain problems, use of the solver can become very time consuming. People are more than welcome to make changes to the solver and make a steady state solver for it. This would really save a lot of time!
Also do take note of the fact that while using this solver, even the turbulence model needs to be changed. MHD flows require different turbulence models. There are many literatures available online about them. I used Modified Spalart-Allmaras model :

Jean-Fran-atilde, Dietiker, ois, & Hoffmann, K. A. (2003). Modified One-Equation Turbulence Models for Turbulent Magnetohydrodynamic Flows. Journal of Thermophysics and Heat Transfer, 17(4), 509-520. Doi: 10.2514/2.6796
