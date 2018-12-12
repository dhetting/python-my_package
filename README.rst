========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|



.. |version| image:: https://img.shields.io/pypi/v/my-package.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/my-package

.. |commits-since| image:: https://img.shields.io/github/commits-since/dhetting/python-my_package/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dhetting/python-my_package/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/my-package.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/my-package

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/my-package.svg
    :alt: Supported versions
    :target: https://pypi.org/project/my-package

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/my-package.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/my-package


.. end-badges

An example package. Generated with cookiecutter-pylibrary.

* Free software: BSD 2-Clause License

Installation
============

::

    pip install my-package

Documentation
=============


To use the project:

.. code-block:: python

    import my_package
    my_package.longest()


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
