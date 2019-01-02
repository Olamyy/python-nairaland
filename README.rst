========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis|
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|



.. |travis| image:: https://travis-ci.org/olamyy/python-nairaland.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/olamyy/python-nairaland

.. |version| image:: https://img.shields.io/pypi/v/nairaland.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/nairaland

.. |commits-since| image:: https://img.shields.io/github/commits-since/olamyy/python-nairaland/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/olamyy/python-nairaland/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/nairaland.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/nairaland

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/nairaland.svg
    :alt: Supported versions
    :target: https://pypi.org/project/nairaland

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/nairaland.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/nairaland


.. end-badges

Simple Nairaland API able to handle all GET operations on the platform.

* Free software: MIT license

Installation
============

::

    pip install nairaland

Documentation
=============


To use the project:

.. code-block:: python

    import nairaland
    nairaland.longest()


Development
===========

To run the all tests run::

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
