elephantsql\_cli
================

|PyPI version|

CLI implementation of the ElephantSQL API

Usage:
------

Install using pip

::

    $ pip install elephantsql-cli

Register your API token

::

    $ elephant register  # this will prompt you to add your API token

List backups:

::

    $ elephant backups [--db=my_database]

Create backups:

::

    $ elephant backup [--db=my_database]

Restore backup:

::

    $ elephant restore backup_id

List alarms:

::

    $ elephant alarms

Project Features
----------------

-  `elephantsql\_cli <http://www.comingsoon.net>`__
-  a starter `Click <http://click.pocoo.org/5/>`__ command-line
   application
-  automated unit tests you can run with
   `pytest <https://docs.pytest.org/en/latest/>`__
-  a `Sphinx <http://www.sphinx-doc.org/en/master/>`__ documentation
   project

Getting Started
---------------

The project's documentation contains a section to help you `get
started <https://elephantsql-cli.readthedocs.io/en/latest/getting_started.html>`__
as a developer or user of the library.

Development Prerequisites
-------------------------

If you're going to be working in the code (rather than just using the
library), you'll want a few utilities.

-  `GNU Make <https://www.gnu.org/software/make/>`__
-  `Pandoc <https://pandoc.org/>`__

Resources
---------

Below are some handy resource links.

-  `Project Documentation <http://elephantsql-cli.readthedocs.io/>`__
-  `Click <http://click.pocoo.org/5/>`__ is a Python package for
   creating beautiful command line interfaces in a composable way with
   as little code as necessary.
-  `Sphinx <http://www.sphinx-doc.org/en/master/>`__ is a tool that
   makes it easy to create intelligent and beautiful documentation,
   written by Geog Brandl and licnsed under the BSD license.
-  `pytest <https://docs.pytest.org/en/latest/>`__ helps you write
   better programs.
-  [GNU Make] is a tool which controls the generation of executables and
   other non-source files of a program from the program's source files.

Authors
-------

-  **Malik S** - *Initial work* -
   `github <https://github.com/flyudvik>`__

See also the list of
`contributors <https://github.com/flyudvik/elephantsql_cli/contributors>`__
who participated in this project.

LicenseMIT License
------------------

Copyright (c) flyudvik

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

.. |PyPI version| image:: https://badge.fury.io/py/elephantsql-cli.svg
   :target: https://badge.fury.io/py/elephantsql-cli
