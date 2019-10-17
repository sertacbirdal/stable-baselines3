.. Stable Baselines documentation master file, created by
   sphinx-quickstart on Thu Sep 26 11:06:54 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Torchy Baselines docs! - Pytorch RL Baselines
========================================================

`Torchy Baselines <https://github.com/hill-a/stable-baselines>`_ is the PyTorch version of `Stable Baselines <https://github.com/hill-a/stable-baselines>`_,
a set of improved implementations of reinforcement learning algorithms.

RL Baselines Zoo (collection of pre-trained agents): https://github.com/araffin/rl-baselines-zoo

RL Baselines zoo also offers a simple interface to train, evaluate agents and do hyperparameter tuning.



.. toctree::
   :maxdepth: 2
   :caption: User Guide

   guide/quickstart
   guide/vec_envs


.. toctree::
  :maxdepth: 1
  :caption: RL Algorithms

  modules/base
  modules/ppo
  modules/sac
  modules/td3


.. toctree::
  :maxdepth: 1
  :caption: Misc

  misc/changelog


Citing Torchy Baselines
-----------------------
To cite this project in publications:

.. code-block:: bibtex

    @misc{torchy-baselines,
      author = {Raffin, Antonin and Hill, Ashley and Ernestus, Maximilian and Gleave, Adam and Kanervisto, Anssi},
      title = {Torchy Baselines},
      year = {2019},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/hill-a/stable-baselines}},
    }

Indices and tables
-------------------

* :ref:`genindex`
* :ref:`search`
* :ref:`modindex`