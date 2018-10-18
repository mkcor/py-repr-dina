# py-repr-dina

An attempt at reproducing Stan's education case study "DINA" in Python.

## Setup

We work in a [conda](https://conda.io/) environment. If you are setting up the
environment for the first time, run:

    $ conda env create -f environment.yml

to install all dependencies in this isolated environment, named `py-repr-dina`.

If dependencies get updated, run:

    $ conda env update -f environment.yml

If you wish to remove the `py-repr-dina` environment, run:

    $ conda remove -n py-repr-dina --all

To work in the environment, we need to activate it:

    $ source activate py-repr-dina
