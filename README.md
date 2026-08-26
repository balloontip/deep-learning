# Deep Learning: From Curiosity to Mastery — Volumes 1 & 2

### Official Companion Code Repository

[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/) [![PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C.svg)](https://pytorch.org/) [![Colab Ready](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00.svg)](https://colab.research.google.com/) [![License: Educational Use](https://img.shields.io/badge/License-Educational%20Use-green.svg)](#license-and-copyright) [![Release 1.3](https://img.shields.io/badge/Release-1.3-informational.svg)](#)

> Published by **Balloon Tip** (Richardson, TX, USA) · [www.balloontip.com](http://www.balloontip.com)
>
> © 2025 Balloon Tip. All rights reserved.

---

## About This Repository

This is the **official companion code repository** for *Deep Learning: From Curiosity to Mastery — Volumes 1 & 2*.

The repository contains Python, PyTorch, and Google Colab notebook examples covering **Chapters 1–9**, organized in a clean chapter-wise folder structure.

* **Volume 1:** Chapters 1–6
* **Volume 2:** Chapters 7–9

The notebooks progress from fundamental deep learning concepts to practical and advanced topics including convolutional neural networks, recurrent neural networks, word embeddings, Transformers, natural language processing, transfer learning, generative models, reinforcement learning, explainable AI, adversarial attacks, diffusion models, and emerging neural architectures.

Every notebook is designed to be executable either locally or in **Google Colab**, allowing readers to follow the examples presented in the books and experiment with the models independently.

---

## About the Books

*Deep Learning: From Curiosity to Mastery* provides an intuition-first, hands-on journey through modern deep learning using Python and PyTorch.

**Volume 1** establishes the foundations of neural networks and introduces practical deep learning workflows, regression, classification, image recognition, and end-to-end projects.

**Volume 2** builds on these foundations with CNNs, sequence models, embeddings, Transformers, NLP, transfer learning, generative AI, reinforcement learning, explainability, adversarial learning, diffusion models, and emerging neural-network architectures.

| Detail                 | Information                                     |
| ---------------------- | ----------------------------------------------- |
| **Title**              | Deep Learning: From Curiosity to Mastery        |
| **Volumes**            | 1 & 2                                           |
| **Repository Release** | 1.3                                             |
| **Publisher**          | Balloon Tip (Richardson, TX, USA)               |
| **Copyright**          | © 2025 Balloon Tip. All rights reserved.        |
| **Author**             | As listed in the books                          |
| **Website**            | [www.balloontip.com](http://www.balloontip.com) |

---

## Who This Repository Is For

* **College and university students** taking introductory or advanced deep learning courses
* **Educators and instructors** who have adopted the books and want ready-to-run demonstrations
* **Self-learners** working through the books independently
* **Researchers and practitioners** looking for clear PyTorch implementations
* **Software engineers and AI developers** exploring modern neural-network architectures

No prior deep learning experience is required for Volume 1. Volume 2 builds progressively on the concepts introduced in Volume 1.

---

## How to Use This Repository

### Using Google Colab — Recommended

Google Colab provides a cloud-based Jupyter environment with optional GPU acceleration and requires no local installation.

1. Navigate to the chapter folder of interest, for example `chapter-08/`.
2. Click the `.ipynb` notebook you want to run.
3. Click the **Open in Colab** badge inside the notebook, when available.
4. Alternatively, open [Google Colab](https://colab.research.google.com/), choose **File → Open notebook → GitHub**, and paste the notebook URL.
5. If GPU acceleration is required, select **Runtime → Change runtime type → GPU**.
6. Run the notebook cells sequentially from top to bottom.

---

# Chapters and Notebooks Index

## Volume 1 — Foundations and Applied Deep Learning

### Chapters 1–5

| Chapter | Title / Topic | Notebook                                                     |
| ------- | ------------- | ------------------------------------------------------------ |
| 1       | Chapter 1     | [`chapter-01/chapter-01.ipynb`](chapter-01/chapter-01.ipynb) |
| 2       | Chapter 2     | [`chapter-02/chapter-02.ipynb`](chapter-02/chapter-02.ipynb) |
| 3       | Chapter 3     | [`chapter-03/chapter-03.ipynb`](chapter-03/chapter-03.ipynb) |
| 4       | Chapter 4     | [`chapter-04/chapter-04.ipynb`](chapter-04/chapter-04.ipynb) |
| 5       | Chapter 5     | [`chapter-05/chapter-05.ipynb`](chapter-05/chapter-05.ipynb) |

### Chapter 6 — Applied Deep Learning Projects

| Problem | Topic                                      | Notebook                                                                                      |
| ------- | ------------------------------------------ | --------------------------------------------------------------------------------------------- |
| **6.1** | Predicting House Prices with Deep Learning | [`problem-1-house-prices.ipynb`](chapter-06/problem-1-house-prices.ipynb)                     |
| **6.2** | Weather Forecasting                        | [`problem-2-weather-forecasting.ipynb`](chapter-06/problem-2-weather-forecasting.ipynb)       |
| **6.3** | Predicting Housing Prices in New York City | [`problem-3-nyc-housing.ipynb`](chapter-06/problem-3-nyc-housing.ipynb)                       |
| **6.4** | Handwritten Digit Recognition with MNIST   | [`problem-4-mnist-handwriting.ipynb`](chapter-06/problem-4-mnist-handwriting.ipynb)           |
| **6.5** | Model Deployment with PyTorch and Flask    | [`problem-5-model-deployment-flask.ipynb`](chapter-06/problem-5-model-deployment-flask.ipynb) |

---

# Volume 2 — Advanced Deep Learning

## Chapter 7

| Topic                                   | Notebook                                                                                      |
| --------------------------------------- | --------------------------------------------------------------------------------------------- |
| Model Deployment with PyTorch and Flask | [`problem-5-model-deployment-flask.ipynb`](chapter-07/problem-5-model-deployment-flask.ipynb) |

---

## Chapter 8 — CNNs, RNNs, Embeddings and Transformers

| #       | Topic                                                                   | Notebook                                                                                                                                                                                                |
| ------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **8.1** | CNN 2D Convolution Sliding Visualization                                | [`08-01-CNN-2D-Convolution-Sliding-Visualization.ipynb`](chapter-08/08-01-CNN-2D-Convolution-Sliding-Visualization.ipynb)                                                                               |
| **8.2** | CNN CIFAR-10 Image Classification Project                               | [`08-02-CNN-CIFAR-10-Image-Classification-Project.ipynb`](chapter-08/08-02-CNN-CIFAR-10-Image-Classification-Project.ipynb)                                                                             |
| **8.3** | RNN Sequence-to-One Prediction Model                                    | [`08-03-RNN-Sequence-to-One-Prediction-Model.ipynb`](chapter-08/08-03-RNN-Sequence-to-One-Prediction-Model.ipynb)                                                                                       |
| **8.4** | RNN Daily Temperature Prediction — Regression Project                   | [`08-04-RNN-Daily-Temperature-Prediction-Regression-Project.ipynb`](chapter-08/08-04-RNN-Daily-Temperature-Prediction-Regression-Project.ipynb)                                                         |
| **8.5** | RNN Sequence Classification Project                                     | [`08-05-RNN-Sequence-Classification-Project.ipynb`](chapter-08/08-05-RNN-Sequence-Classification-Project.ipynb)                                                                                         |
| **8.6** | RNN Learned Word Embeddings for Text Classification                     | [`08-06-RNN-Learned-Word-Embeddings-for-Text-Classification.ipynb`](chapter-08/08-06-RNN-Learned-Word-Embeddings-for-Text-Classification.ipynb)                                                         |
| **8.7** | RNN Mixed-Input Energy Usage Prediction Project                         | [`08-07-RNN-Mixed-Input-Energy-Usage-Prediction-Project.ipynb`](chapter-08/08-07-RNN-Mixed-Input-Energy-Usage-Prediction-Project.ipynb)                                                                 |
| **8.8** | Transformer English-to-Turkish Neural Machine Translation               | [`08-08-Project-Transformer-English-to-Turkish-Neural-Machine-Translation-Project.ipynb`](chapter-08/08-08-Project-Transformer-English-to-Turkish-Neural-Machine-Translation-Project.ipynb)             |
| **8.9** | Transformer Book Review Classification with DistilBERT and Hugging Face | [`08-09-Project-Transformer-Book-Review-Classification-with-DistilBERT-and-Hugging-Face.ipynb`](chapter-08/08-09-Project-Transformer-Book-Review-Classification-with-DistilBERT-and-Hugging-Face.ipynb) |

---

## Chapter 9 — Modern and Emerging Deep Learning

| #        | Topic                                                            | Notebook                                                                                                                                                                  |
| -------- | ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **9.1**  | GloVe Word Embeddings in Practice                                | [`09-01-NLP-GloVe-Word-Embeddings-in-Practice.ipynb`](chapter-09/09-01-NLP-GloVe-Word-Embeddings-in-Practice.ipynb)                                                       |
| **9.2**  | Fine-Tuning BERT for Sentiment Classification                    | [`09-02-NLP-Fine-Tuning-BERT-for-Sentiment-Classification.ipynb`](chapter-09/09-02-NLP-Fine-Tuning-BERT-for-Sentiment-Classification.ipynb)                               |
| **9.3**  | Zero-Shot Text Classification with Transformers                  | [`09-03-NLP-Zero-Shot-Text-Classification-with-Transformers.ipynb`](chapter-09/09-03-NLP-Zero-Shot-Text-Classification-with-Transformers.ipynb)                           |
| **9.4**  | Transfer Learning with ResNet50                                  | [`09-04-Transfer-Learning-with-ResNet50.ipynb`](chapter-09/09-04-Transfer-Learning-with-ResNet50.ipynb)                                                                   |
| **9.5**  | Transfer Learning in PyTorch — Oak vs. Palm Classifier           | [`09-05-Transfer-Learning-in-PyTorch-Step-by-Step-Oak-vs-Palm-Classifier.ipynb`](chapter-09/09-05-Transfer-Learning-in-PyTorch-Step-by-Step-Oak-vs-Palm-Classifier.ipynb) |
| **9.6**  | GAN — MNIST Handwritten Digit Generation                         | [`09-06-GAN-MNIST-Handwritten-Digit-Generation.ipynb`](chapter-09/09-06-GAN-MNIST-Handwritten-Digit-Generation.ipynb)                                                     |
| **9.7**  | Deep Q-Learning with CartPole                                    | [`09-07-Deep-Q-Learning-with-CartPole.ipynb`](chapter-09/09-07-Deep-Q-Learning-with-CartPole.ipynb)                                                                       |
| **9.8**  | Variational Autoencoder — Synthetic Data Generation              | [`09-08-Variational-Autoencoder-VAE-Synthetic-Data-Generation.ipynb`](chapter-09/09-08-Variational-Autoencoder-VAE-Synthetic-Data-Generation.ipynb)                       |
| **9.9**  | Autoencoder and t-SNE for Customer Feedback Analysis             | [`09-09-Autoencoder-and-t-SNE-for-Customer-Feedback-Analysis.ipynb`](chapter-09/09-09-Autoencoder-and-t-SNE-for-Customer-Feedback-Analysis.ipynb)                         |
| **9.10** | Autoencoder and t-SNE — Fashion-MNIST Latent Space Visualization | [`09-10-Autoencoder-and-t-SNE-Fashion-MNIST-Latent-Space-Visualization.ipynb`](chapter-09/09-10-Autoencoder-and-t-SNE-Fashion-MNIST-Latent-Space-Visualization.ipynb)     |
| **9.11** | LIME Text Classification Explanations                            | [`09-11-LIME-Text-Classification-Explanations.ipynb`](chapter-09/09-11-LIME-Text-Classification-Explanations.ipynb)                                                       |
| **9.12** | SHAP Feature Contributions for Soccer Player Classification      | [`09-12-SHAP-Feature-Contributions-for-Soccer-Player-Classification.ipynb`](chapter-09/09-12-SHAP-Feature-Contributions-for-Soccer-Player-Classification.ipynb)           |
| **9.13** | FGSM Adversarial Attack on MNIST                                 | [`09-13-FGSM-Adversarial-Attack-on-MNIST.ipynb`](chapter-09/09-13-FGSM-Adversarial-Attack-on-MNIST.ipynb)                                                                 |
| **9.14** | Blank Notebook                                                   | [`09-14-Blank.ipynb`](chapter-09/09-14-Blank.ipynb)                                                                                                                       |
| **9.15** | Diffusion Model — MNIST Digit Generation                         | [`09-15-Diffusion-Model-MNIST-Digit-Generation.ipynb`](chapter-09/09-15-Diffusion-Model-MNIST-Digit-Generation.ipynb)                                                     |
| **9.16** | Liquid Neural Network for Robot Balance Control                  | [`09-16-Liquid-Neural-Network-for-Robot-Balance-Control.ipynb`](chapter-09/09-16-Liquid-Neural-Network-for-Robot-Balance-Control.ipynb)                                   |
| **9.17** | Fourier Neural Operator for Pipe Flow Prediction                 | [`09-17-Fourier-Neural-Operator-for-Pipe-Flow-Prediction.ipynb`](chapter-09/09-17-Fourier-Neural-Operator-for-Pipe-Flow-Prediction.ipynb)                                 |

---

## Important Notes

**Reproducibility.** Random seeds are set where appropriate to improve reproducibility. Exact numerical output can vary slightly depending on hardware, CUDA versions, library versions, and GPU configuration.

**Datasets.** Some notebooks download datasets automatically at runtime through libraries such as `torchvision` or Hugging Face. Other notebooks may require additional local or external datasets. Check the instructions at the beginning of each notebook.

**GPU Usage.** Introductory examples can generally be executed on a CPU. CNNs, Transformers, GANs, diffusion models, and other computationally intensive examples in Volumes 1 and 2 may benefit significantly from GPU acceleration.

In Google Colab, GPU acceleration can be enabled through:

**Runtime → Change runtime type → GPU**

---

## How to Report Errors

Found a bug, typo, broken dependency, or incorrect output? Please open a **GitHub Issue** so it can be investigated.

When filing an issue, please include:

* **Chapter and notebook name**
* **Cell number or relevant code section**
* **Full error message or traceback**
* **Python version**
* **PyTorch version**
* **Operating system**
* **CPU or GPU environment**
* **Steps required to reproduce the problem**
* Whether the problem occurs in **Google Colab**, locally, or both

Please search existing issues before opening a new issue to avoid duplicates.

---

## Contributions

Community contributions are welcome and appreciated.

If you would like to propose a correction, improvement, or addition:

1. **Fork** this repository.
2. Create a new **feature branch**:

   ```bash
   git checkout -b fix/chapter-08-example
   ```
3. Make your changes.
4. Verify that affected notebooks execute correctly.
5. **Commit** your changes with a clear description.
6. Open a **Pull Request** against the `main` branch explaining what was changed and why.

Please keep each pull request focused on a specific issue or improvement. Contributions will be reviewed by the maintainers before merging.

---

## Citation

If you use the companion code repository or reference the books in academic work, you may cite the repository as:

```bibtex
@misc{deep_learning_curiosity_mastery_code,
  title        = {Deep Learning: From Curiosity to Mastery -- Companion Code Repository},
  publisher    = {Balloon Tip},
  address      = {Richardson, TX, USA},
  note         = {Companion code for Volumes 1 and 2, Release 1.3},
  howpublished = {\url{https://github.com/balloontip/deep-learning}}
}
```

When formally citing an individual book volume, please use the bibliographic information printed in that volume.

---

## License and Copyright

© 2025 Balloon Tip. All rights reserved.

The **source code** in this repository is provided for **educational and personal learning purposes** in conjunction with the *Deep Learning: From Curiosity to Mastery* book series.

You may run, modify, and experiment with the code for your own learning, subject to the repository license.

The **book content, text, figures, and structure** are copyrighted by Balloon Tip and may not be reproduced, distributed, or transmitted without prior written permission from the publisher.

See [`LICENSE.md`](LICENSE.md) for the complete terms.

---

## Contact

For questions about the books, bulk or institutional orders, or other inquiries:

**Balloon Tip**
Richardson, TX, USA

[www.balloontip.com](http://www.balloontip.com)

For code-specific problems, please use [GitHub Issues](../../issues).

---

## Acknowledgements

We thank the reviewers, educators, contributors, and early readers whose feedback helped shape the books and companion code repository.

A detailed list of acknowledgements can be found in the books.

*If you have contributed to this repository, thank you for helping improve this learning resource.*

---

## Quick Start — Recommended Learning Path

### Volume 1

Follow the foundational material in sequence:

**Chapter 1 → Chapter 2 → Chapter 3 → Chapter 4 → Chapter 5 → Chapter 6**

Chapters 1–5 progressively establish the concepts needed to understand and build neural networks.

Chapter 6 applies those concepts through practical projects:

| Problem                | Domain          | Key Concepts                              |
| ---------------------- | --------------- | ----------------------------------------- |
| 1. House Prices        | Regression      | Feature preparation, feedforward networks |
| 2. Weather Forecasting | Time Series     | Sequential data and prediction            |
| 3. NYC Housing Prices  | Regression      | Real-world data preprocessing             |
| 4. MNIST Handwriting   | Computer Vision | Image classification                      |
| 5. Model Deployment    | Deployment      | PyTorch model serving with Flask          |

### Volume 2

After completing the foundations, continue with:

**Chapter 7 → Chapter 8 → Chapter 9**

Volume 2 extends the learning path toward modern and advanced deep learning:

* **Chapter 7:** Model deployment
* **Chapter 8:** CNNs, RNNs, word embeddings, sequence learning, and Transformers
* **Chapter 9:** NLP, BERT, transfer learning, GANs, VAEs, reinforcement learning, explainable AI, adversarial attacks, diffusion models, liquid neural networks, and Fourier neural operators

---

*Happy learning! If this repository helps you, consider giving it a star on GitHub.*
