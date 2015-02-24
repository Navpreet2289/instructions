Running tests
=============

To run tests you will need these packages:

* coverage
* nose

For your convenience they are all listed in the ``requirements.txt`` file in this directory. If
you are running Python 2.6 you also need to install ``unittest2`` package. After all dependencies
are installed you can run tests with this command:

.. code-block:: bash

   $ nosetests --with-coverage --cover-erase --cover-package=instructions
