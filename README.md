# Bayesian Statistical Analysis in Python

The aim of this course is to introduce new users to the Bayesian approach of statistical modeling and analysis, so that they can use Python packages such as NumPy, SciPy and [PyMC](https://github.com/pymc-devs/pymc) effectively to analyze their own data. It is designed to get users quickly up and running with Bayesian methods, incorporating just enough statistical background to allow users to understand, in general terms, what they are implementing. The tutorial will be example-driven, with illustrative case studies using real data. Selected methods will include approximation methods, importance sampling, Markov chain Monte Carlo (MCMC) methods such as Metropolis-Hastings and Slice sampling. In addition to model fitting, the tutorial will address important techniques for model checking, model comparison, and steps for preparing data and processing model output. 

![PyMC forest plot](http://d.pr/i/pqWT+)

![DAG](http://d.pr/i/AHZV+)

All course content will be available as a GitHub repository, including IPython notebooks and example data.

**To account for last-minute updates to course material, please clone the repository on the day of the tutorial**

## Tutorial Outline

1.  Introduction to Bayesian statistics.
2.  Markov chain Monte Carlo (MCMC)
3.  The Essentials of PyMC
4.  Fitting Statistical Models in PyMC
5.  Hierarchical Modeling
6.  Model Checking and Validation

## Package Installation

This tutorial requires the following third-party packages to be installed on your system:

- IPython
- NumPy (>= 1.7)
- SciPy (>= 0.12)
- matplotlib (>=1.2.1)
- PyMC 2.3.3
- nose (OPTIONAL for testing)
- pydot (OPTIONAL; also requires [GraphViz](http://www.graphviz.org))
- gFortran (OPTIONAL to build from source)

The easiest way to install the Python packages required for this tutorial is via [Anaconda](https://store.continuum.io/cshop/anaconda/), a scientific Python distribution offered by Continuum analytics. Several other tutorials will be recommending a similar setup. 

One of the key features of Anaconda is a command line utility called `conda` that can be used to manage third party packages. We have built a PyMC package for `conda` (Python 2.7.x only) that can be installed from your terminal via the following command:

    conda install -c https://conda.binstar.org/pymc pymc

This should install any prerequisite packages that are required to run PyMC. Those wishing to run PyMC under Python 3 should build it from source:

    pip install git+git://github.com/pymc-devs/pymc.git@2.3.3

For those of you on Mac OS X that are already using the [Homebrew](http://brew.sh) package manager, I have prepared a script that will install the entire Python scientific stack, including PyMC 2.3. You can download the script [here](https://gist.github.com/fonnesbeck/7de008b05e670d919b71) and run it via:

    sh install_superpack_brew.sh
