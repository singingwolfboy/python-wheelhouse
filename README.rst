python-wheelhouse
=================

Personal collection of `Python wheels`_, hosted on `Github Pages`_.

Adding Wheels
-------------

#. Grab the source code for the Python module you want to make a wheel for.
#. Run ``python setup.py bdist_wheel``. The wheel file should end up
   in the ``dist`` directory.
#. Make a pull request to ``gh-pages`` branch of this repo.

Using Wheels
------------
To use wheels from this wheelhouse, just pass a
``--find-links=https://singingwolfboy.github.io/python-wheelhouse/``
parameter to your ``pip install`` command.


.. _Python wheels: http://wheel.readthedocs.org/en/latest/
.. _Github Pages: https://pages.github.com/
