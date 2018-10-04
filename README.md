## Introduction

This repository demonstrates using T4 for versioning your data pipeline.

This example is based on the Atlantic portion of [HURDAT2](http://www.nhc.noaa.gov/data/#hurdat), the NOAA's public hurricane tracking data (available [here](https://www.nhc.noaa.gov/data/hurdat/)).


## Building

To build these datasets yourself, navigate to the `notebooks` folder and run the following in the command line:

    >>> jupyter nbconvert --to ipynb munge.ipynb

This executes the notebooks in-place and emits the data files.

Alternatively, if something breaks or you want to explore what's happening, you should run `jupyter notebook` and
open the notebooks themselves.