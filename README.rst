========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/Plotwinccdatalogs/badge/?style=flat
    :target: https://readthedocs.org/projects/Plotwinccdatalogs
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/kelupa/Plotwinccdatalogs.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/kelupa/Plotwinccdatalogs

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/kelupa/Plotwinccdatalogs?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/kelupa/Plotwinccdatalogs

.. |requires| image:: https://requires.io/github/kelupa/Plotwinccdatalogs/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/kelupa/Plotwinccdatalogs/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/kelupa/Plotwinccdatalogs/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/kelupa/Plotwinccdatalogs

.. |version| image:: https://img.shields.io/pypi/v/plotwinncclogs.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/plotwinncclogs

.. |commits-since| image:: https://img.shields.io/github/commits-since/kelupa/Plotwinccdatalogs/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/kelupa/Plotwinccdatalogs/compare/v0.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/plotwinncclogs.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/plotwinncclogs

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/plotwinncclogs.svg
    :alt: Supported versions
    :target: https://pypi.org/project/plotwinncclogs

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/plotwinncclogs.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/plotwinncclogs


.. end-badges

A way to plot data logs from Wincc

* Free software: MIT license

Installation
============

::

    pip install plotwinncclogs

Documentation
=============


https://Plotwinccdatalogs.readthedocs.io/


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
