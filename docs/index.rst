Welcome to autodoc-example's documentation!
===========================================

This project servers as an example project to demostrate
how to use the *sphinx* documentation generator for Python.

Simple use
----------
This is a section within a *sphinx* .rst file.

You can also include code snippets::

    import pkg
    x = pkg.Pkg()
    x.foo()

Another Section
----------------
Here is another section. Now I'll include a list.

- one fish
- two fish
- red fish
- blue fish

Link Example
-------------

Here is an example of a link in reStructuredText `GitHub <https://github.com>`_.

Reference Example
------------------

For more information about how to use this library, see the :ref:`api`.

.. toctree::
   :maxdepth: 2
   :glob:
   :caption: Flare

   *

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`