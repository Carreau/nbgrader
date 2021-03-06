# nbgrader

[![Google Group](https://img.shields.io/badge/-Google%20Group-lightgrey.svg)](https://groups.google.com/forum/#!forum/jupyter)
[![Build Status](https://travis-ci.org/jupyter/nbgrader.svg)](https://travis-ci.org/jupyter/nbgrader)
[![codecov.io](http://codecov.io/github/jupyter/nbgrader/coverage.svg?branch=master)](http://codecov.io/github/jupyter/nbgrader?branch=master)

A system for assigning and grading notebooks.

[Documentation can be found on Read the Docs.](http://nbgrader.readthedocs.org)

## Installation

If you want to develop on nbgrader, please follow the [development installation instructions](CONTRIBUTING.md#development-installation).

### Dependencies

Before installing nbgrader, please ensure that the IPython notebook is properly installed.
Note that it is not sufficient to just install IPython; you must specifically install the notebook components as well.

If using conda, run

    conda install ipython-notebook=3.2

Otherwise, run

    pip install ipython[all]==3.2

### Installing nbgrader

After installing the above dependencies, you can install the current version of nbgrader with:

    pip install nbgrader

You can then install and activate the nbgrader assignment toolbar extension with:

    nbgrader extension install
    nbgrader extension activate

If you want to install the extension for only yourself (and not systemwide), use `nbgrader extension install --user`.
If you don't want to have to reinstall the extension when nbgrader is updated, use `nbgrader extension install --symlink`.
To get help and see all the options you can pass while installing/activating the nbgrader notebook extension, use:

    nbgrader extension install --help-all
    nbgrader extension activate --help-all

## Contributing

Please see the [contributing guidelines and documentation](CONTRIBUTING.md).
