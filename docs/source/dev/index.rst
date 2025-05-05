Development Guide
=================

Here you will find information on how to contribute to the project.
If you are looking for information on how to use the project,
please refer to the `API Reference <../ref/index.html>`_ or the `Tutorials <../tutorial/index.html>`_ for a quick start.

.. note::

   This section is not complete yet.

To develop the project, clone the repository and install the project in editable mode.

.. code-block:: console

   $ git clone https://github.com/technic960183/spherimatch.git
   $ cd spherimatch
   $ pip install -e .[dev]

To test the project, run the following command.

.. code-block:: console

   $ python -m unittest

You should see ``OK (skipped=3)`` if all tests pass.

.. toctree::
   :maxdepth: 2

   spherimatch
