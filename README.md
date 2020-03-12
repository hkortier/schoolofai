# Gaussian Processes: A practical introduction

**School of AI Enschede 2020**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hkortier/schoolofai/master)

## Description

Gaussian processes are flexible probabilistic models that can be used to perform Bayesian regression analysis. This tutorial will introduce new users to create simple Gaussian process models, i.e. Gaussian Likelihoods and Priors with SE Kernels, in Python.

## Abstract

Nowadays, there are many ways of building data science models using Python, including statistical and machine learning methods. I will introduce probabilistic models, which use Bayesian statistical methods to quantify all aspects of uncertainty relevant to your problem, and provide inferences in simple, interpretable terms using probabilities. A particularly flexible class of probabilistic models uses Bayesian non-parametric methods, which allow models to vary in complexity depending on how much data are available. In doing so, they avoid the over-fitting that is common in machine learning and statistical modeling. I will demonstrate the basics of Bayesian non-parametric modeling in Python. Specifically, I will introduce Gaussian processes (GP), and show how they can be applied to regression analysis using a few examples.

## Setup

This tutorial assumes that you have the [pipenv](https://pipenv-fork.readthedocs.io/en/latest/) (Python 3.6 or greater) setup and installed on your system.
Alternatively you could use the google colab environment.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/hkortier/schoolofai.git
    
otherwise you can [download a zip file](https://github.com/hkortier/schoolofai/archive/master.zip) of its contents, and unzip it on your computer.
***
The repository for this tutorial contains a file called `Pipfile` that includes a list of all the packages used for the tutorial. If you run:

    pipenv install
    
from the main directory, it will create the environment for you and install all of the packages listed. You can run jupyter notebook within this environment using:

    pipenv run jupyter notebook