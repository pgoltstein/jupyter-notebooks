# fov-calibration
Jupyter notebook that showcases way(s) to measure the field-of-view (fov) size of a two-photon microscope (or other imaging device) using a 2d calibration grid.

__Contains__
* Loading and visualizing images of a calibration grid
* Calculation of grid spacing by detecting and counting peaks
* Conversion to field-of-view size and pixel size

__Requires the following python packages__
* os
* glob
* numpy
* matplotlib
* skimage

_Future directions_: The current notebook only shows how to detect the average fov/pixel size over a selected area of the grid. A possible next versions may include a way to fit a 2d grid to the entire image and estimate an instantaneous pixel size transformation.

Version 1.0 - April 1st, 2020 - Pieter Goltstein
