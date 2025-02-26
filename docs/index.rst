.. Surgical Task Identification documentation master file

Welcome to the Surgical Task Identification Tutorials!
======================================================

| **Repository**: https://github.com/bfortuno/Surgical-Phase-Recognition
| **Author**: Benjamin I. Fortuno
| **Google Colab Notebooks**: Click on the tutorial links to open them interactively!

For this project, we have created a structured series of **Jupyter notebooks** designed to teach deep learning techniques for **surgical phase recognition**. These tutorials provide a practical approach to applying **computer vision, time-series modeling, and deep learning frameworks** to surgical task identification.

We will explore various techniques such as:
- **Convolutional Neural Networks (CNNs)** for feature extraction.
- **Recurrent Neural Networks (RNNs) & Temporal Convolutional Networks (TCNs)** for time-series analysis.
- **Transformers & Multi-Head Attention** for sequence modeling.
- **Optimization techniques** and **model evaluation** for real-world performance.

The notebooks aim to bridge the gap between theoretical concepts and real-world implementation using **PyTorch** and **Google Colab**.

---

Schedule (Surgical Task Recognition Tutorials - 2024)
------------------------------------------------------

+------------------------------------------+---------------------------------------------------------------+
| **Date**                                 | **Notebook**                                                  |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 4. March 2024, 15:00-16:00       | Tutorial 1: Introduction to Python & PyTorch                  |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 11. March 2024, 15:00-16:00      | Tutorial 2: Image Processing with OpenCV                      |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 18. March 2024, 15:00-16:00      | Tutorial 3: CNNs for Surgical Data Analysis                   |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 25. March 2024, 15:00-16:00      | Tutorial 4: RNNs & LSTMs for Time-Series Modeling             |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 1. April 2024, 15:00-16:00       | Tutorial 5: Transformers for Surgical Phase Recognition       |
+------------------------------------------+---------------------------------------------------------------+
| Monday, 8. April 2024, 15:00-16:00       | Tutorial 6: Model Training, Evaluation & Deployment          |
+------------------------------------------+---------------------------------------------------------------+

---

How to Run the Notebooks
------------------------

On this website, you will find the notebooks exported into an **HTML format**, allowing you to **browse through the tutorials**.  
However, to gain hands-on experience, we highly recommend running them yourself.  
There are three primary ways to execute the notebooks:

- **1️⃣ Locally on CPU**:  
  - Clone the repository:
    ```bash
    git clone https://github.com/bfortuno/Surgical-Phase-Recognition.git
    cd Surgical-Phase-Recognition
    pip install -r requirements.txt
    ```
  - Run Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
  - All notebooks are **optimized to run on a standard laptop**.

- **2️⃣ Google Colab (Recommended for GPU Support)**:  
  - Click on the **Google Colab badge** next to each notebook to open it in the cloud.
  - Ensure **GPU support is enabled**:  
    **Runtime → Change runtime type → Select "GPU"**.
  - Notebooks run **independently** without requiring additional setup.
---

Tutorial-Notebook Alignment
---------------------------

These tutorials are aligned to **Deep Learning techniques applied to Surgical Phase Recognition**:

- **Guide 1**: Python Basics for Deep Learning  
- **Tutorial 1**: Image Processing with OpenCV  
- **Tutorial 2**: CNNs for Surgical Phase Identification  
- **Tutorial 3**: Recurrent Neural Networks (RNNs) & LSTMs for Surgical Sequences  
- **Tutorial 4**: Transformers & Attention Mechanisms  
- **Tutorial 5**: Model Training, Fine-tuning, and Evaluation  
- **Tutorial 6**: Model Deployment & Real-time Inference  

These topics ensure that learners **progressively build expertise** in applying **deep learning** to surgical data.

---

Feedback, Questions, or Contributions
--------------------------------------

This project is a **work in progress**, and improvements are continuously being made.  
We encourage feedback and contributions!

📌 **Ways to contribute:**
- Report issues, typos, or bugs via [GitHub Issues](https://github.com/bfortuno/Surgical-Phase-Recognition/issues).
- Suggest improvements or submit **pull requests**.
- Contact me via email for further discussions.

If you find these tutorials helpful and would like to cite them, use the following BibTeX reference:

```bibtex
@misc{fortuno2024surgical,
   title        = {Surgical Phase Recognition Tutorials},
   author       = {Benjamin I. Fortuno},
   year         = 2024,
   howpublished = {https://github.com/bfortuno/Surgical-Phase-Recognition}
}


.. toctree::
   :caption: Project Noteboks
   :maxdepth: 2

   tutorial_notebooks/tutorial1/python_basics

