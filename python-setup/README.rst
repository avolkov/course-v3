=================================
Local machine \w GPU python setup
=================================

Use pyenv -- https://github.com/pyenv/pyenv
The instructions include how to install pre-requisites.

Install Python 3.6.8 version on your system if you haven't already

.. code-block:: sh

    $ pyenv install 3.6.8

Create Python 3.6.6 virtual environment for course tutorial.

.. code-block:: sh

    $ pyenv virtualenv 3.6.8 course-v3


Activate python environment


.. code-block:: sh

    $ pyenv activate course-v3

Install all of the dependencies (if present)

.. code-block:: sh

    (course-v3) $ pip install -r python-setup/requirements.txt

Update dependencies

.. code-block:: sh

    (course-v3) $ pip install --upgrade pip setuptools


Install jupyter-notebook

.. code-block:: sh

    (course-v3) $ pip install jupyter

Install machine learning libraries


.. code-block:: sh

    (course-v3) $ pip install tensorflow-gpu
    (course-v3) $ pip install torch
    (course-v3) $ pip install mxnet
    (course-v3) $ pip install cntk-gpu
    (course-v3) $ pip install fastai