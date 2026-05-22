# Clustering and Manifold Learning — UC Davis STA 142B Final Project

<!-- BADGES_BEGIN -->
<p align="center">
  <img alt="Course" src="https://img.shields.io/badge/Course-STA%20142B-022851?style=flat-square&labelColor=2a323d">
  <img alt="UC Davis" src="https://img.shields.io/badge/UC%20Davis-Statistical%20Learning-FFBF00?style=flat-square&labelColor=2a323d">
  <img alt="Term" src="https://img.shields.io/badge/Term-Spring%202023-2a323d?style=flat-square&labelColor=2a323d">
  <img alt="Author" src="https://img.shields.io/badge/Author-Solo%20+%20Group-1f7a3d?style=flat-square&labelColor=2a323d">
  <img alt="Status" src="https://img.shields.io/badge/Status-Final-ec5800?style=flat-square&labelColor=2a323d">
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10-3776AB?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-notebook-F37626?style=flat-square&labelColor=2a323d&logo=jupyter&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-1.2-F7931E?style=flat-square&labelColor=2a323d&logo=scikitlearn&logoColor=white">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.24-013243?style=flat-square&labelColor=2a323d&logo=numpy&logoColor=white">
  <img alt="Plotly" src="https://img.shields.io/badge/Plotly-5.14-3F4F75?style=flat-square&labelColor=2a323d&logo=plotly&logoColor=white">
  <img alt="matplotlib" src="https://img.shields.io/badge/matplotlib-3.7-11557C?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="pandas" src="https://img.shields.io/badge/pandas-1.5-150458?style=flat-square&labelColor=2a323d&logo=pandas&logoColor=white">
  <img alt="Keras" src="https://img.shields.io/badge/Keras-2.12-D00000?style=flat-square&labelColor=2a323d&logo=keras&logoColor=white">
</p>
<!-- BADGES_END -->

Final project in two parts: an individual component covering clustering and manifold learning, and a group component applying the Gap Statistic to select the optimal number of clusters on MNIST data.

**Course:** STA 142B — Statistical Learning (Spring 2023, UC Davis)  
**Author:** Chiyang Chen

---

<p align="center">
  <img src="part1-individual/plots/newplot.png" width="60%">
</p>

---

## Part I — Individual: Clustering and Manifold Learning (`part1-individual/`)

| Section | Topic |
|---|---|
| Part 1 | Compare DBSCAN, K-Means, and Mean Shift on shaped datasets |
| Part 2 | Data visualization with t-SNE / UMAP |
| Part 3 | Multi-dimensional Scaling (MDS) and PCA |
| Extra | Image segmentation using clustering |

**Files:**
| File | Description |
|---|---|
| `notebook.ipynb` | Full analysis notebook |
| `report.pdf` | Submitted PDF report |
| `data/` | Input datasets (CSV files + feature data) |
| `plots/` | Exported Plotly figures (newplot*.png) |

---

## Part II — Group: Gap Statistic on MNIST (`part2-group/`)

| Section | Topic |
|---|---|
| Main | Implement Gap Statistic to estimate number of clusters |
| Data | MNIST handwritten digit images |
| Analysis | Apply K-Means with Gap Statistic; compare with ground truth |

**Files:**
| File | Description |
|---|---|
| `notebook.ipynb` | Full analysis notebook |
| `notebook_rendered.html` | Rendered HTML with all outputs |
| `instructions.pdf` | Original project instructions |
| `summary.pdf` | Written summary report on Gap Statistic |

---

## Key Concepts

- **DBSCAN** — density-based clustering, handles arbitrary shapes and noise
- **Mean Shift** — kernel-density-based clustering, no need to specify k
- **MDS** — preserve pairwise distances in low-dimensional space
- **Gap Statistic** — compares within-cluster variation to a reference null distribution to select optimal k

---

## Libraries

```
numpy · pandas · matplotlib · seaborn · sklearn · plotly
```

---

## How to Run

```bash
# Part I
jupyter notebook part1-individual/notebook.ipynb

# Part II
jupyter notebook part2-group/notebook.ipynb
```
