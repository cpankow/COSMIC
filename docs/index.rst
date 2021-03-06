##################################
Welcome to cosmic's documentation!
##################################
cosmic is a rapid binary population synthesis suite with a special purpose of generating realistic Milky Way compact binary populations. 

cosmic currently implements binary evolutionary processes using BSE (`Hurley+2002 <http://adsabs.harvard.edu/abs/2002MNRAS.329..897H>`_). Several modifications have been applied to BSE to account for recent updates to binary evolution especially important to compact binary formation (e.g. metallicity-dependent stellar winds or black hole natal kick strengths). For a detailed discussion of these modifications, see Breivik+2018 in prep.

************
Using cosmic
************
cosmic's primary purpose is to generate synthetic Milky Way populations. 
This is done through two executables that are installed when cosmic is installed:

* runFixedPop
* gxRealization

For more information on how to use these executables in the command line, see :ref:`fixedpop`. 

For more details on how to use cosmic to run BSE in python, see :ref:`examples` and :ref:`runpop`.

*****************
Table of Contents
*****************

.. toctree::
   :maxdepth: 2

   install/index
   examples/index
   runpop/index
   fixedpop/index

*********************
Package documentation
*********************

Please consult these pages for more details on using cosmic:

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
