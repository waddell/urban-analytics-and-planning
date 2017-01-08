Preface
===============================================================================

.. contents:: **Contents**
   :local:


About the author
----------------

`Paul Waddell` is a professor of city and regional planning at the University
of California, Berkeley.  His research and teaching focus on planning and modeling
cities, with particular emphasis on the interactive impacts of of land use regulations and
investment in transportation and other infrastructure.


About this book
---------------

This book has been written in |ReST|_ format and generated using the
`rst2html.py` command line available from the docutils_ python package.

If you want to rebuild the html output, from the top directory, type:

.. code-block::

   $ rst2html.py --link-stylesheet --cloak-email-addresses \
                 --toc-top-backlinks --stylesheet=book.css \
                 --stylesheet-dirs=. book.rst book.html

The sources are available from https://github.com/waddell/urban-analytics-and-planning.
                   
.. |ReST| replace:: restructured text
.. _ReST: http://docutils.sourceforge.net/rst.html
.. _docutils: http://docutils.sourceforge.net/

Acknowledgements
----------------
The format and idea for writing it in |ReST|_ format came from this project of Nicholas P. Rougier:
https://github.com/rougier/from-python-to-numpy.  I have shamelessly borrowed his templates and style to
get this project underway.  Besides the formatting, there is no overlap with Rougier's project, however.

Prerequisites
+++++++++++++

The material in this book should not require a strong quantitative or programming background,
but will contain some technical material, hopefully presented in an reasonably accessible way.
More technical treatment will be provided separately.


Conventions
+++++++++++

We will use usual naming conventions. If not stated explicitly, each script
should import numpy, scipy and matplotlib as:

.. code-block:: python
   
   import numpy as np
   import scipy as sp
   import matplotlib.pyplot as plt


We'll use up-to-date versions (at the date of writing, i.e. January, 2017) of the
different packages:

=========== =========
Packages    Version
=========== =========
Python      3.5.2
----------- ---------
Numpy       1.11.2
----------- ---------
Scipy       0.18.1
----------- ---------
Matplotlib  1.5.3
=========== =========

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
<mailto:waddell@berkeley.com>`


License
--------

**Book**

This work is licensed under a `Creative Commons Attribution-Non Commercial-Share
Alike 4.0 International License <https://creativecommons.org/licenses/by-nc-sa/4.0/>`_. You are free to:

* **Share** — copy and redistribute the material in any medium or format
* **Adapt** — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.

**Code**

The code is licensed under the `OSI-approved BSD 2-Clause License
<LICENSE-code.txt>`_.


.. --- Links ------------------------------------------------------------------
.. _Paul Waddell:     http://ced.berkeley.edu/ced/faculty-staff/paul-waddell

.. ----------------------------------------------------------------------------

