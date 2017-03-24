---
layout: post
title:  "Tutorial materials"
date:   2017-03-20
author: Ariel Rokem
---

## Format

The tutorials consist of lecture segments, demos, and hands-on
exercises.  We strongly encourage you to bring a laptop with all the
required packages installed in order to participate fully.

## Data

We will be using a data-set of cell images kindly provided by Maryana Alegro (UCSF). The data is available to download [here]({{ site.baseurl }}/assets/cells.tar.gz).

## Software

### Python for Science

- Python

  If you are new to Python, please install the
  [Anaconda distribution](https://www.continuum.io/downloads) for
  **Python version 3** (available on OSX, Linux and Windows).
  Everyone else, feel free to use your favorite distribution, but
  please ensure the requirements below are met:

  - `numpy` >= 1.11
  - `scipy` >= 0.18
  - `matplotlib` >= 2.0
  - `skimage` >= 0.12
  - `sklearn` >= 0.18
  - `dask` >= 0.14

  In the next section below, we provide a test script to confirm the
  version numbers on your system.

- Tensor Flow and Keras

   First install Tensorflow. Follow the instructions provide [here](https://www.tensorflow.org/install/) for your platform. Once you have completed that, please type `pip install keras`. Depending on your setup, this last command may have to be executed under `sudo` (that is, `sudo pip install keras`)

- Jupyter

  The lecture material includes Jupyter notebooks.  Please follow the
  [Jupyter installation instructions](http://jupyter.readthedocs.io/en/latest/install.html),
  and ensure you have version 4 or later:

  ```bash
  $ jupyter --version
  4.3.0
  ```

#### Test your setup

Please run the following commands inside of Python:

```
import numpy as np
import scipy as sp
import matplotlib as mpl
import skimage
import sklearn
import dask
import tensorflow as tf
import keras

for module in (np, sp, mpl, skimage, sklearn, dask, tf, keras):
    print(module.__name__, module.__version__)
```

E.g., on my computer, I see:

```
numpy 1.12.0
scipy 0.19.0
matplotlib 2.0.0
skimage 0.13dev
sklearn 0.18.1
dask 0.14.0
tensorflow 1.0.0
keras 1.2.2
```

**If you do not have a working setup, please contact the instructors.**

### ImageJ

- Fiji
 
Installation instructions are available here: http://fiji.sc/#download

For this demo we will use samples that will be fetched from the [imagej.net](image.net) site through the application, so no separate downloads are required.
 
- ImageJ Notebooks 
 
We encourage downloading Beaker and opening the ImageJ tutorials notebook prior to the tutorial. This will automatically fetch the necessary dependencies.
 
Recently the ImageJ community has begun using Beaker Notebook for interactive coding. Beaker is like Jupyter notebook, but is built upon the JVM. It has some unique features that are a bit more challenging to incorporate into Jupyter notebook; in particular, Beaker is a polyglot notebook where switching between languages within a single notebook while maintaining access to the same scope/variables.
 
Beaker installation instructions are available here:  http://beakernotebook.com/getting-started?scroll

## Lecture materials

### Numpy, Scipy, Matplotlib, Scikit-image
There are two ways of downloading the lecture materials:

a) Get the [ZIP file from GitHub](https://github.com/imagexd/imagexd-2017-tutorials/archive/master.zip)
   
b) Clone the repository at
   https://github.com/imagexd/imagexd-2017-tutorials
   
### Dask for Parallel Processing
Tutorial materials are [here](https://github.com/arokem/keras-tutorial)

### Tensor Flow and Keras 
Tutorial materials are [here](https://github.com/valentina-s/dask-image-tutorial)

### ImageJ 
We will work through the ImageJ beaker tutorial from the imagej-tutorials github repository, which can either be checked out from the repository:
https://github.com/imagej/tutorials

Or downloaded directly with this link:
https://github.com/imagej/tutorials/raw/master/ImageJ%20Tutorials%20and%20Demo.bkr


Please download the latest version of the material on the morning of the
tutorials to be sure you have all updates.

