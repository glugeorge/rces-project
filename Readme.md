# Research Computing in Earth Science Final Project
By George Lu

This binder link is to the Jupyter hub since unfortunately, the MyBinder server doesn't have enough space to run the code.

[![Binder](https://mybinder.org/badge.svg)](https://us-central1-b.gcp.pangeo.io/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fglugeorge%2Frces-project&urlpath=lab%2Ftree%2Frces-project%2Fproject.ipynb&branch=main)

## Research Question:
How does meltwater runoff influence glacier velocities on the Greenland Ice Sheet (GIS)?

## Data Description
I will be using two data sets, one being the output from a climate model for daily run-off on the GIS (from MAR, data stored in the LDEO Glaciology Google Cloud storage) [1]. The second dataset I would use is annual velocities of the GIS (https://zenodo.org/record/4977910#.YZPMQr3ML0o [2].

## Analysis
First I resample and transform the daily runoff such that I can get an annual runoff variability across the GIS. Next, I take the cross correlation with the interpolated velocity data to see how strongly the two 2D timeseries are correlated. I display spatial averages of runoff and velocity over time to compare trends across the entire GIS, while also having 2d heatmaps of the cross correlation to see if only specific regions are strongly influenced by runoff. 

[1] Fettweis, X., Box, J. E., Agosta, C., Amory, C., Kittel, C., Lang, C., van As, D., Machguth, H., and Gallée, H.: Reconstructions of the 1900–2015 Greenland ice sheet surface mass balance using the regional climate MAR model, The Cryosphere, 11, 1015–1033, https://doi.org/10.5194/tc-11-1015-2017, 2017.

[2] Mouginot, Jeremie, Rignot, Eric, Scheuchl, Bernd, Wood, Michael, & Millan, Romain. (2019). Annual Ice Velocity of the Greenland Ice Sheet (2010-2017) [Data set]. https://doi.org/10.7280/D11H3X
