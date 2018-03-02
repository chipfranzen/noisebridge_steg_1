# Noisebridge Python class guest lecture: Steganography

## Overview

Student notebook at `steganography_class_student.ipynb`

Solutions will be posted after the class.

Various text files for use during the class, and for you to play with.

## Setup

I'll be using Conda (miniconda to be specific) to handle virtual environments, but feel free to use `venv` or whatever else you like.

If you don't have python:

https://conda.io/miniconda.html

Get python 3.

On MacOS:
```bash
$ cd ~
$ wget https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
$ bash Miniconda3-latest-MacOSX-x86_64.sh
```
Type `yes` when prompted.

Now set up the environment:

```bash
$ conda create -n steganography python=3.6 jupyter
$ source activate steganography
$ pip install jupyter
$ git clone git@github.com:fastforwardlabs/steganos.git
$ cd steganos
$ python setup.py install
```
And start a notebook server
```bash
$ jupiter notebook
```

If things don't automatically open, navigate to `localhost:8888` in your favorite browser.
