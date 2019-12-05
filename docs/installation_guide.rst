
Installation Guide
==================

So lets see how to get you all set up. As long as this is still much work in progress, I'll not upload this to `PyPI <https://pypi.org/>`_. You have two choices: installing "by hand", or using the `git` command. I strongly recommend using `git` as it facilitates updates and the like. This is the handy way.

Installation with ``pip`` (elegant via ``git``\ )
-------------------------------------------------------

First install ``git``. Linux users just use their respective repos. 

Windows users probably use anaconda and can do

.. code-block:: bash

   conda install -c anaconda git

in the conda shell `as they kindly tell us here <https://anaconda.org/anaconda/git>`_. Otherwise you can probably get it `here <https://git-scm.com/download/win>`.

Then you can simply do

.. code-block:: bash

   pip install git+https://github.com/gboehl/grgrlib
   pip install git+https://github.com/gboehl/econsieve
   pip install git+https://github.com/gboehl/pydsge

Maybe you'd have to use `pip3` instead. If you run it and it complains about missing packages, please let me know so that I can update the `setup.py`!


Installation with ``pip`` (simple)
--------------------------------------

First, be sure that you are on Python 3.x. Then, get the ``econsieve`` and ``grgrlib`` packages:

* https://github.com/gboehl/grgrlib

* https://github.com/gboehl/econsieve

The simplest way is to clone the repository and then from within the cloned folder run (Windows user from the Anaconda Prompt):

.. code-block:: bash

   pip3 install .