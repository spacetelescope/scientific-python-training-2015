STSCI's Scientific Python Course 2015
=====================================

Introduction
------------

This is a data-oriented approach to Python. The focus is on showing one how to
quickly get up and running reading, manipulating and displaying data learning
the minimum amount of Python initially. Gradually, more Python language is
introduced as more complex examples are worked through.

No Python background is required.

Course Material
---------------

Video of all the presentations is available
`on the STScI webpage <https://webcast.stsci.edu/webcast/searchresults.xhtml?searchtype=20&eventid=184&sortmode=1>`_.

Homework and demo IPython Notebooks are available in the
`homework_notebooks <./homework_notebooks>`_ and
`lecture_notebooks <./lecture_notebooks>`_ directories.

Homeworks are due the end of Tuesday before the Problem Review date

Schedule
--------

============== ============== ==========
Session 1
----------------------------------------
Work Session   Jan 16, 3 PM   Cafe Con
Problem Review Jan 23, 3 PM   Cafe Con
============== ============== ==========

============== ============== ==========
Session 2
----------------------------------------
Work Session   Jan 30, 3 PM   Cafe Con
Problem Review Feb 6,  3 PM   Cafe Con
============== ============== ==========

============== ============== ==========
Session 3
----------------------------------------
Work Session   Feb 13, 3 PM   Cafe Con
Problem Review Feb 20, 3 PM   Cafe Con
============== ============== ==========

============== ============== ==========
Session 4
----------------------------------------
Work Session   Feb 27, 3 PM   Cafe Con
Problem Review Mar  6, 3 PM   Cafe Con
============== ============== ==========

============== ============== ==========
Session 5
----------------------------------------
Work Session   Mar 13, 3 PM   Cafe Con
Problem Review Mar 20, 3 PM   Cafe Con
============== ============== ==========

============== ============== ==========
Session 6
----------------------------------------
Work Session   Mar 27, 3 PM   Cafe Con
Problem Review Apr  3, 3 PM   Cafe Con
============== ============== ==========

Course Outline
--------------

**Session 1: Introduction**

- Goals
- Sources of information
- IPython Notebook basics
- Examples of capabilities

  - Reading data
  - Displaying images
  - Plotting data

- General Python practicalities
- Exercises part of all sessions

**Session 2: Basic Tools**

Introduction to:

- pyfits
- numpy
- matplotlib
- ascii tables

**Session 3: Source finding example part 1**

- Calling IRAF tasks, manipulating and displaying results
- Python topics covered:

  - strings and lists
  - writing functions, modules, and scripts

**Session 4: Source finding example part 2**

- Doing completeness tests on previous results and displaying results
- Python topics covered:

  - intermediate numpy
  - looping, conditional expressions
  - random distributions

**Session 5: STIS Long-Slit spectral extraction example**

- Identify location of spectral sources in STIS long-slit data,
  call xxx with fit locations
- Python topics covered

  - fitting
  - numpy techniques and libraries

**Session 6: Data elsewhere**

- Doodle poll for potential topics is at http://doodle.com/78vi8b6rzruarcwb

Information on Scientific Python
--------------------------------

There are many sources of information. That's sometime part of the problem (as
compared to integrated tools like IDL or IRAF).

Using Python for Astronomy
~~~~~~~~~~~~~~~~~~~~~~~~~~

- `AstroPy <http://www.astropy.org>`_:
  relatively new; software specifically for astronomy (with documentation)
- `Using Python for Interactive Data Analysis
  <http://stsdas.stsci.edu/perry/pydatatut.pdf>`_: short book by STSCI/SSB
- `Python4Astronomers <http://python4astronomers.github.com/>`_:
  tutorials by CfA

Using Python for Science and Engineering
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- `Numpy and SciPy <http://scipy.org>`_: general website containing software
  and documentation for scientific python
- `matplotlib <http://matplotlib.org>`_: 2-d plotting (and some 3-d capability)
- `IPython <http://ipython.org>`_: enhanced interactive python environments

Books
~~~~~

- `Python for Data Analysis by Wes McKinney <http://shop.oreilly.com/product/0636920023784.do>`_
- `SciPy and NumPy by Eli Bressert <http://shop.oreilly.com/product/0636920020219.do>`_
- A Primer on Scientific Programming with Python by Hans Petter Langtangen
  (Also: Python Scripting for Computational Science)
- Beginning Python Visualization: Crafting Visual Transformation Scripts
  by Shai Vaingast
- Matplotlib for Python Developers by Sandro Tosi
- Numpy 1.5 Beginner's Guide by Ivan Idris
- Numerical Methods in Engineering with Python by Jaan Kiusalaas

Information on General Python
-----------------------------

Online
~~~~~~

- `Python <http://python.org>`_: The Python mother ship
- `Standard Python Docs <http://www.python.org/doc/>`_
- `Standard Python Library <http://docs.python.org/library/>`_:
  Bookmark this!

Books
~~~~~

There are a large number of books about Python.

- `Python Book Reviews <http://www.awaretek.com/book.html>`_

Python 2 vs. Python 3
---------------------

These two versions of Python differ in non-trivial ways. Eventually we expect
that we will migrate to Python 3 (the process has been underway for a while),
but we expect it will still be a couple years before a significant number of
science users will be using Python 3. This course will use only Python 2 for
all its examples. Discussions regarding the differences are beyond the scope of
this course.

Installing AstroPy
------------------

Ureka
~~~~~

For the easiest install use Ureka: http://ssb.stsci.edu/ssb_software.shtml (and install the SSBX version)

