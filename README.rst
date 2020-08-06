========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor|
        |
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/tox-sitepackages-example/badge/?style=flat
    :target: https://readthedocs.org/projects/tox-sitepackages-example
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/dHannasch/tox-sitepackages-example.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/dHannasch/tox-sitepackages-example

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/dHannasch/tox-sitepackages-example?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/dHannasch/tox-sitepackages-example

.. |commits-since| image:: https://img.shields.io/github/commits-since/dHannasch/tox-sitepackages-example/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dHannasch/tox-sitepackages-example/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install tox-sitepackages-example

You can also install the in-development version with::

    pip install https://github.com/dHannasch/tox-sitepackages-example/archive/master.zip


Documentation
=============


https://tox-sitepackages-example.readthedocs.io/


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
