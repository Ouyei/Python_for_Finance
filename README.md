# Python for Finance (2nd ed., O'Reilly)

This repository provides all Python codes and Jupyter Notebooks of the book _Python for Finance -- Mastering Data-Driven Finance_ (2nd edition) by Yves Hilpisch.

<img src="http://hilpisch.com/images/py4fi_2nd_shadow.png" width="500">

Visit the book page of O'Reilly under http://bit.ly/python-finance-2e or order the book under https://www.amazon.com/Python-Finance-Mastering-Data-Driven/dp/1492024333/.

The codes of the book are based on Python 3.7. The codes presented in this Github repository are tested for Python 3.6 since at the time of creating it, `TensorFlow` was not yet compatible with Python 3.7. Once this has happened, appropriate changes (e.g. to the `conda` `yaml` file, see below) will be made.

## Python Packages

There is a `yaml` file for the installation of required Python packages in the repository. This is to be used with the `conda` package manager (see https://conda.io/docs/user-guide/tasks/manage-environments.html). If you do not have Miniconda or Anaconda installed, we recommend to install **Miniconda 3.7** first (see https://conda.io/miniconda.html).

After you have cloned the repository, do on the shell (currently works on Mac OS):

    cd py4fi2nd
    conda env create -f py4fi2nd.yml
    source activate py4fi2nd
    jupyter notebook

Then you can navigate to the Jupyter Notebook files and get started.
