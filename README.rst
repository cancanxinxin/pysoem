PySOEM
======

PySOEM is a Cython wrapper for the Simple Open EtherCAT Master Library (https://github.com/OpenEtherCATsociety/SOEM).

Introduction
------------

PySOEM enables basic system testing of EtherCAT slave devices with Python.

Features

* input process data read and output process data write
* SDO read and write
* EEPROM read and write

Todo

* FoE
* EoE

Beware that real-time applications need some special considerations.

Requirements
------------

Linux
^^^^^

* Python 3
* Cython (installed into your Python distribution)
* GCC (installed on your machine)
* Python scripts that use PySOEM must be executed under administrator privileges

Windows
^^^^^^^

* Python 3
* a 64-bit operating system
* WinPcap


Installation
------------
::

  python -m pip install pysoem

or

::

  pip install pysoem

Consider using a `virtualenv <https://virtualenv.pypa.io/en/stable/>`_.


Usage
-----
Please have a look at the examples on GitHub.


Changes
-------

v0.0.15
^^^^^^^
* SDO info read

v0.0.14
^^^^^^^
* Readme update only

v0.0.13
^^^^^^^
* Initial publication