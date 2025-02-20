
# ND Pyomo Cookbook

**ND Pyomo Cookbook** is a collection of notebooks showing how to use [Pyomo](http://www.pyomo.org/) to solve
modeling and optimization problems. With Pyomo, one can embed within Python an optimization model consisting of
**decision variables**, **constraints**, and an optimization **objective**. A rich set of features enables the modeling
and analysis of complex systems.

The notebooks in this collection were developed for instructional purposes at Notre Dame. Originally
developed using the [Anaconda distribution of Python](https://www.anaconda.com/download/), the notebooks have been
updated to open directly [Google Colaboratory](https://colab.research.google.com/) where they can be run using
only a browser window.

PyomoFest at Notre Dame was held June 5-7, 2018. This repository contains the 
[agenda](https://github.com/jckantor/ND-Pyomo-Cookbook/tree/master/PyomoFest/PyomoFest.md), 
[slides](https://github.com/jckantor/ND-Pyomo-Cookbook/tree/master/PyomoFest/slides) and
[exercises](https://github.com/jckantor/ND-Pyomo-Cookbook/tree/master/PyomoFest/exercises_wo_soln/exercises)
distributed during that event.

### [Table of Contents](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/toc.ipynb?flush=true)
### [Keyword Index](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/index.ipynb?flush=true)
### [Chapter 1. Getting Started with Pyomo](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/01.00-Getting-Started-with-Pyomo.ipynb)
- [1.1 Installing a Pyomo/Python Development Environment](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/01.01-Installing-Pyomo.ipynb)
- [1.2 Running Pyomo on Google Colab](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/01.02-Running-Pyomo-on-Google-Colab.ipynb)
- [1.3 Running Pyomo on the Notre Dame CRC Cluster](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/01.03-Running-Pyomo-on-the-Notre-Dame-CRC-Cluster.ipynb)
- [1.4 Cross-Platform Installation of Pyomo and Solvers](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/01.04-Cross-Platform-Installation-of-Pyomo-and-Solvers.ipynb)

### [Chapter 2. Linear Programming](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/02.00-Linear-Programming.ipynb)
- [2.1 Production Models with Linear Constraints](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/02.01-Production-Models-with-Linear-Constraints.ipynb)
- [2.2 Linear Blending Problem](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/02.02-Linear-Blending-Problem.ipynb)
- [2.3 Design of a Cold Weather Fuel for a Camping Stove](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/02.03-Mixture-Design-Cold-Weather-Fuel.ipynb)
- [2.4 Gasoline Blending](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/02.04-Gasoline-Blending.ipynb)
- [2.5 Model Predictive Control of a Double Integrator](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/02.05-Model-Predictive-Control-of-a-Double-Integrator.ipynb)

### [Chapter 3. Assignment Problems](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/03.00-Assignment-Problems.ipynb)
- [3.1 Transportation Networks](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/03.01-Transportation-Networks.ipynb)

### [Chapter 4. Scheduling with Disjunctive Constraints](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/04.00-Scheduling-with-Disjunctive-Constraints.ipynb)
- [4.1 Machine Bottleneck](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/04.01-Machine-Bottleneck.ipynb)
- [4.2 Job Shop Scheduling](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/04.02-Job-Shop-Scheduling.ipynb)
- [4.3 Maintenance Planning](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/04.03-Maintenance-Planning.ipynb)
- [4.4 Scheduling Multipurpose Batch Processes using State-Task Networks](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/04.04-Scheduling-Multipurpose-Batch-Processes-using-State-Task_Networks.ipynb)

### [Chapter 5. Simulation](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/05.00-Simulation.ipynb)
- [5.1 Response of a First Order System to Step and Square Wave Inputs](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/05.01-Response-of-a-First-Order-System-to-Step-and-Square-Wave-Inputs.ipynb)
- [5.2 Exothermic CSTR](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/05.02-Exothermic-CSTR.ipynb)
- [5.3 Transient Heat Conduction in Various Geometries](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/05.03-Heat_Conduction_in_Various_Geometries.ipynb)

### [Chapter 6. Differential-Algebraic Equations](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/06.00-Differential-Algebraic-Equations.ipynb)
- [6.1 Unconstrained Scalar Optimization](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/06.01-Unconstrained-Scalar-Optimization.ipynb)
- [6.2 Maximizing Concentration of an Intermediate in a Batch Reactor](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/06.02-Maximizing-Concentration-of-an-Intermediate-in-a-Batch-Reactor.ipynb)
- [6.3 Path Planning for a Simple Car](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/06.03-Path-Planning-for-a-Simple-Car.ipynb)
- [6.4 Soft Landing Apollo 11 on the Moon](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/06.04-Soft-Landing-Apollo-11-on-the-Moon.ipynb)

### [Chapter 7. Parameter Estimation](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/07.00-Parameter-Estimation.ipynb)
- [7.1 Parameter estimation](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/07.01-Parameter-Estimation-Catalytic-Reactor.ipynb)

### [Chapter 8. Financial Applications](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/08.00-Financial-Applications.ipynb)
- [8.1 Obtaining Historical Stock Data](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/08.01-Obtaining-Historical-Stock_-ata.ipynb)
- [8.2 Consolidating and Charting Stock Data](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/08.02-Consolidating-and-Charting-Stock-Data.ipynb)
- [8.3 Binomial Model for Pricing Options](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/08.03-Binomial-Model-for-Pricing-Options.ipynb)
- [8.4 MAD Portfolio Optimization](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/08.04-MAD-Portfolio-Optimization.ipynb)
- [8.5 Real Options](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/08.05-Real-Options.ipynb)

### [Appendix A. Style Guide](http://nbviewer.jupyter.org/github/jckantor/ND-Pyomo-Cookbook/blob/master/notebooks/A.00-Style-Guide.ipynb)

