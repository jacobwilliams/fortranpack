# fortranpack

A Modern Fortran Numerical & Scientific Programming Package

This is an experiment. It is basically just a [Fortran Package Manager](https://fpm.fortran-lang.org) `fpm.toml` manifest file that uses the following packages:

 * [argv-fortran             ](https://github.com/jacobwilliams/argv-fortran)
 * [bspline-fortran          ](https://github.com/jacobwilliams/bspline-fortran)
 * [conmax                   ](https://github.com/jacobwilliams/conmax)
 * [conmin                   ](https://github.com/jacobwilliams/conmin)
 * [csv-fortran              ](https://github.com/jacobwilliams/csv-fortran)
 * [daglib                   ](https://github.com/jacobwilliams/daglib)
 * [ddeabm                   ](https://github.com/jacobwilliams/ddeabm)
 * [dop853                   ](https://github.com/jacobwilliams/dop853)
 * [finterp                  ](https://github.com/jacobwilliams/finterp)
 * [fortran-mach             ](https://github.com/jacobwilliams/fortran-mach)
 * [fortran-search-and-sort  ](https://github.com/jacobwilliams/fortran-search-and-sort)
 * [json-fortran             ](https://github.com/jacobwilliams/json-fortran)
 * [lbfgsb                   ](https://github.com/jacobwilliams/lbfgsb)
 * [mersenne-twister-fortran ](https://github.com/jacobwilliams/mersenne-twister-fortran)
 * [nlesolver-fortran        ](https://github.com/jacobwilliams/nlesolver-fortran")
 * [NumDiff                  ](https://github.com/jacobwilliams/NumDiff)
 * [optgra                   ](https://github.com/jacobwilliams/optgra)
 * [pchip                    ](https://github.com/jacobwilliams/PCHIP)
 * [pikaia                   ](https://github.com/jacobwilliams/pikaia)
 * [polyroots-fortran        ](https://github.com/jacobwilliams/polyroots-fortran)
 * [popen-fortran            ](https://github.com/jacobwilliams/popen-fortran)
 * [psqp                     ](https://github.com/jacobwilliams/psqp)
 * [pyplot-fortran           ](https://github.com/jacobwilliams/pyplot-fortran)
 * [quadpack                 ](https://github.com/jacobwilliams/quadpack)
 * [quadrature-fortran       ](https://github.com/jacobwilliams/quadrature-fortran)
 * [regridpack               ](https://github.com/jacobwilliams/regridpack)
 * [rklib                    ](https://github.com/jacobwilliams/rklib)
 * [roots-fortran            ](https://github.com/jacobwilliams/roots-fortran)
 * [simulated-annealing      ](https://github.com/jacobwilliams/simulated-annealing)
 * [slsqp                    ](https://github.com/jacobwilliams/slsqp)
 * [splpak                   ](https://github.com/jacobwilliams/splpak)

To use this, just add this to your project's `fpm.toml` file:

```toml
[dependencies]
fortranpack = { git="https://github.com/jacobwilliams/fortranpack.git" }
```

### See also

* [A Modern Fortran Scientific Programming Ecosystem](https://degenerateconic.com/a-modern-fortran-scientific-programming-ecosystem.html), degenerateconic.com, Oct 12, 2022.
* [Packs](https://degenerateconic.com/packs.html), degenerateconic.com, Feb 08, 2022.
* [Fortran Standard Library](https://github.com/fortran-lang/stdlib)