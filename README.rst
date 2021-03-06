.. image:: http://pybee.org/static/images/defaultlogo.png
    :width: 72px
    :target: https://pybee.org/

Legless Lizard
==============

Legless Lizard is a setuptools mock of `Python for .NET
<https://github.com/pythonnet/pythonnet>`__.

Python for .NET is a great library for interfacing Python with .NET, but it
can't be installed (easily) on non-Windows platforms. This can be a problem if
you want to run non-platform specific tests of a package that has `pythonnet`
listed in dependencies.

Legless Lizard registers itself as `pythonnet`, fooling PyPI into thinking
Python for .NET is already installed.

What does the name mean?
------------------------

A `legless lizard <https://en.wikipedia.org/wiki/Legless_lizard>`__ may *look*
like a snake, but doesn't behave like a snake at all.

Usage
-----

Legless Lizard can't be installed from PyPI (because it masquerades as a different package). To install it, run::

    > pip install git+https://github.com/pybee/legless-lizard.git

Community
---------

Legless Lizard is part of the `BeeWare suite`_. You can talk to the community through:

* `@pybeeware on Twitter`_

* The `pybee/general`_ channel on Gitter.

We foster a welcoming and respectful community as described in our
`BeeWare Community Code of Conduct`_.

Contributing
------------

If you experience problems with Python.net mock, `log them on GitHub`_. If you
want to contribute code, please `fork the code`_ and `submit a pull request`_.

.. _BeeWare suite: http://pybee.org
.. _@pybeeware on Twitter: https://twitter.com/pybeeware
.. _pybee/general: https://gitter.im/pybee/general
.. _BeeWare Community Code of Conduct: http://pybee.org/community/behavior/
.. _log them on Github: https://github.com/pybee/legless-lizard/issues
.. _fork the code: https://github.com/pybee/legless-lizard
.. _submit a pull request: https://github.com/pybee/legless-lizard/pulls
