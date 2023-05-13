.. meta::
   :description lang=en: kafe - a general, Python-based approach to fit a
      model function to two-dimensional data points with correlated
      uncertainties in both dimensions
   :robots: index, follow


.. toctree::
   :hidden:
   :caption: Table of Contents
   :name: mastertoc
   :maxdepth: 2

   self
   installation
   examples
   module_doc

Welcome to *kafe*, the Karlsruhe Fit Environment
================================================

   **kafe** is a data fitting framework designed for use in undergraduate
   physics lab courses. It provides a basic Python toolkit for fitting
   models to data as well as visualisation of the data and the model function.
   It relies on Python packages such as :py:mod:`numpy` and :py:mod:`matplotlib`,
   and uses the Python interface to the minimizer `Minuit` contained in the data
   analysis framework `ROOT` or in the Python package `iminuit`.

.. include::  overview.rst
