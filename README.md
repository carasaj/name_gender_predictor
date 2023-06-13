# Predicting Gender by Name

This logistic regression model will predict if a name is male or female. The input data is read from a CSV file found here: https://www.kaggle.com/datasets/kaggle/us-baby-names?resource=download

---

## Technologies

The script is written in Python 3.7 using Jupyter Lab, and exists as a Python Notebook file (.ipynb). The datasheet is in a CSV (.csv) format.

The user will need to install and/or import the following:

* [Python3](https://www.python.org/downloads/) - This script is written in Python3, which the user will need installed.
* [Anaconda](https://docs.continuum.io/anaconda/) - A package manager for installing pandas and Jupyter Lab. Optional but efficient.
* [Jupyter Lab - Anaconda](https://anaconda.org/anaconda/jupyter) - Optional notebook workspace, useful for users wanting to experiment with the code.
* [Jupyter Lab- Manual Install](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) - Install link for use w/o Anaconda. For users not utilizing Anaconda.
* [Pandas - Anaconda](https://docs.anaconda.com/navigator/tutorials/pandas/) - Essential for DataFrame/Series manipulation and CSV reading. 
* [Pandas - Manual Install](https://pandas.pydata.org/docs/getting_started/install.html) - Install link for use w/o Anaconda. For users not utilizing Anaconda.
* [Pathlib](https://docs.python.org/3/library/pathlib.html) - For file paths.
* [texthero](https://pypi.org/project/texthero/) - For text processing.
* [sklearn](https://scikit-learn.org/stable/install.html) - Create, fit, and tune a chosen model to run predictions.

---

## Installation Guide

The user will need to have [Python3](https://www.python.org/downloads/) downloaded first, then [Anaconda](https://docs.continuum.io/anaconda/).

Anaconda Navigator can be used to easily install and/or access [Jupyter Lab - Anaconda](https://anaconda.org/anaconda/jupyter) and [Pandas - Anaconda](https://docs.anaconda.com/navigator/tutorials/pandas/). They should be accessable immediately after installing Anaconda; if not, follow the previous links. If you are not using Anaconda and prefer manual installs, use the Manual Install links provided in the previous section and follow the steps listed in the documentation.

If using Miniconda instead of Anaconda, the user will need to set up their virtual environment first. Use this command in a terminal window:

```
    conda create -n name_of_my_env python
```
Then, to enter the environment, use this command:
```
    source activate name_of_my_env
```
For Windows users, you will need to use:
```
    activate name_of_my_env
```
Last, we will install pandas:
```
    conda install pandas
```
The user may also need to install pathlib and matplotlib with the following commands:
```
    conda install matplotlib
```
```
    conda install -c anaconda pathlib
```

---

## Usage

The code will need to be adapted for use with alternate datasheets. New data should work if the CSV files are formatted similarly, but the user will need to perform data cleanup as needed(NaN/missing values, currency symbol removal, etc.,).


---

## Contributors

This project was created by Austin Caras. You can contact him at caras.austin@gmail.com for any questions.

---

## License

This project is unlicensed and free to use by anyone.

---
