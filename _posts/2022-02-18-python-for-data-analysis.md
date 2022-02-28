---
title: "Python for Data Analysis"
categories:
  - book
  - memo
  - python
---

accompanying materials: [link](https://github.com/wesm/pydata-book)

## 2022-02-18

### 1. Preliminaries

* NumPy - container for data passed between algorithms and libraries.
* pandas - `DataFrame` and `Series`
* matplotlib - library for producing plots and 2D data visualizations.
* SciPy - collection of packages for problem domains in scientific computing.
* scikit-learn - machine-learning toolkit for python.
* Updating conda packages with pip might result in environment problems. Best update with conda first (when using Anaconda/Miniconda).

### 2. Python language basics, IPython, and Jupyter Notebooks

* `%run [.py]` - (in IPython) execute the code in .py file in the same process.
* tab completion works both in IPython and Jupyter.
* introspection - put ? after object or function.
    * ?? after name of a function will show the function's source code. 
    * Can be combined with wildcard.

## 2022-02-26

* assigning a variable (or name) is creating a reference to the object on the righthand side of the equals sign.
* when passing objects as arguments to a function, new local variables are created referencing the original objects without copying them. 

## 2022-02-28

* to check if two references refer to the same object, use `is`. Use `is not` if you want to check that two objects are not the same.
* `list` always create new Python list (copy).
* 
