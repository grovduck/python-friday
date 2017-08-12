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
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-friday/badge/?style=flat
    :target: https://readthedocs.org/projects/python-friday
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/grovduck/python-friday.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/grovduck/python-friday

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/grovduck/python-friday?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/grovduck/python-friday

.. |requires| image:: https://requires.io/github/grovduck/python-friday/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/grovduck/python-friday/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/grovduck/python-friday/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/grovduck/python-friday

.. |codecov| image:: https://codecov.io/github/grovduck/python-friday/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/grovduck/python-friday

.. |version| image:: https://img.shields.io/pypi/v/friday.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/friday

.. |commits-since| image:: https://img.shields.io/github/commits-since/grovduck/python-friday/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/grovduck/python-friday/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/friday.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/friday

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/friday.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/friday

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/friday.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/friday


.. end-badges

Spending a Friday evening coding

* Free software: BSD license

Installation
============

::

    pip install friday

Documentation
=============

https://python-friday.readthedocs.io/

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
