.. notebook_test documentation master file, created by
   sphinx-quickstart on Sat Jul 25 11:56:56 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to the Surgical Phase Recognition Project!
===========================================

| *Repository*: https://github.com/bfortuno/Surgical-Phase-Recognition
| *Author*: Benjamin I. Fortuno

As part of this **BSc project**, we have created a structured series of **Jupyter notebooks** designed to guide students through the **testing and evaluation of neural networks for surgical phase recognition**. These tutorials provide a **hands-on approach** to understanding key deep learning concepts through **practical implementation**.

Throughout this project, we will explore topics such as:
- **Optimization techniques** for training deep learning models.
- **Transformers and self-attention mechanisms** for sequence modeling.
- **Graph Neural Networks (GNNs)** and their applications in surgical phase recognition.
- **Model evaluation and performance benchmarking** in real-world surgical datasets.

Each notebook is designed to **complement theoretical knowledge** by demonstrating **real-world implementations** using **PyTorch** and **PyTorch Lightning**. These materials serve as a foundation for students to **analyze, test, and optimize different neural architectures** for surgical phase recognition.

The notebooks are introduced in **guided tutorial sessions**, where the **content and implementation details** are explained step by step. Students can choose to:
- Simply **review the pre-filled notebooks** for theoretical understanding.
- **Modify and experiment** with different configurations and training setups.
- **Code along during sessions** to gain practical experience.

The notebooks are **not directly part of any graded assignments**, but students are encouraged to **experiment, modify, and extend them** to develop a **deeper understanding of model testing and evaluation**. The knowledge gained from these tutorials will be **highly relevant for the final project assessment**.

Additionally, these tutorials integrate **best practices from PyTorch Lightning**, making it easier to **train, validate, and deploy models efficiently**. More information about PyTorch Lightning can be found in **[their official documentation](https://pytorch-lightning.readthedocs.io/en/latest/)**.

Schedule (Deep Learning 1, edition 2024)
----------------------------------------

+------------------------------------------+---------------------------------------------------------------+
| **Date**                                 | **Notebook**                                                  |
+------------------------------------------+---------------------------------------------------------------+
| Tuesday, 29. October 2024, 09:00-10:00   | Tutorial 2: Introduction to PyTorch                           |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 4. November 2024, 15:00-16:00    | Tutorial 3: Activation functions                              |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 11. November 2024, 15:00-16:00   | Tutorial 4: Optimization and Initialization                   |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 18. November 2024, 15:00-16:00   | Tutorial 5: Inception, ResNet and DenseNet                    |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 25. November 2024, 15:00-16:00   | Tutorial 6: Transformers and Multi-Head Attention             |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 2. December 2024, 15:00-16:00    | Tutorial 7: Graph Neural Networks                             |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 9. December 2024, 15:00-16:00    | Tutorial 17: Self-Supervised Contrastive Learning with SimCLR |
+------------------------------------------+---------------------------------------------------------------+

How to run the notebooks
------------------------

On this website, you will find the notebooks exported into a HTML format so that you can read them from whatever device you prefer.
However, we suggest that you also give them a try and run them yourself. There are three main ways of running the notebooks we recommend:

- **Locally on CPU**: All notebooks are stored on the github repository that also builds this website. You can find them here: https://github.com/phlippe/uvadlc_notebooks/tree/master/docs/tutorial_notebooks. The notebooks are designed so that you can execute them on common laptops without the necessity of a GPU. We provide pretrained models that are automatically downloaded when running the notebooks, or can manually be downloaded from this `Google Drive <https://drive.google.com/drive/folders/1SevzqrkhHPAifKEHo-gi7J-dVxifvs4c?usp=sharing>`_. The required disk space for the pretrained models and datasets is less than 1GB. To ensure that you have all the right python packages installed, we provide a conda environment in the `same repository <https://github.com/uvadlc/uvadlc_practicals_2020/blob/master/environment.yml>`_ (choose the CPU or GPU version depending on your system).

- **Google Colab**: If you prefer to run the notebooks on a different platform than your own computer, or want to experiment with GPU support, we recommend using `Google Colab <https://colab.research.google.com/notebooks/intro.ipynb#recent=true>`_. Each notebook on this documentation website has a badge with a link to open it on Google Colab. Remember to enable GPU support before running the notebook (:code:`Runtime -> Change runtime type`). Each notebook can be executed independently, and doesn't require you to connect your Google Drive or similar. However, when closing the session, changes might be lost if you don't save it to your local computer or have copied the notebook to your Google Drive beforehand.

Tutorial-Lecture alignment
--------------------------

We will discuss 7 of the tutorials in the course, spread across lectures to cover something from every area. You can align the tutorials with the lectures based on their topics. The list of tutorials in the Deep Learning 1 course is:

- Tutorial 1: Introduction to Python for AI: Numpy, Matplotlib, Pandas

Feedback, Questions or Contributions
------------------------------------

This is the first time we present these tutorials during the Deep Learning course. As with any other project, small bugs and issues are expected. We appreciate any feedback from students, whether it is about a spelling mistake, implementation bug, or suggestions for improvements/additions to the notebooks. Please use the following `link <https://forms.gle/kENuNvcCq3LzQWDA8>`_ to submit feedback, or feel free to reach out to me directly per mail (p dot lippe at uva dot nl), or grab me during any TA session.

If you find the tutorials helpful and would like to cite them, you can use the following bibtex::

   @misc{lippe2024uvadlc,
      title        = {{Surgical Phase Recognition BSc Project}},
      author       = {Benjamin I. Fortuno},
      year         = 2025,
      howpublished = {\url{https://surgical-phase-recognition.readthedocs.io/}}
   }

.. toctree::
   :caption: Project Noteboks
   :maxdepth: 2

   tutorial_notebooks/tutorial1/python_basics_1
   tutorial_notebooks/tutorial2/python_basics_2
   tutorial_notebooks/tutorial3/pytorch_intro

