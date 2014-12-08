Welcome to Noha's documentation!!!!!
====================================

Contents:
^^^^^^^^^
.. toctree::

   License
   help

Introduction
============
reStructuredText is an easy-to-read, what-you-see-is-what-you-get plaintext markup syntax and parser system. It is useful for in-line program documentation (such as Python docstrings), for quickly creating simple web pages, and for standalone documents.

`Python <http://www.python.com>`_

Code block:
===========
.. code-block:: python

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'

test
====

.. literalinclude:: application.scala
   :language: scala


Team Members:
^^^^^^^^^^^^^
.. toctree::

   Noha
   Amal
   Mohamed

Another simple Header:
======================

This is a simple example:
::

    import math
    print 'import done'


scala
=====
.. code-block:: scala

    import math._
        def intRoot23(num: Int) = {
          val numSquare = num*num
          (cbrt(numSquare) + log(numSquare)).toInt
    }


list and bullets:
=================

* This is a bulleted list.
* It has two items, the second
  item uses two lines. (note the indentation)

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.

bold and italic:
================

*italic text*

**bold text**

table
=====

Simple tables can be written as follows:

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


Image
=====

.. image:: ../images/team.jpg


Colored boxes
=============

.. note:: This is a simple **note** note.

.. warning:: This is a simple **warning** note.


Sidebar
=======

.. sidebar:: Sidebar Title
        :subtitle: Optional Sidebar Subtitle

   Subsequent indented lines comprise
   the body of the sidebar, and are
   interpreted as body elements.

