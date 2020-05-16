.. _header:

*********
flat-tree
*********

.. image:: https://img.shields.io/badge/license-GPL-brightgreen.svg
   :target: LICENSE
   :alt: Repository license

.. image:: https://badge.fury.io/py/flat-tree.svg
   :target: https://badge.fury.io/py/flat-tree
   :alt: PyPI Package

.. image:: https://drone.autonomic.zone/api/badges/hyperpy/flat-tree/status.svg
   :target: https://drone.autonomic.zone/hyperpy/flat-tree
   :alt: Drone CI result

.. image:: https://readthedocs.org/projects/flat-tree/badge/?version=latest
   :target: https://flat-tree.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

.. image:: http://img.shields.io/liberapay/patrons/decentral1se.svg?logo=liberapay
   :target: https://liberapay.com/decentral1se
   :alt: Support badge

.. _introduction:

Utilities for navigating flat trees
-----------------------------------

Flat Trees are the core data structure that power Hypercore feeds. They allow
us to deterministically represent a tree structure as a vector. This is
particularly useful because vectors map elegantly to disk and memory.

Because Flat Trees are deterministic and pre-computed, there is no overhead to
using them. In effect this means that Flat Trees are a specific way of indexing
into a vector more than they are their own data structure. This makes them
uniquely efficient and convenient to implement in a wide range of languages.

.. _documentation:

Documentation
*************

* `flat-tree.readthedocs.io`_

.. _flat-tree.readthedocs.io: https://flat-tree.readthedocs.io
