---
layout: post
title:  "Tutorial materials"
date:   2017-03-20
author: Ariel Rokem
---

## Data

We will be using a data-set of cell images kindly provided by Maryana Alegro (UCSF). The data is available to download [here]({{ site.baseurl }}/assets/cells.tar.gz).


## Software

### Keras and Tensorflow:

First install Tensorflow. Follow the instructions provide [here](https://www.tensorflow.org/install/) for your platform. Once you have completed that, please type `pip install keras`. Depending on your setup, this last command may have to be executed under `sudo` (that is, `sudo pip install keras`)

Materials for the keras tutorial are available [here](https://github.com/arokem/keras-tutorial).

### Dask

Verify that you have a recent version of the Python Dask library installed:

`pip install dask --upgrade`

Materials for the dask tutorial ara available [here](https://github.com/valentina-s/dask-image-tutorial).

### ImageJ

The ImageJ tutorial will cover 2 components of the ImageJ ecosystem:
1. The standalone ImageJ application: Fiji
2. the ImageJ API through Beaker notebooks

**Fiji**

Installation instructions are available here: http://fiji.sc/#download

For this demo we will use samples that will be fetched from the imagej.net site through the application, so no separate downloads are required.

**ImageJ Notebooks**

We encourage downloading Beaker and opening the ImageJ tutorials notebook prior to the tutorial. This will automatically fetch the necessary dependencies.

Recently the ImageJ community has begun using Beaker Notebook for interactive coding. Beaker is like Jupyter notebook, but is built upon the JVM. It has some unique features that are a bit more challenging to incorporate into Jupyter notebook; in particular, Beaker is a polyglot notebook where switching between languages within a single notebook while maintaining access to the same scope/variables.

Beaker installation instructions are available here:  http://beakernotebook.com/getting-started?scroll

We will work through the ImageJ beaker tutorial from the imagej-tutorials github repository, which can either be checked out from the repository:
https://github.com/imagej/tutorials

Or downloaded directly with this link:
https://github.com/imagej/tutorials/raw/master/ImageJ%20Tutorials%20and%20Demo.bkr
