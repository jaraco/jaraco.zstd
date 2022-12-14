.. image:: https://img.shields.io/pypi/v/jaraco.zstd.svg
   :target: https://pypi.org/project/jaraco.zstd

.. image:: https://img.shields.io/pypi/pyversions/jaraco.zstd.svg

.. image:: https://github.com/jaraco/jaraco.zstd/workflows/tests/badge.svg
   :target: https://github.com/jaraco/jaraco.zstd/actions?query=workflow%3A%22tests%22
   :alt: tests

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/psf/black
   :alt: Code style: Black

.. .. image:: https://readthedocs.org/projects/skeleton/badge/?version=latest
..    :target: https://skeleton.readthedocs.io/en/latest/?badge=latest

.. image:: https://img.shields.io/badge/skeleton-2023-informational
   :target: https://blog.jaraco.com/skeleton

Extract files from a ``.tar.zstd``::

    python -m jaraco.zstd --extract filename.tar.zstd

Usage::

    python -m jaraco.zstd --help
    usage: zstd.py [-h] -e SOURCE [--out-dir OUT_DIR]

    options:
      -h, --help            show this help message and exit
      -e SOURCE, --extract SOURCE
      --out-dir OUT_DIR
