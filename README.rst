AwkwardQL - SQL-like language for awkward arrays
================================================

|GitHub Actions Status: CI|
|Binder|
|PyPI version|
|Supported Python versions|

.. inclusion-marker-1-do-not-remove

A SQL-like language for doing set operations on data in Awkward Arrays.

.. inclusion-marker-1-5-do-not-remove

This is derived from and inspired by the `demo <https://github.com/jpivarski/PartiQL>`_ by Jim Pivarski (PartiQL) and targets awkward 1.0.

We will start out focusing on particle physics uses cases and see how far it goes from there. :-)

.. inclusion-marker-2-do-not-remove

Installation
============

Install coffea like any other Python package:

.. code-block:: bash

    pip install awkwardql

or similar (use ``sudo``, ``--user``, ``virtualenv``, or pip-in-conda if you wish).

Strict dependencies
===================

- `Python <http://docs.python-guide.org/en/latest/starting/installation/>`__ (3.6+)

The following are installed automatically when you install coffea with pip:

- `awkward1 <https://github.com/scikit-hep/awkward-array>`__ to manipulate complex-structured columnar data, such as jagged arrays;
- `numba <https://numba.pydata.org/>`__ just-in-time compilation of python functions;
- `lark <https://lark-parser.readthedocs.io/en/latest/>`__ a modern and well featured parser/lexer/interpreter engine;
- `numpy <https://scipy.org/install.html>`__ for flat array manipulation;
- `matplotlib <https://matplotlib.org/>`__ as a plotting backend;

.. inclusion-marker-3-do-not-remove

Documentation
=============
Not yet developed, but you should check out the notebooks in this repository!

.. |GitHub Actions Status: CI| image:: https://github.com/lgray/AwkwardQL/workflows/CI/CD/badge.svg
 :target: https://github.com/lgray/AwkwardQL/actions?query=workflow%3ACI%2FCD+branch%3Amaster

.. |Binder| image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/lgray/AwkwardQL/master

.. |PyPI version| image:: https://badge.fury.io/py/awkwardql.svg
 :target: https://badge.fury.io/py/awkwardql

.. |Supported Python versions| image:: https://img.shields.io/pypi/pyversions/awkwardql.svg
 :target: https://pypi.org/project/awkwardql/
