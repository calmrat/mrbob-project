.. image:: https://travis-ci.org/kejbaly2/pyproject.png
   :target: https://travis-ci.org/kejbaly2/pyproject

.. image:: https://coveralls.io/repos/kejbaly2/pyproject.svg
   :target: https://coveralls.io/r/kejbaly2/pyproject


INSTALLATION
============
Example install, using VirtualEnv::

    # install/use python virtual environment
    virtualenv ~/virtenv_pyproject --no-site-packages

    # activate the virtual environment
    source ~/virtenv_pyproject/bin/activate

    # upgrade pip in the new virtenv
    pip install -U pip setuptools virtualenv

    # install this package in DEVELOPMENT mode
    python setup.py develop


CONFIGURATION
=============

Example configuration, eg at `~/.mrbob.ini`::

    COMING SOON


USAGE
=====

    COMING SOON


BUILD DOCS
==========

Example scenario for building docs with sphinx::

    cd docs
    make html


TESTING
=======
Testing is py.test based. Run with::

    py.test tests/ -v


DEVELOPMENT
===========
Install the supplied githooks; eg, ::

    REPO_PATH = '.'
    ln -s $REPO_PATH/_githooks/commit-msg $REPO_PATH/.git/hooks/commit-msg
    ln -s $REPO_PATH/_githooks/pre-commit $REPO_PATH/.git/hooks/pre-commit
