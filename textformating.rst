Text Formating
==============

=============
Bold, Italics
=============
Here we start with basics:

I like it when it is *italics*

I see it when it is **boldface**

===========
Code Blocks
===========
Hardcore coding is easy with ``Serial.println("Hello World")``

=====
Lists
=====
* This is a bulleted list.
* It has two items, the second item uses two lines.

1. This is a numbered list.
2. It has two items too.

Another list:

#. This is a numbered list.
#. It has two items too.

Nested List:

* This list
* includes

* a nested list
* and some subitems

* and here the parent list continues

=====================
Terms and Definitions
=====================

term (up to a line of text)
Definition of the term, which must be indented

and can even consist of multiple paragraphs

next term
Description.

| These lines are
| broken exactly like in
| the source file.
|

This is a normal text paragraph. The next paragraph is a code sample::

  It is not processed in any way, except
  that the indentation is removed.

It can span multiple lines.

This is a normal text paragraph again.

=====================
Tables
=====================

+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

=====================
Links and Photos
=====================

This is a paragraph that contains `a link`_.

.. _a link: http://thingforward.io/

.. image:: ioraptor.png

======================
Footnotes and Comments
======================

Footnotes:

Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] Text of the first footnote.
.. [#f2] Text of the second footnote.


Comment:

.. This is a comment.

..
  This whole indented block
  is a comment.

  Still in the comment.


