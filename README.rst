==============
pymt_nwm
==============


.. image:: https://img.shields.io/badge/CSDMS-Basic%20Model%20Interface-green.svg
        :target: https://bmi.readthedocs.io/
        :alt: Basic Model Interface

.. .. image:: https://img.shields.io/badge/recipe-pymt_nwm-green.svg
        :target: https://anaconda.org/conda-forge/pymt_nwm

.. image:: https://readthedocs.org/projects/pymt-nwm/badge/?version=latest
        :target: https://pymt-nwm.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://img.shields.io/badge/License-MIT-blue.svg
        :target: hhttps://github.com/gantian127/pymt_nwm/blob/master/LICENSE


pymt_nwm is a package that converts `nwm package <https://github.com/gantian127/nwm>`_ into a reusable,
plug-and-play data component for `PyMT <https://pymt.readthedocs.io/en/latest/?badge=latest>`_ modeling framework.
This allows the National Water Model datasets to be easily coupled with other datasets or models that expose
a `Basic Model Interface <https://bmi.readthedocs.io/en/latest/>`_.

---------------
Installing pymt
---------------

Installing `pymt` from the `conda-forge` channel can be achieved by adding
`conda-forge` to your channels with:

.. code::

  conda config --add channels conda-forge

*Note*: Before installing `pymt`, you may want to create a separate environment
into which to install it. This can be done with,

.. code::

  conda create -n pymt python=3
  conda activate pymt

Once the `conda-forge` channel has been enabled, `pymt` can be installed with:

.. code::

  conda install pymt

It is possible to list all of the versions of `pymt` available on your platform with:

.. code::

  conda search pymt --channel conda-forge

-------------------------
Installing pymt_nwm
-------------------------

To install `pymt_nwm`,

.. code::

  pip install pymt_nwm

