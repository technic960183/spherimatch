Installation
============

You can install **spherimatch** by cloning the `repository <https://github.com/technic960183/spherimatch>`_.

.. code-block:: console

   $ git clone https://github.com/technic960183/spherimatch.git

.. note::
   ``pip install`` will be supported in the future after we collect enough feedback from the users.
   Please feel free to try this package and give us feedback. Your feedback is valuable to us.

If you encounter the error:

.. code-block:: console

   ModuleNotFoundError: No module named 'spherimatch'

Please add the path of the cloned directory to ``sys.path`` by running the following code before importing the module:

.. code-block:: python

   import sys
   path_to_spherimatch = '/your_path_to/spherimatch'
   sys.path.append(path_to_spherimatch)

Check if the installation is successful by importing the module:

.. code-block:: python

   from spherimatch import xmatch
   print(xmatch.__module__)

If the output is ``spherimatch.xmatch``, congratulations! You have successfully installed **spherimatch**.
