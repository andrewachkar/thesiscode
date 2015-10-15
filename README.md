# Thesis code
## Overview

This repository contains tabulations of the theoretical and empirical atomic scattering form factors for the elements and two Mathematica notebooks that can be use to load,  extract and plot the data as needed. It also provides a framework for performing [Kramers-Kronig transformations](https://en.wikipedia.org/wiki/Kramers%E2%80%93Kronig_relations) on the data, with examples for the elements shown. 


## Contents

The two notebooks are:
1. f1f2mu\_Henke\_Chantler.nb
2. KramersKronig\_atomicNIST.nb

The first notebook is merely a tool to extract the f1 and f2 data for all the elements and combine them into a calculation for compounds. 

The second notebook takes f2, the imaginary part of f, and performs a Kramers-Kronig transformation in order to determine the real part f1. This is a useful framework for stitching tabulated data to experimental X-ray absorption data and obtaining reliable Kramers-Kronig transforms in the near edge structure.   

This work originates from my [PhD thesis](https://uwspace.uwaterloo.ca/handle/10012/9255), which explains all of this in substantially more detail (see Ch 2). 


The database files are:
1. f1f2\_Henke.dat
2. f1f2\_NIST.dat


## Sources
### Online tabulations
f1f2_Henke.dat contains empirical atomic scattering form factors and was taken from the [XOP project](http://ftp.esrf.eu/pub/scisoft/xop2.3/DabaxFiles/).

f1f2_NIST.dat contains theoretical atomic scattering form factors and was compiled using a script to extract data from the [FFAST NIST server](http://www.nist.gov/pml/data/ffast/index.cfm).

### Original work
1. [C. T. Chantler. Journal of Physical and Chemical Reference Data, 24(1):71–643, 1995.] (http://dx.doi.org/10.1063/1.555974)

2. [C. T. Chantler. Journal of Physical and Chemical Reference Data, 29(4):597–1056, 2000.](http://dx.doi.org/10.1063/1.1321055)

3. [B. Henke, E. Gullikson, and J. Davis. Atomic Data and Nuclear Data Tables, 54(2):181–342, 1993.](http://dx.doi.org/10.1006/adnd.1993.1013)
