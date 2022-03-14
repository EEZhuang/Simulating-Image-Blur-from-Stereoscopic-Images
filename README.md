# Simulated Image Blur from Stereoscopic Images

## Evan Serrano and Emily Zhuang

This project contains implementation for Simulated Image Blur from Stereoscopic Images. It runs on
Python3.10.2 and uses Jupyter-Notebook for its implementation. The following Python3 libraries are
used:

    - OpenCV2
    - MatPlotLib PyPlot
    - NumPy
    - SciPy
    - iPyWidgets
    - Math

To run, launch the Jupyter Notebook file. The last cell launches the user interface, in which you
may select a Left and Right image relative to the base directory, change the disparity map values,
and change the blurring parameters.

The included images are from the Middlebury Stereoscopic image dataset. Sample image paths are
`cones/im2.png` or `teddy/im2.png` for the left images, and `cones/im6.png` or `teddy/im6.png` for
the right images.
