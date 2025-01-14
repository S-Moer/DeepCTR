.. DeepCTR documentation master file, created by
   sphinx-quickstart on Fri Nov 23 21:08:54 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to DeepCTR's documentation!
===================================

|Downloads|_ |Stars|_ |Forks|_ |PyPii|_ |Issues|_ |Chat|_

.. |Downloads| image:: https://pepy.tech/badge/deepctr
.. _Downloads: https://pepy.tech/project/deepctr

.. |Stars| image:: https://img.shields.io/github/stars/shenweichen/deepctr.svg
.. _Stars: https://github.com/shenweichen/DeepCTR

.. |Forks| image:: https://img.shields.io/github/forks/shenweichen/deepctr.svg
.. _Forks: https://github.com/shenweichen/DeepCTR/fork

.. |PyPii| image:: https://img.shields.io/pypi/v/deepctr.svg
.. _PyPii: https://pypi.org/project/deepctr

.. |Issues| image:: https://img.shields.io/github/issues/shenweichen/deepctr.svg
.. _Issues: https://github.com/shenweichen/deepctr/issues

.. |Chat| image:: https://img.shields.io/badge/chat-wechat-brightgreen?style=flat
.. _Chat: ./#disscussiongroup

DeepCTR is a **Easy-to-use** , **Modular** and **Extendible** package of deep-learning based CTR models along with lots of core components layer  which can be used to easily build custom models.You can use any complex model with ``model.fit()`` and ``model.predict()``.

- Provide ``tf.keras.Model`` like interface for **quick experiment**. `example <https://deepctr-doc.readthedocs.io/en/latest/Quick-Start.html#getting-started-4-steps-to-deepctr>`_
- Provide  ``tensorflow estimator`` interface for **large scale data** and **distributed training**. `example <https://deepctr-doc.readthedocs.io/en/latest/Quick-Start.html#getting-started-4-steps-to-deepctr-estimator-with-tfrecord>`_
- It is compatible with both ``tf 1.x``  and ``tf 2.x``.

Let's `Get Started! <./Quick-Start.html>`_ (`Chinese Introduction <https://zhuanlan.zhihu.com/p/53231955>`_)

You can read the latest code and related projects

- DeepCTR: https://github.com/shenweichen/DeepCTR
- DeepMatch: https://github.com/shenweichen/DeepMatch
- DeepCTR-Torch: https://github.com/shenweichen/DeepCTR-Torch

News
-----
07/18/2021 : Support pre-defined key-value vocabulary in `Hash` Layer. `example <./Examples.html#hash-layer-with-pre-defined-key-value-vocabulary>`_ `Changelog <https://github.com/shenweichen/DeepCTR/releases/tag/v0.8.7>`_

06/14/2021 : Add `IFM <./Features.html#ifm-input-aware-factorization-machine>`_ , `DIFM <./Features.html#difm-dual-input-aware-factorization-machine>`_ and `DeepFEFM <./Features.html#deepfefm-deep-field-embedded-factorization-machine>`_ . `Changelog <https://github.com/shenweichen/DeepCTR/releases/tag/v0.8.6>`_

03/13/2021 : Add `BST <./Features.html#bst-behavior-sequence-transformer>`_ . `Changelog <https://github.com/shenweichen/DeepCTR/releases/tag/v0.8.5>`_

DisscussionGroup
-----------------------

`Discussions <https://github.com/shenweichen/DeepCTR/discussions>`_  公众号：**浅梦学习笔记**  wechat ID: **deepctrbot**

.. image:: ../pics/code.png

.. toctree::
   :maxdepth: 2
   :caption: Home:

   Quick-Start<Quick-Start.md>
   Features<Features.md>
   Examples<Examples.md>
   FAQ<FAQ.md>
   History<History.md>

.. toctree::
   :maxdepth: 3
   :caption: API:

   Models<Models>
   Estimators<Estimators>
   Layers<Layers>




Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`