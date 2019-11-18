# Spring et al. 2020, manuscript in prep.

The paper is still in the process of writing and has not been submitted yet.

## Aim

This repo is setup for scientists interested to reproduce our `Spring et al., 2020` paper. It contains scripts to reproduce the analysis and create the shown figures. It is inspired by `Irving (2015)` to enhance reproducibility in geosciences.

-   Irving, Damien. “A Minimum Standard for Publishing Computational Results in the Weather and Climate Sciences.” Bulletin of the American Meteorological Society 97, no. 7 (October 7, 2015): 1149–58. <https://doi.org/10/gf4wzh>.

## Climate model setup

-   Maher, Nicola, Sebastian Milinski, Laura Suarez-Gutierrez, Michael Botzet, Mikhail Dobrynin, Luis Kornblueh, Jürgen Kröger, et al. “The Max Planck Institute Grand Ensemble - Enabling the Exploration of Climate System Variability.” Journal of Advances in Modeling Earth Systems 0, no. ja (June 4, 2019). <https://doi.org/10/gf3kgt>.

## Raw output availability

-   <https://www.mpimet.mpg.de/en/grand-ensemble/>

## Packages used mostly

-   model output aggregation: `cdo`
-   analysis: `xarray`
-   visualisation: `matplotlib`, `cartopy`
-   predictive skill analysis: [`climpred`](https://climpred.readthedocs.io/)
-   (private repo) data storage paths on supercomputer: `PMMPIESM`

## Computation

The results in this paper were obtained using a number of different software packages. The command line tool known as Climate Data Operators (CDO) was used to aggregate output and perform routine calculations on those files (e.g., the calculation of temporal and spatial means). For more complex analysis and visualization, a Python distribution called Anaconda was used. A Python library called `xarray` was used for reading/writing netCDF files and data analysis. `matplotlib` (the default Python plotting library) was used to generate the figures.

-   CDO: Climate Data Operators, 2018. <http://www.mpimet.mpg.de/cdo>.
-   Hoyer, Stephan, and Joe Hamman. “Xarray: N-D Labeled Arrays and Datasets in Python.” Journal of Open Research Software 5, no. 1 (April 5, 2017). <https://doi.org/10/gdqdmw>.
-   Hunter, J. D. “Matplotlib: A 2D Graphics Environment.” Computing in Science Engineering 9, no. 3 (May 2007): 90–95. <https://doi.org/10/drbjhg>.

## Environment

Dependencies (Packages installed) can be found in `requirements.txt` (conda list). Installed via conda (see setup `conda_info.txt`) and pip.
