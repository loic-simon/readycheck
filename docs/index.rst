Welcome to readycheck's documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:


The goal of this module is to allow to add custom checks when accessing class
attributes.

It is designed to build classes that store objects not available at import time
(e.g. later fetched from a distant service).  It avoid us the pain to check if
the connection has been established each time we need these objects: trying to
access them will automagically raise an exception if they are not ready.


API Reference
-------------------------------

.. automodule:: readycheck
   :members:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
