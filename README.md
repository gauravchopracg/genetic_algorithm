# genetic_algorithm

This is the code for Genetic Algorithms. In this demo code we use the [MAGIC Gamma Telescope dataset](https://archive.ics.uci.edu/ml/datasets/MAGIC+Gamma+Telescope) to build a classifer. The classifier will train on the dataset and then be able to classify whether or not some energy is either Gamma Radiation or Hadron Radiation. Instead of guessing and checking the best ML model and hyperparameters to use, we use a genetic programming library called [tpot](https://github.com/rhiever/tpot) to do that for us by trying out a bunch of them. See [this](https://github.com/rhiever/tpot/tree/master/tutorials/MAGIC%20Gamma%20Telescope) link for an IPython notebook version of this code. 

Dependencies
============

* Numpy 
* tpot
* scikit-learn
* pandas

Use [pip](https://pypi.python.org/pypi/pip) to install any missing dependencies

Usage
===========

To run the demo code, after installing the dependencies, just run the following in terminal

``python genetic_algo.py``

Credits
===========
Genetic Algorithm Challenge for Learn Python for Data Science #6 by @Sirajology on [Youtube](https://youtu.be/dSofAXnnFrY)
