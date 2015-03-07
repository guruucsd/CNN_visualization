## CNN_visualization

This is our implementation (plus a demo) of CNN feature visualization (Zeiler & Fergus, 2013).

The way to just look at the ipython notebook. Use link: http://nbviewer.ipython.org/github/guruucsd/CNN_visualization/blob/master/urban_tribe/caffe/deconv_demo.ipynb

The visualization result is not as clear as the paper shows. We assume it's because they use different architecture and we have a small dataset for visualization.  However, it may due to undetected bugs (but we hope not..)  If you find any mistakes in this code, please tell us!


## References

Zeiler, M. D. and Fergus, R. (2013) Visualizing and Understanding Convolutional Networks. http://arxiv.org/abs/1311.2901


## To run

This notebook should be run from the `guru2.ucsd.edu` server.  Installation of caffe can be quite challenging, and this notebook depends on a particular `urban_tribes` model that only exists on that server.

To run,
* `ssh -X [username@]guru2.ucsd.edu
* clone this repository
* run `ipython notebook` and open the `CNN_visualization/urban_tribe/caffe/deconv_demo.ipynb` file.
