Preface
===============================================================================

.. contents:: **Contents**
   :local:


About the authors
-----------------

`Paul Waddell`_ is a professor of city and regional planning at the University
of California, Berkeley.  His research and teaching focus on planning and modeling
cities, with particular emphasis on the interactive impacts of of land use regulations and
investment in transportation and other infrastructure.

`Samuel Maurer` is a Ph.D. student in city planning at the University of California, Berkeley.
He has worked on urban mapping, simulation modeling, and economic forecasting for a variety
of public and private sector organizations. His interests include land use typologies and travel behavior.


About this book
---------------

The origin of this book is as a set of notes for a graduate course in land and housing markets in the masters program
in the Department of City and Regional Planning at the University of California, Berkeley.  The aim of the course
is to engage students in theory and data that helps to understand how markets and governments interact to shape cities
and metropolitan regions, with a special focus on land and housing markets.

Prerequisites
+++++++++++++

The material in this book should not require a strong quantitative or programming background,
but will contain some technical material, hopefully presented in an reasonably accessible way.
More technical treatment will be provided separately.



Formatting
++++++++++++++++

This book has been written in |ReST|_ format and generated using the
`rst2html.py` command line available from the docutils_ python package.
The format and idea for writing it in |ReST|_ format came from this project of Nicholas P. Rougier:
https://github.com/rougier/from-python-to-numpy.  I have shamelessly borrowed his templates and style to
get this project underway.  Besides the formatting, there is no overlap with Rougier's project, however.


If you want to rebuild the html output, from the top directory, type:

.. code-block::

   $ rst2html.py --link-stylesheet --cloak-email-addresses \
                 --toc-top-backlinks --stylesheet=book.css \
                 --stylesheet-dirs=. book.rst book.html

The sources are available from https://github.com/waddell/urban-analytics-and-planning.

.. |ReST| replace:: restructured text
.. _ReST: http://docutils.sourceforge.net/rst.html
.. _docutils: http://docutils.sourceforge.net/



How to contribute
+++++++++++++++++

If you want to contribute to this book, you can:

* Review chapters (please contact me)
* Report issues (https://github.com/waddell/urban-analytics-and-planning/issues)
* Suggest improvements (https://github.com/waddell/urban-analytics-and-planning/pulls)
* Star the project (https://github.com/waddell/urban-analytics-and-planning)

Publishing
++++++++++

If you're an editor interested in publishing this book, you can `contact me
<mailto:waddell@berkeley.com>`_


**Code**

The code is licensed under the `OSI-approved BSD 2-Clause License
<LICENSE-code.txt>`_.


.. --- Links ------------------------------------------------------------------
.. _Paul Waddell:     http://ced.berkeley.edu/ced/faculty-staff/paul-waddell

.. ----------------------------------------------------------------------------

