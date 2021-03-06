pybo
----

A Python package for modular Bayesian optimization.

This package provides methods for performing optimization of a possibly
noise-corrupted function *f*. In particular this package allows us to place
a prior on the possible behavior of *f* and select points in order to gather
information about the function and its maximum.

[![Build Status](https://travis-ci.org/mwhoffman/pybo.svg)]
(https://travis-ci.org/mwhoffman/pybo)
[![Coverage Status](https://coveralls.io/repos/mwhoffman/pybo/badge.png)]
(https://coveralls.io/r/mwhoffman/pybo)

Installation
============

The easiest way to install this package is by running

    pip install git+https://github.com/mwhoffman/{mwhutils,pygp,pybo}.git

from the command line. Alternatively the packages above can be installed by
cloning their repositories and using `setup.py` directly. Once the package is
installed the included demos can be run directly via python.  For example, by
running

    python -m pybo.demos.beginner

A full list of demos can be viewed [here](pybo/demos).
