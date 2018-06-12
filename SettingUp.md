Google Doc for this mx-rcnn project setting up and running on SSH

Step1:
Pull this project from github by following:
	git clone https://github.com/zlyin/mx-rcnn

Step2:
Will refer "path/where/store/the/sourcecode/" as "HomePath" for further reference;
Enter the HomePath and go through all files;

Step3:
Follow the README.md to set up environment, especially install essential packages:
	Install Python package pip install numpy matplotlib cython easydict.
	Install MXNet pip install mxnet-cu90. Type import mxnet in Python console to confirm.

[important]
Need to "make" cython package at first, otherwise, several errors alike to this one may occur:
	from ..cython.bbox import bbox_overlaps_cython
	ImportError: No module named bbox

