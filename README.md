# Bayesian Statistical Analysis in Python

**SciPy 2014 Tutorial**

This tutorial is a *work in progress* until July 1, 2014. I recommend waiting to clone or fork until then.

## Package Installation

This tutorial requires the following third-party packages to be installed on your system:

- IPython
- NumPy (>= 1.7)
- SciPy (>= 0.12)
- matplotlib (>=1.2.1)
- PyMC 2.3

The easiest way to install the Python packages required for this tutorial is via [Anaconda](https://store.continuum.io/cshop/anaconda/), a scientific Python distribution offered by Continuum analytics. Several other tutorials will be recommending a similar setup. 

One of the key features of Anaconda is a command line utility called `conda` that can be used to manage third party packages. We have built a PyMC package for `conda` that can be installed from your terminal via the following command:

    conda install -c https://conda.binstar.org/pymc pymc

This should install any prerequisite packages that are required to run PyMC.

For those of you on Mac OS X that are already using the [Homebrew](http://brew.sh) package manager, I have prepared a script that will install the entire Python scientific stack, including PyMC 2.3. You can download the script [here](https://gist.github.com/fonnesbeck/7de008b05e670d919b71) and run it via:

    sh install_superpack_brew.sh
