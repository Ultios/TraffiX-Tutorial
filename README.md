# Introduction to TraffiX, a traffic assignment module

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Ultios/TraffiX-tutorial/main)

## Tutorial on macroscopic four step traffic modelling with Python

This tutorial is an introduction to traffic modelling in Python, with a focus on getting first hand experience on different libraries used for macroscopic traffic modelling. The street network data is provided by OpenStreetMap using osmnX and is manipulated using NetworkX and GeoPandas. Visualizations of the model used MatPlotLib.
It will follow classical four step modelling with step-by-step tutorial using Yogyakarta City as study cases.
 
The tutorial will cover the following topics, each of them using Jupyter notebooks and hands-on exercises with real-world data:

1. 
2. 
3. 
4. 
5. 


## Installation notes

Following this tutorial will require recent installations of:

- traffix
- [Jupyter Notebook or Lab](http://jupyter.org)

If you do not yet have these packages installed, we recommend to use the [conda](http://conda.pydata.org/docs/intro.html) package manager to install all the requirements 
(you can install [miniconda](http://conda.pydata.org/miniconda.html) or install the (larger) Anaconda
distribution, found at https://www.anaconda.com/download/).

Using conda, we recommend to create a new environment with all packages using the
following commands:

```bash
# setting the configuation so all packages come from the conda-forge channel
conda config --add channels conda-forge
conda config --set channel_priority strict
# navigate to the downloaded (or git cloned) material
cd .../geopandas-tutorial/
# creating the environment
conda env create --name traffix-tutorial traffix
# activating the environment
conda activate traffix-tutorial
```


Alternatively, you can install the packages using conda manually, or you can
use ``pip``, as long as you have the above packages installed. In that case,
we refer to the installation instructions of the individual packages (note:
this won't work on Windows out of the box).

**Want to try out without installing anything?** You can use the "launch binder" link above at the top of this README, which will launch a notebook instance on Binder with all required libraries installed.

This repo is inspired and adapted from Joris Van Den Bossche's geopandas-tutorial.