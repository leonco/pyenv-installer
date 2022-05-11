pyenv installer
===============

This tool installs `pyenv <https://github.com/pyenv/pyenv>`__ and friends. It is inspired by `rbenv-installer <https://github.com/rbenv/rbenv-installer>`__.

Prerequisites
----
`Git <https://git-scm.com/>`__ installed.

In general, compiling your own Python interpreter requires the installation of the
appropriate libraries and packages.  The `installation wiki
<https://github.com/pyenv/pyenv/wiki/Common-build-problems>`__ provides a list of these for common
operating systems.


Installation / Update / Uninstallation
--------------------------------------
Once prerequisites have been installed correctly: 

Install:
~~~~
If you wish to install a specific release of Pyenv rather than the latest head, set the ``PYENV_GIT_TAG`` environment variable (e.g. ``export PYENV_GIT_TAG=v2.2.5``).

.. code:: bash

    curl -L https://github.91chi.fun//https://github.com/leonco/pyenv-installer/raw/master/bin/pyenv-installer | bash

Restart your shell so the path changes take effect:

.. code:: bash

    exec $SHELL

You can now begin using pyenv.

License
-------

MIT - see `License file <LICENSE>`_.
