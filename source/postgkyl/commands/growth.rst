.. _pg_cmd_growth:

growth
------

.. contents::

Function description
^^^^^^^^^^^^^^^^^^^^

Command line usage
^^^^^^^^^^^^^^^^^^

.. code-block:: bash

   $ pgkyl growth --help
   Usage: pgkyl growth [OPTIONS]

     Fit e^(2x) to the data

   Options:
     -g, --guess <FLOAT FLOAT>...  Specify initial guess
     -p, --plot                    Plot the data and fit
     --minn INTEGER                Set minimal number of points to fit
     --maxn INTEGER                Set maximal number of points to fit
     --help                        Show this message and exit.
