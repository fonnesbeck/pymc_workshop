# Bayesian Computing Course

Material for course on Bayesian Computation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fonnesbeck/bayes_course_july2020/master) [![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/bayes_course_july2020/community)

## Setup

This tutorial assumes that you have [Miniforge](https://github.com/conda-forge/miniforge) (recommended) or [Anaconda](https://www.anaconda.com/products/individual#download-section) setup and installed on your system. If you do not, please download and install one of these on your system before proceeding with the setup.

The next step is to clone or download the tutorial materials in this repository. If you are familiar with Git, run the clone command:

    git clone https://github.com/fonnesbeck/pymc_workshop.git

otherwise you can [download a zip file](https://github.com/fonnesbeck/pymc_workshop/archive/master.zip) of its contents, and unzip it on your computer.

The repository for this tutorial contains a file called `environment.yml` that includes a list of all the packages used for the tutorial. If you run:

    conda env create

from the main tutorial directory, it will create the environment for you and install all of the packages listed. This environment can be enabled using:

    conda activate pymc_workshop

Then, you can start **JupyterLab** to access the materials:

    jupyter lab

The binder link above should also provide a working environment.

## Pre-course Work

In advance of the course, we would like attendees to complete a short homework notebook that will ensure everyone has the requisite baseline knowledge. You can find this Jupyter notebook in the `/notebooks` subdirectory (under `Section0-Pre_Work.ipynb`). There is no need to hand this in to anyone, but please reach out if you have difficulty with any of the problems (or with setting up your computing environment) by creating an [issue](https://github.com/fonnesbeck/pymc_workshop/issues) in this repository, or by emailing.

## Course Outline

The course comprises four modules, along with short associated hands-on projects to reinforce materials covered during lectures. 

### Part 1: Basic Bayes
- Bayesian vs frequentist statistics
- Bayesian computation
- Evaluating hypotheses

### Part 2: Hierarchcial Models
- Motivation and case studies
- Partial pooling
- Building hierarchical models
- Parameterizations
- Model checking

### Part 3: Markov chain Monte Carlo
- Probability density functions, inverse CDF sampling
- Rejection sampling
- MCMC basics
- Metropolis-Hastings samplers
- Gibbs samplers
- Gradient-based MCMC
- Diagnostics

### Part 4: The Bayesian Workflow
- Prior predictive checks
- Iterating models
- Posterior predictive checks
- Using the model


