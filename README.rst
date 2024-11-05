========
Overview
========

Python wrapper for analyze.rs web api

* Free software: MIT license

Installation
============

::

    pip install analyzers-py

You can also install the in-development version with::

    pip install git+ssh://git@1/analyze-rs/analyzers-py.git@main

Documentation
=============


https://analyzers-py.readthedocs.io/


Development
===========

To run all the tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
