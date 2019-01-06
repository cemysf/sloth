sloth
=====

[![Build Status](https://travis-ci.org/cvhciKIT/sloth.svg)](https://travis-ci.org/cvhciKIT/sloth)

sloth is a tool for labeling image and video data for computer vision research.

The documentation can be found at http://sloth.readthedocs.org/ .

Latest Releases
===============

2013/11/29 v1.0: 2e69fdae40f89050fbaeef22491eee2a92e78b4f [.zip](https://github.com/cvhciKIT/sloth/archive/v1.0.zip) [.tar.gz](https://github.com/cvhciKIT/sloth/archive/v1.0.tar.gz)

For a full list, visit https://github.com/cvhciKIT/sloth/releases


Install from source
=====
```
conda create -n sloth python=2.7 pyqt=4
conda activate sloth
conda install numpy
conda install pil
python setup.py build
python setup.py install
```

Usage
=====
First, create a json file of images in a path:

`sloth appendfiles annotations.json images/*.jpg`

Then, open that json with sloth

`sloth annotations.json`