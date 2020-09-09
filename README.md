# pyproffit

Pyproffit is a python package for the analysis of X-ray brightness profiles of clusters of galaxies. It is the python equivalent of the popular Proffit C++ package (Eckert et al. 2011).

# Installation

``pyproffit`` is available on PyPI. The easiest way of installing ``pyproffit`` is obviously to use pip:

    pip3 install pyproffit
    
The PyPI repository should contain the latest stable release (as judged by the developer), it may not be the latest version thus some features may be missing. To install the latest version from Github:

    git clone https://github.com/domeckert/pyproffit.git
    cd pyproffit
    pip3 install .
    
``pyproffit`` depends on numpy, scipy, astropy, matplotlib, iminuit, pymc3, and pystan.

# Documentation

An extensive documentation is available on readthedocs:

https://pyproffit.readthedocs.io
