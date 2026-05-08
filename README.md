# Deep Learning: From Curiosity to Mastery — Volume 1

### Official Companion Code Repository

[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C.svg)](https://pytorch.org/)
[![Colab Ready](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00.svg)](https://colab.research.google.com/)
[![License: Educational Use](https://img.shields.io/badge/License-Educational%20Use-green.svg)](#license-and-copyright)
[![Release 1.1](https://img.shields.io/badge/Release-1.1-informational.svg)](#)

> Published by **Balloon Tip** (Richardson, TX, USA) · [www.balloontip.com](http://www.balloontip.com)
>
> © 2025 Balloon Tip. All rights reserved.

---

## About This Repository

This is the **official companion code repository** for *Deep Learning: From Curiosity to Mastery — Volume 1*. It contains all Python, PyTorch, and Google Colab notebook examples presented throughout Chapters 1–6 of the book, organized in a clean, chapter-wise folder structure.

Every code listing, exercise, and end-of-chapter project in the book has a matching runnable notebook or script in this repository. The code is designed to be executed as-is, either locally or in Google Colab, so you can follow along with the text and experiment on your own.

---

## About the Book

*Deep Learning: From Curiosity to Mastery* takes readers on a structured journey from foundational concepts to hands-on deep learning projects using Python and PyTorch. Volume 1 covers the essential building blocks — from understanding what deep learning is, through the mathematics and mechanics of neural networks, to solving real-world problems including regression, classification, and image recognition.

| Detail | |
|---|---|
| **Title** | Deep Learning: From Curiosity to Mastery |
| **Volume** | 1 |
| **Release** | 1.1 |
| **Publisher** | Balloon Tip (Richardson, TX, USA) |
| **Copyright** | © 2025 Balloon Tip. All rights reserved. |
| **Author** | As listed in the book |
| **Website** | [www.balloontip.com](http://www.balloontip.com) |

---

## Who This Repository Is For

- **College and university students** taking introductory or intermediate deep learning courses
- **Educators and instructors** who have adopted the textbook and want ready-to-run demonstrations
- **Self-learners** working through the book independently
- **Practitioners** looking for clean, well-documented PyTorch starter code

No prior deep learning experience is required — the book and this repository start from the fundamentals.

---

## How to Use This Repository

### Using Google Colab (Recommended for Beginners)

Google Colab provides a free, cloud-based Jupyter environment with GPU access — no local setup needed.

1. Navigate to the chapter folder of interest (e.g., `chapter-01/`).
2. Click on the `.ipynb` notebook file.
3. At the top of the notebook preview on GitHub, click the **"Open in Colab"** badge (if included) or go to [colab.research.google.com](https://colab.research.google.com), select **File → Open notebook → GitHub**, and paste the notebook URL.
4. In Colab, go to **Runtime → Change runtime type** and select **GPU** if the notebook requires it.
5. Run cells sequentially from top to bottom.


#

## Chapters and Notebooks Index

| Chapter | Title / Topic | Notebook
|---|---|---|
| 1 | Chapter 1 | [`chapter-01/chapter-01.ipynb`](chapter-01/chapter-01.ipynb) 
| 2 | Chapter 2 | [`chapter-02/chapter-02.ipynb`](chapter-02/chapter-02.ipynb) 
| 3 | Chapter 3 | [`chapter-03/chapter-03.ipynb`](chapter-03/chapter-03.ipynb) 
| 4 | Chapter 4 | [`chapter-04/chapter-04.ipynb`](chapter-04/chapter-04.ipynb) 
| 5 | Chapter 5 | [`chapter-05/chapter-05.ipynb`](chapter-05/chapter-05.ipynb) 
| **6. Problem 1** | Predicting House Prices with Deep Learning | [`chapter-06/problem-1-house-prices.ipynb`](chapter-06/problem-1-house-prices.ipynb) | — |
| **6. Problem 2** | Weather Forecasting | [`chapter-06/problem-2-weather-forecasting.ipynb`](chapter-06/problem-2-weather-forecasting.ipynb) | — |
| **6. Problem 3** | Predicting Housing Prices in NYC | [`chapter-06/problem-3-nyc-housing.ipynb`](chapter-06/problem-3-nyc-housing.ipynb) | — |
| **6. Problem 4** | Spam Detection | [`chapter-06/problem-4-spam-detection.ipynb`](chapter-06/problem-4-spam-detection.ipynb) | — |
| **6. Problem 5** | Handwriting Recognition (MNIST) | [`chapter-06/problem-5-mnist-handwriting.ipynb`](chapter-06/problem-5-mnist-handwriting.ipynb) | — |

---

## Important Notes

**Reproducibility.** Random seeds are set in most notebooks to ensure reproducible results. However, exact numerical output may vary slightly across different hardware, CUDA versions, and PyTorch releases. This is expected behavior and does not indicate an error.

**Datasets.** Some notebooks download datasets automatically at runtime (e.g., MNIST via `torchvision.datasets`). Others may require manual download — check the `datasets/` folder or the instructions at the top of each notebook for details.

**GPU Usage.** Chapters 1–5 can be completed on a CPU. Chapter 6 problems benefit significantly from GPU acceleration. If running locally, ensure you have a CUDA-compatible GPU and the appropriate PyTorch CUDA build installed. In Google Colab, enable GPU under **Runtime → Change runtime type**.

---


## How to Report Errors

Found a bug, typo, or incorrect output? Please open a **GitHub Issue** so we can address it.

When filing an issue, include the following:

- **Chapter and notebook name** (e.g., Chapter 6 — Problem 3)
- **Cell number or code section** where the error occurs
- **Full error message / traceback**
- **Your environment** — Python version, PyTorch version, OS, CPU vs. GPU
- **Steps to reproduce** the issue
- **Whether the issue occurs in Google Colab**, locally, or both

Please search existing issues before opening a new one to avoid duplicates.

---

## Contributions

Community contributions are welcome and appreciated. If you would like to propose a fix, improvement, or addition:

1. **Fork** this repository.
2. Create a new **feature branch** (`git checkout -b fix/chapter-03-typo`).
3. Make your changes and ensure all notebooks run without errors.
4. **Commit** with a clear message describing the change.
5. Open a **Pull Request** against the `main` branch with a description of what you changed and why.

Please keep contributions focused and limited to one issue or improvement per PR. All contributions will be reviewed by the maintainers before merging.

---

## Citation

If you use this code or reference the book in academic work, please cite:

```bibtex
@book{deep_learning_curiosity_mastery_v1,
  title     = {Deep Learning: From Curiosity to Mastery},
  volume    = {1},
  publisher = {Balloon Tip},
  address   = {Richardson, TX, USA},
  year      = {2025},
  edition   = {1.1},
  note      = {Companion code: https://github.com/balloontip/deep-learning/}
}
```

---

## License and Copyright

© 2025 Balloon Tip. All rights reserved.

The **source code** in this repository is provided for **educational and personal learning purposes** in conjunction with the textbook *Deep Learning: From Curiosity to Mastery — Volume 1*. You may run, modify, and experiment with the code for your own learning.

The **book content, text, figures, and structure** are copyrighted by Balloon Tip and may not be reproduced, distributed, or transmitted in any form without prior written permission from the publisher.

See [`LICENSE.md`](LICENSE.md) for full terms.

---

## Contact

For questions about the book, bulk or institutional orders, or other inquiries:

**Balloon Tip**
Richardson, TX, USA
[www.balloontip.com](http://www.balloontip.com)

For code-specific issues, please use [GitHub Issues](../../issues).

---

## Acknowledgements

We thank the reviewers, educators, and early readers whose feedback shaped both the book and this companion repository. A detailed list of contributors and acknowledgements can be found in the book's preface.

*If you have contributed to this repository, your name will be added here. Thank you for helping improve this resource for the learning community.*

---

## Quick Start (Recommended Path for Beginners)

If you are new to deep learning, we recommend following the chapters in order:

**Chapter 1** → **Chapter 2** → **Chapter 3** → **Chapter 4** → **Chapter 5** → **Chapter 6**

Chapters 1–5 build your foundational understanding progressively — each chapter depends on concepts introduced in the previous ones. Take your time with the code examples and experiment with modifying parameters to build intuition.

**Chapter 6** is project-based. It brings together everything from the earlier chapters into five self-contained real-world problems. We recommend attempting each problem on your own before consulting the solution notebooks:

| Problem | Domain | Key Concepts |
|---|---|---|
| 1. House Prices | Regression | Feature engineering, feedforward networks |
| 2. Weather Forecasting | Time Series | Sequential data, prediction pipelines |
| 3. NYC Housing Prices | Regression | Real-world messy data, preprocessing |
| 4. Spam Detection | NLP / Classification | Text processing, binary classification |
| 5. MNIST Handwriting | Computer Vision | Image classification, CNNs |

Start with Problem 1 or Problem 5 — they are the most approachable entry points into applied deep learning.

---

*Happy learning! If this repository helps you, consider giving it a star on GitHub.*
