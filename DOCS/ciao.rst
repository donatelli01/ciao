The parrot module
=================

.. testsetup:: *

   import parrot

The parrot module is a module about parrots.

Doctest example:

.. doctest::

   >>> parrot.voom(3000)
   This parrot wouldn't voom if you put 3000 volts through it!

Test-Output example:

.. testcode::

   parrot.voom(3000)

This would output:

.. testoutput::

   This parrot wouldn't voom if you put 3000 volts through it!
   :orphan:

.. _example_google:

Example Google Style Python Docstrings
======================================

.. seealso::

   :ref:`example_numpy`

.. only:: builder_html

   Download: :download:`example_google.py <example_google.py>`

.. literalinclude:: example_google.py
   :language: python
