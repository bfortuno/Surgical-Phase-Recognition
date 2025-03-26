.. notebook_test documentation master file, created by
   sphinx-quickstart on Sat Jul 25 11:56:56 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to the Surgical Phase Recognition Project!
===========================================

| *Repository*: https://github.com/bfortuno/Surgical-Phase-Recognition
| *Author*: Benjamin I. Fortuno

As part of this **BSc project**, we have created a structured series of **Jupyter notebooks** designed to guide students through the **testing and evaluation of neural networks for surgical phase recognition**. These tutorials provide a **hands-on approach** to understanding key deep learning concepts through **practical implementation**.

Topics Covered
--------------

Throughout this project, we explore topics such as:

- **python basics** for data manipulation and visualization.
- **Introduction to PyTorch** for building and training neural networks.
- **Convolutional Neural Networks (CNNs)** for image classification.
- **Recurrent Neural Networks (RNNs)** for sequential data processing.
- **Attention mechanisms** for capturing temporal dependencies.
- **Transfer learning** for leveraging pre-trained models.
- **Data augmentation** for improving model generalization.
- **Hyperparameter tuning** for optimizing model performance.
- **Optimization techniques** for training deep learning models.
- **Model evaluation and performance benchmarking** using real-world surgical datasets.

Practical Implementation
------------------------

Each notebook is designed to **complement theoretical knowledge** by demonstrating **real-world implementations** using **PyTorch** and **PyTorch Lightning**. These materials serve as a foundation for students to **analyze, test, and optimize different neural architectures** for surgical phase recognition.

The notebooks are introduced in **guided tutorial sessions**, where the **content and implementation details** are explained step by step. Students can choose to:

- **Review the pre-filled notebooks** for theoretical understanding.
- **Modify and experiment** with different configurations and training setups.
- **Code along during sessions** to gain practical experience.

Grading and Learning Approach
-----------------------------

The notebooks are **not directly part of any graded assignments**, but students are encouraged to **experiment, modify, and extend them** to develop a **deeper understanding of model testing and evaluation**. 

Additional Resources
--------------------

These tutorials integrate **best practices from PyTorch Lightning**, making it easier to **train, validate, and deploy models efficiently**. More information about PyTorch Lightning can be found in their official documentation:

`PyTorch Lightning Documentation <https://pytorch-lightning.readthedocs.io/en/latest/>`_

How to run the notebooks
------------------------

On this website, you will find the notebooks exported into a HTML format so that you can read them from whatever device you prefer.
However, we suggest that you also give them a try and run them yourself. There are three main ways of running the notebooks we recommend:

- **Locally on CPU**: All notebooks are stored on the github repository that also builds this website. You can find them here: https://github.com/phlippe/uvadlc_notebooks/tree/master/docs/tutorial_notebooks. The notebooks are designed so that you can execute them on common laptops without the necessity of a GPU. We provide pretrained models that are automatically downloaded when running the notebooks, or can manually be downloaded from this `Google Drive <https://drive.google.com/drive/folders/1SevzqrkhHPAifKEHo-gi7J-dVxifvs4c?usp=sharing>`_. The required disk space for the pretrained models and datasets is less than 1GB. To ensure that you have all the right python packages installed, we provide a conda environment in the `same repository <https://github.com/uvadlc/uvadlc_practicals_2020/blob/master/environment.yml>`_ (choose the CPU or GPU version depending on your system).

- **Google Colab**: If you prefer to run the notebooks on a different platform than your own computer, or want to experiment with GPU support, we recommend using `Google Colab <https://colab.research.google.com/notebooks/intro.ipynb#recent=true>`_. Each notebook on this documentation website has a badge with a link to open it on Google Colab. Remember to enable GPU support before running the notebook (:code:`Runtime -> Change runtime type`). Each notebook can be executed independently, and doesn't require you to connect your Google Drive or similar. However, when closing the session, changes might be lost if you don't save it to your local computer or have copied the notebook to your Google Drive beforehand.

------------------------------------

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
   tutorial_notebooks/tutorial4/misaw_data_processing

