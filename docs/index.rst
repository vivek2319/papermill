Welcome to papermill
====================

.. image:: https://travis-ci.org/nteract/papermill.svg?branch=master
   :target: https://travis-ci.org/nteract/papermill
.. image:: https://codecov.io/github/nteract/papermill/coverage.svg?branch=master
   :target: https://codecov.io/github/nteract/papermill?branch=master
.. image:: https://readthedocs.org/projects/papermill/badge/?version=latest
   :target: http://papermill.readthedocs.io/en/latest/?badge=latest
.. image:: https://tinyurl.com/ybwovtw2
   :target: https://mybinder.org/v2/gh/nteract/papermill/master?filepath=binder%2Fprocess_highlight_dates.ipynb
.. image:: https://tinyurl.com/y7uz2eh9
   :target: https://mybinder.org/v2/gh/nteract/papermill/master?filepath=binder%2Fcli-simple%2Fcli_example.ipynb
.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/ambv/black

**Papermill** is a tool for parameterizing, executing, and analyzing Jupyter
Notebooks.

Papermill lets you:

* **parameterize** notebooks
* **execute** and **collect** metrics across the notebooks
* **summarize collections** of notebooks

This opens up new opportunities for how notebooks can be used. For example:

- Perhaps you have a financial report that you wish to run with different
  values on the first or last day of a month or at the beginning or end
  of the year, **using parameters** makes this task easier.
- Do you want to run a notebook and depending on its results,
  choose a particular notebook to run next? You can now programmatically
  **execute a workflow** without having to copy and paste from notebook to
  notebook manually.
- Do you have plots and visualizations spread across 10 or more notebooks?
  Now you can choose which plots to programmatically display a **summary**
  **collection** in a notebook to share with others.

Documentation
-------------

These pages guide you through the installation and usage of papermill.

.. toctree::
   :maxdepth: 1

   installation
   usage-workflow
   usage-parameterize
   usage-execute
   usage-recording
   usage-display
   usage-store
   usage-collection
   usage-cli

API Reference
-------------

If you are looking for information about a specific function, class, or method,
this documentation section will help you.

.. toctree::
   :maxdepth: 3

   reference/index.rst
   reference/papermill.tests.rst


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
