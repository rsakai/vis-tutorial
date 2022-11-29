# Visualisation tutorial

## Introduction

"JupyterLab is the latest web-based interactive development environment for notebooks, code, and data. Its flexible interface allows users to configure and arrange workflows in data science, scientific computing, computational journalism, and machine learning. A modular design invites extensions to expand and enrich functionality." - [jupyter.org](https://jupyter.org)

This is a visualisation tutorial for python, and the main focus is to introduce the package called, [Altair](https://altair-viz.github.io).

## Set-up

### Binder

For the interactive exercise during the tutorial, we will use Binder because it is easy and quick, and the tutorial does not contain any sensitive information. [mybinder.org](http://mybinder.org) provides you with a free service that turns a Github repository into a collection of interactive notebooks that are accessible online.

To launch a JupyterLab environment for this tutorial, go to: https://mybinder.org/v2/gh/rsakai/vis-tutorial/main?urlpath=lab
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/rsakai/vis-tutorial/main?urlpath=lab)

MyBinder installs the dependencies specified inside of the `environment.yml` for you. We also add an extension to JupyterLab in the `postBuild` script file.

The original data, from SWAPI, the Star Wars API, https://swapi.dev/, has been revised to reflect additional research into gender and sex determinations of characters.

The antibiotics data was obtained from the [vega-datasets collection](https://github.com/vega/vega-datasets).
