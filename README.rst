AOtools
=======

Useful tools for Adaptive Optics analysis for the Python Programming Language

.. image:: https://travis-ci.org/AOtools/aotools.svg?branch=master
   :target: https://travis-ci.org/AOtools/aotools

.. image:: https://ci.appveyor.com/api/projects/status/hru9gl4jekcwtm6l/branch/master?svg=true
   :target: https://ci.appveyor.com/project/Soapy/aotools/branch/master

.. image:: https://codecov.io/gh/AOtools/aotools/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/AOtools/aotools

.. image:: http://readthedocs.org/projects/aotools/badge/?version=latest
   :target: http://aotools.readthedocs.org/en/latest/?badge=latest
  
.. image:: https://img.shields.io/badge/dynamic/json.svg?color=bright%20green&label=Downloads%2FMonth&query=%24.data.last_month&url=https%3A%2F%2Fpypistats.org%2Fapi%2Fpackages%2Faotools%2Frecent
   :target: https://pypistats.org/packages/aotools


Required libraries
------------------

.. code-block:: python

   python
   SciPy
   NumPy
   matplotlib

Installation
------------

As everything is just pure python, you don't really need to "install" at all. To be able to use the tools from anywhere on your system,
add the ``aotools`` directory to your ``PYTHONTPATH``.
Alternatively you can use one of the methods below.

Pip
+++

AOtools can be installed using pip:

.. code-block:: python

    pip install aotools

(which may require admin or root privileges)

From Source
+++++++++++
Alternatively, to install the tools to your system python distribution from source, run:

.. code-block:: python

    python setup.py install

(which may require admin or root privileges) from the ``aotools`` directory.

Documentation
+++++++++++++
Full documentation is hosted by  `Read the Docs <http://aotools.readthedocs.io/en/stable/>`_
