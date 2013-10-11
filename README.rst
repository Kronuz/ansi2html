ansi2html
=========

A Python tool to convert ANSI/VT100 terminal control colored input to HTML.

Supports regular ANSI colors, indexed colors and 24 bit RGB color codes.


Quickstart
----------

You need Python 2.6 or later.  Python 3 is also supported.

Usage::

    git log --color | python ansi2html.py > git_log.html

Python API::

    from ansi2html import ansi2html
    output = ansi2html('\033[1;32Hello\033[m')


Obligatory
----------

Copyright © 2013 German M. Bravo (Kronuz)

Licensed under the `MIT license`_, reproduced in ``LICENSE``.

.. _MIT license: http://www.opensource.org/licenses/mit-license.php
