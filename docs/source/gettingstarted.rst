Getting Started
***************

GPkit is a Python package. We assume basic familiarity with Python. If you are new to Python take a look at `Learn Python <http://www.learnpython.org>`_.

GPkit is also a command line tool. This means that you need to be in the terminal (OS X/Linux) or command prompt (Windows) to use it. If you are not familiar with working in the command line, check out this `Learn Code the Hard Way tutorial <http://cli.learncodethehardway.org/book/>`_.

The first thing to do is `install GPkit <installation.html>`_ . Once you have done this, you can start using GPkit in 3 easy steps:

1. Open your command line interface (terminal/Command Prompt)
2. Open a Python interpreter. This can be done by typing either ``python`` (or ``ipython`` if you have Anaconda and like colorful error messages).
3. Type ``import gpkit``

In your command line, this will look something like this::

    $ python
    >>> import gpkit

    $ ipython
    In [1]: import gpkit

From here, you can use GPkit commands to formulate and solve geometric programs. To learn how to do this take a look at the `Basic Commands <basiccommands.html>`_.


Writing GPkit scripts
=====================
Another way to write and solve GPs is to write a scipt and save it as a .py file. To run this file (e.g. ``myscript.py``), type the following in your command line::

    $ python myscript.py

Again, ``ipython`` will also work here.


Basic Commands
==============

.. A list of the most basic commands needed to solve a simple example, like the box example
.. This section should be subdivided, if possible, into the commands for "declaring variables", "constructing constraints", "solving" etc...
.. Simple Example 1
.. The box example using the basic commands listed above. No fewer, no more.
.. Well documented at each step