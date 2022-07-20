Welcome to astro_py_scripts!
================================

**astro_py_scripts** is a collection of useful scripts and tricks that can speed up or improve the quality of your Python code in various fields of astronomy.

Contents
========

.. toctree::
   :maxdepth: 2
   :caption: NumPy

   notebooks/demo.ipynb


.. toctree::
   :maxdepth: 2
   :caption: MatPlotLib

   notebooks/demo.ipynb

How to contribute?
==================

**astro_py_scripts** is deployed on `GitHub <https://github.com/EnthalpyBill/astro_py_scripts>`_. You are more than welcome to contribute your own script! Just email us your script, or raise an issue/pull request. We recommend contributors to follow the following format:

Format
------

We strongly recommend you to put everythong in a single `Jupyter Notebook <https://jupyter.org/>`_. However, if extra files are needed, you should put all files in one folder. Once being deployed, your notebook will be stored as::

   docs/source/notebooks/<name_of_your_folder>/<name_of_your_notebook>.ipynb

Please also put it in a folder even if you only have one notebook. Some of our post-processing codes rely on such hierarchy.

**It is super important to make sure everyone can run your notebook on their own devices!** So, remember to restart your notebook before submitting it. Fix any bug if the notebook cannot run smoothly. Also, we recommend you to write down the versions of your Python and any packages you have imported at the begining of your notebook. 

License
-------

Since **astro_py_scripts** is completely open source, you are recommended to have an `open source license <https://opensource.org/licenses>`_. Normally, the formal license file should be placed in the same folder as your notebook::

   docs/source/notebooks/<name_of_your_folder>/LICENSE

And, you can also briefly mention your license information in the notebook. Write something like "The copyright of this notebook belongs to <your name> under the MIT license (see LICENSE)".

Please make sure your license is compatible with **astro_py_scripts**, which uses the MIT license. Clearly, a GPL license is not compatible. Click `here <https://opensource.org/licenses>`_ for more information about licenses.

Contribute in a GitHub style
----------------------------

We maintain **astro_py_scripts** with `GitHub Flow <https://docs.github.com/en/get-started/quickstart/github-flow>`_, which is a simple and effective workflow suitable for small projects like **astro_py_scripts**! 

You can learn GitHub Flow with `this video <https://www.youtube.com/watch?v=juLIxo42A_s>`_. It's a long video but don't be afraid! The standard GitHub Flow includes many subtle operations to avoid any potential conflict with other contributers. However, since our project is not that popular (at least for now), you are not likely to face a lot of annoying conflicts. You may alternatively want to watch this `shoter video <https://www.youtube.com/watch?v=GgjIvUrOpmg>`_.



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
