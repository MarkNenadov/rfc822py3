rfc822py3 - A port of the Python 2.x rfc822 module into Python 3

INTRODUCTION

They removed rfc822, but here is an attempt to make this library
work properly in Python 3 for your convenience.

If you want to support both the built-in module for Python 2 and
this one for Python 3, you can do the following:

try:
    import rfc822
except ImportError:
    import rfc822py3 as rfc822

TODO

- Further testing

AUTHOR

Mark J. Nenadov (2011)
* Essex, Ontario
* Email: <marknenadov@gmail.com> 

LICENSE

This is under the Python Software Foundation License v2. Please
see LICENSE.txt for details.
