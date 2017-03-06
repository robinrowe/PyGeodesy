=========
PyGeodesy
=========

A pure Python implementation of geodesy tools for various ellipsoidal and
spherical earth models using trigonometric and vector-based methods.

Transcribed from JavaScript originals by *(C) Chris Veness 2005-2016*
and published under the same MIT Licence [*]_.

For more information and further details see:

- <http://github.com/chrisveness/geodesy/>
- <http://www.movable-type.co.uk/scripts/latlong.html>
- <http://www.movable-type.co.uk/scripts/latlong-vincenty.html>
- <http://www.movable-type.co.uk/scripts/latlong-vectors.html>

Also included are conversions to and from UTM coordinates and MGRS
and OSGR grid references, see:

- <http://www.movable-type.co.uk/scripts/latlong-utm-mgrs.html>
- <http://www.movable-type.co.uk/scripts/latlong-os-gridref.html>

An additional module provides Lambert conformal conic projections
and positions, transcribed from:

- <https://pubs.er.USGS.gov/djvu/PP/PP_1395.pdf> pp 107-109.

The Python code has been statically `checked <http://code.activestate.com/recipes/546532/>`_
with `PyChecker <https://pypi.python.org/pypi/pychecker>`_,
`PyFlakes <https://pypi.python.org/pypi/pyflakes>`_,
`PyCodeStyle <https://pypi.python.org/pypi/pycodestyle>`_ (formerly Pep8),
`McCabe <https://pypi.python.org/pypi/mccabe>`_ on Python 2.7.10 and 2.7.13
and with `Flake8 <https://pypi.python.org/pypi/flake8>`_ on Python 3.6.0.
The tests were run with 64-bit Python 2.6.9, 2.7.10, 2.7.13, 3.5.2, 3.5.3
and 3.6.0, but only on MacOS 10.10 Yosemite, MacOS 10.11 El Capitan and/or
MacOS 10.12.2 and 10.12.3 Sierra.

The ``zip`` and ``tar`` files in directory ``dist`` each contain the entire
PyGeodesy distribution for installation with the enclosed ``setup.py`` file.

The documentation was generated by `Epydoc <https://pypi.python.org/pypi/epydoc>`_
using command line
``epydoc --html --no-private --no-source --name=PyGeodesy --url=... -v geodesy``

Several function and method names differ from the JavaScript version.
Documentation tag **JS name:** shows the original JavaScript name.

\_\_

.. [*] `MIT License <https://opensource.org/licenses/MIT>`_ text follows:

 Copyright (C) 2016-2017 -- mrJean1@Gmail.com

 Permission is hereby granted, free of charge, to any person obtaining a
 copy of this software and associated documentation files (the "Software"),
 to deal in the Software without restriction, including without limitation
 the rights to use, copy, modify, merge, publish, distribute, sublicense,
 and/or sell copies of the Software, and to permit persons to whom the
 Software is furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included
 in all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
 OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
 THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR
 OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
 ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
 OTHER DEALINGS IN THE SOFTWARE.

*Last updated: Mar 06, 2017.*