===============================
README for sphinxcontrib-jsmath
===============================

sphinxcontrib-jsmath is a sphinx extension which renders display math in HTML
via JavaScript.

Installing
==========

Install from PyPI::

   pip install -U sphinxcontrib-jsmath

Usage
=====

This extension works just as the `MathJax extension`_ does, but uses the older
package jsMath_.  It provides this config value:

jsmath_path
   :type: `str`
   :default: `''`

   The path to the JavaScript file to include in the HTML files in order to load
   JSMath.

   The path can be absolute or relative; if it is relative, it is relative to
   the ``_static`` directory of the built docs.

   For example, if you put JSMath into the static path of the Sphinx docs, this
   value would be ``jsMath/easy/load.js``.  If you host more than one
   Sphinx documentation set on one server, it is advisable to install jsMath in
   a shared location.

.. _MathJax extension: https://www.sphinx-doc.org/en/master/usage/extensions/math.html#module-sphinx.ext.mathjax
.. _jsMath: https://www.math.union.edu/~dpvc/jsmath/


Contributing
============

See `CONTRIBUTING.rst`__

.. __: https://github.com/sphinx-doc/sphinx/blob/master/CONTRIBUTING.rst
