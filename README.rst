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
.. |docs| image:: https://readthedocs.org/projects/vis2aud/badge/?style=flat
    :target: https://readthedocs.org/projects/vis2aud
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/timothysit/vis2aud.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/timothysit/vis2aud

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/timothysit/vis2aud?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/timothysit/vis2aud

.. |requires| image:: https://requires.io/github/timothysit/vis2aud/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/timothysit/vis2aud/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/timothysit/vis2aud/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/timothysit/vis2aud

.. |version| image:: https://img.shields.io/pypi/v/vis2aud.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/vis2aud

.. |wheel| image:: https://img.shields.io/pypi/wheel/vis2aud.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/vis2aud

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/vis2aud.svg
    :alt: Supported versions
    :target: https://pypi.org/project/vis2aud

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/vis2aud.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/vis2aud

.. |commits-since| image:: https://img.shields.io/github/commits-since/timothysit/vis2aud/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/timothysit/vis2aud/compare/v0.0.0...master



.. end-badges

Conversion of 2D visual images to 1D audio by mapping pixel location to frequency space

* Free software: MIT license

Installation
============

::

    pip install vis2aud

You can also install the in-development version with::

    pip install https://github.com/timothysit/vis2aud/archive/master.zip


Documentation
=============


https://vis2aud.readthedocs.io/


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
