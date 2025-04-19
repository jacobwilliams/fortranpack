![logo](media/fortran_logo_64x64.png)

**fortranpack**: A Modern Fortran Numerical & Scientific Programming Package

[![Language](https://img.shields.io/badge/-Fortran-734f96?logo=fortran&logoColor=white)](https://github.com/topics/fortran)
[![CI Status](https://github.com/jacobwilliams/fortranpack/actions/workflows/CI.yml/badge.svg)](https://github.com/jacobwilliams/fortranpack/actions)
[![last-commit](https://img.shields.io/github/last-commit/jacobwilliams/fortranpack)](https://github.com/jacobwilliams/fortranpack/commits/master)
<!-- [![GitHub release](https://img.shields.io/github/release/jacobwilliams/fortranpack.svg)](https://github.com/jacobwilliams/fortranpack/releases/latest) -->
<!-- [![codecov](https://codecov.io/gh/jacobwilliams/fortranpack/branch/master/graph/badge.svg)](https://codecov.io/gh/jacobwilliams/fortranpack) -->


This is an experiment. It is basically just a [Fortran Package Manager](https://fpm.fortran-lang.org) `fpm.toml` manifest file that uses the following packages:

 * [argv-fortran             ](https://github.com/jacobwilliams/argv-fortran) -- A better `get_command_argument` for Fortran
 * [bspline-fortran          ](https://github.com/jacobwilliams/bspline-fortran) -- Multidimensional B-Spline Interpolation of Data on a Regular Grid
 * [conmax                   ](https://github.com/jacobwilliams/conmax) -- Modern Fortran CONMAX Optimization Method for general nonlinearly constrained function minimization
 * [conmin                   ](https://github.com/jacobwilliams/conmin) -- Modern Fortran CONMIN Optimization Method
 * [csv-fortran              ](https://github.com/jacobwilliams/csv-fortran) -- Read and Write CSV Files Using Modern Fortran
 * [daglib                   ](https://github.com/jacobwilliams/daglib) -- Directed Acyclic Graphs With Modern Fortran
 * [ddeabm                   ](https://github.com/jacobwilliams/ddeabm) -- Modern Fortran implementation of the DDEABM Adams-Bashforth algorithm
 * [dop853                   ](https://github.com/jacobwilliams/dop853) -- Modern Fortran Edition of Hairer's DOP853 ODE Solver
 * [finterp                  ](https://github.com/jacobwilliams/finterp) -- Multidimensional (1D-6D) Linear and Nearest-Neighbor Interpolation with Modern Fortran
 * [fortran-mach             ](https://github.com/jacobwilliams/fortran-mach) -- Modern Fortran Machine Constants Module (r1mach, d1mach, i1mach)
 * [fortran-search-and-sort  ](https://github.com/jacobwilliams/fortran-search-and-sort) -- Searching and sorting with modern Fortran
 * [json-fortran             ](https://github.com/jacobwilliams/json-fortran) -- A Modern Fortran JSON API
 * [lbfgsb                   ](https://github.com/jacobwilliams/lbfgsb) -- Modern Fortran Refactoring of L-BFGS-B Nonlinear Optimization Code
 * [mersenne-twister-fortran ](https://github.com/jacobwilliams/mersenne-twister-fortran) -- Mersenne Twister pseudorandom number generator for Fortran
 * [nlesolver-fortran        ](https://github.com/jacobwilliams/nlesolver-fortran) -- Nonlinear Equation Solver with Modern Fortran
 * [NumDiff                  ](https://github.com/jacobwilliams/NumDiff) -- Modern Fortran Numerical Differentiation Library
 * [optgra                   ](https://github.com/jacobwilliams/optgra) -- Modern Fortran edition of OPTGRA optimization algorithm from ESA
 * [pchip                    ](https://github.com/jacobwilliams/PCHIP) -- Modern Fortran Piecewise Cubic Hermite Interpolation Package
 * [pikaia                   ](https://github.com/jacobwilliams/pikaia) -- Modern Fortran Edition of the Pikaia Genetic Algorithm
 * [polyroots-fortran        ](https://github.com/jacobwilliams/polyroots-fortran) -- Modern Fortran library for finding the roots of real and complex polynomial equations
 * [popen-fortran            ](https://github.com/jacobwilliams/popen-fortran) -- Simple Fortran module for popen
 * [psqp                     ](https://github.com/jacobwilliams/psqp) -- Modern Fortran Edition of PSQP (Sequential quadratic programming algorithm)
 * [pyplot-fortran           ](https://github.com/jacobwilliams/pyplot-fortran) -- For generating plots from Fortran using Python's `matplotlib.pyplot`
 * [quadpack                 ](https://github.com/jacobwilliams/quadpack) -- Modern Fortran QUADPACK Library for 1D numerical quadrature
 * [quadrature-fortran       ](https://github.com/jacobwilliams/quadrature-fortran) -- 1D-6D Adaptive Gaussian Quadrature with Modern Fortran
 * [regridpack               ](https://github.com/jacobwilliams/regridpack) -- Modern Fortran Edition of REGRIDPACK
 * [rklib                    ](https://github.com/jacobwilliams/rklib) -- Fixed and variable-step Runge-Kutta solvers in Modern Fortran
 * [roots-fortran            ](https://github.com/jacobwilliams/roots-fortran) -- A modern Fortran library for finding the roots of continuous scalar functions of a single real variable, using derivative-free methods.
 * [simulated-annealing      ](https://github.com/jacobwilliams/simulated-annealing) -- Simulated Annealing with Modern Fortran
 * [slsqp                    ](https://github.com/jacobwilliams/slsqp) -- Modern Fortran Edition of the SLSQP Optimizer
 * [splpak                   ](https://github.com/jacobwilliams/splpak) -- Modernized SPLPAK library for multidimensional least-squares cubic spline fitting
 * [stringsort               ](https://github.com/jacobwilliams/stringsort) -- Modern Fortran sorting routines for strings
 * [uuid-fortran             ](https://github.com/jacobwilliams/uuid-fortran) -- Fortran module for generating UUIDs

To use this, just add this to your project's `fpm.toml` file:

```toml
[dependencies]
fortranpack = { git="https://github.com/jacobwilliams/fortranpack.git" }
```

### See also

* [A Modern Fortran Scientific Programming Ecosystem](https://degenerateconic.com/a-modern-fortran-scientific-programming-ecosystem.html), degenerateconic.com, Oct 12, 2022.
* [Packs](https://degenerateconic.com/packs.html), degenerateconic.com, Feb 08, 2022.
* [Fortran Standard Library](https://github.com/fortran-lang/stdlib)