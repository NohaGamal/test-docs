title
#####

title
*****

title
=====

title
-----

title
^^^^^

title
"""""

Contents
========

.. toctree::

   help
   License

code block
==========

.. code-block:: scala

   import math._
        def intRoot23(num: Int) = {
          val numSquare = num*num
          (cbrt(numSquare) + log(numSquare)).toInt
   }

Include scala file
==================

.. literalinclude:: application.scala
   :language: scala

bullets and list
================

* this is a bulletes list
* two

1. one
2. two

*italic* 

**build**

link
====

`Python <www.python.com>`_

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

Image
=====

.. image:: ../images/team.jpg

Sidebar
=======

.. sidebar:: Sidebar Title

   Subsequent indented lines comprise
   the body of the sidebar, and are
   interpreted as body elements.


colored boxs
============

.. note:: this is simple note.

.. warning:: this is a simple **warning**.

