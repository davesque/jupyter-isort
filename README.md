# Jupyter isort

A jupyter notebook extension used to move all imports in  the first code cell and sort them using [isort](https://github.com/timothycrosley/isort)

**pre-requisites:** of course, you must have some of the corresponding packages installed:

```
pip install isort [--user]
```

Then the extension provides

- a toolbar button
- a keyboard shortcut for sorting imports in all code-cell (default: Alt-S)


## Installation

If you use [jupyter-contrib-nbextensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions), proceed as usual.

Otherwise, you can still install/try the extension from personal repo, using
```
jupyter nbextension install https://github.com/benjaminabel/jupyter-isort/archive/master.zip --user
jupyter nbextension enable jupyter-isort-master/jupyter-isort
```
# Forked From

[Jupyter autopep8](https://github.com/kenkoooo/jupyter-autopep8): PEP8 formatter for Jupyter Notebook
