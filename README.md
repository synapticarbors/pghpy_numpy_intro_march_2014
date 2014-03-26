Introduction to Numpy
=====================

This repository contains the materials for the Introduction to Numpy tutorial at the PghPy meetup (March 2014).
After cloning or downloading this repository, you should be able to run the IPython notebook by firing up IPython in the head of the
repo directory as:

    ipython notebook

There are three notebooks to choose from:

- `pghpy_numpy_intro.ipynb` -- Contains the complete code with rendered output
- `pghpy_numpy_intro_livecode.ipynb` -- Contains section headings
- `pghpy_numpy_intro_nooutput.ipynb` -- Contains the complete code but with un-executed cells

To view a static version of the complete notebook, open `pghpy_numpy_intro.html` in your browser.

Requirements
------------

* Python 2.7
* IPython >= 1.0 (to run the notebook, although you might be able to get away with 0.13)
* NumPy >= 1.6.1
* Scipy
* Matplotlib >= 1.0 (for some plotting in the notebook)
* rpy2 and R for one example (optional)

My general recommendation is to use either the 
[Anaconda python distribution](https://store.continuum.io/cshop/anaconda/) or 
[Enthought Canopy](https://www.enthought.com/products/canopy/). Both are free and provide one-click installation
of all of the major scientific libraries. I use
and recommend Anaconda since it provides a larger collection of libraries than Canopy's free
version, Canopy Express, although if you have an academic license, both are equivalent.

If you find that both of these distributions are too heavy, you might also want to look at 
Continuum's [miniconda](http://conda.pydata.org/miniconda.html) and then just install the packages you want
from the command line.


Attribution
-----------

This notebook was based largely on Jake VanderPlas's "Scientific Computing with Python" lecture on Numpy among other resources cited
at the end of the notebook:

http://www.astro.washington.edu/users/vanderplas/Astr599/schedule

