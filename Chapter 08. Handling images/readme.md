Image classification is one of the most exciting areas of machine learning. The
ability of computers to recognize patterns and objects from images is an
incredibly powerful tool in our toolkit. However, before we can apply machine
learning to images, we often first need to transform the raw images to features
usable by our learning algorithms.
To work with images, we will use the Open Source Computer Vision Library
(OpenCV). While there are a number of good libraries out there, OpenCV is the
most popular and documented library for handling images. One of the biggest
hurdles to using OpenCV is installing it. However, fortunately if we are using
Python 3 (at the time of publication OpenCV does not work with Python 3.6+),
we can use Anaconda’s package manager tool conda to install OpenCV in a
single line of code in our terminal:
conda install --channel https://conda.anaconda.org/menpo opencv3
Afterward, we can check the installation by opening a notebook, importing
OpenCV, and checking the version number (3.1.0):
import cv2
cv2.__version__