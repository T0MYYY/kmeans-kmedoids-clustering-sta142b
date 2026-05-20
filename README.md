# K-Means and K-Medoids Clustering — UC Davis STA 142B Project 2

<!-- BADGES_BEGIN -->
<p align="center">
  <img alt="Course" src="https://img.shields.io/badge/Course-STA%20142B-022851?style=flat-square&labelColor=2a323d">
  <img alt="UC Davis" src="https://img.shields.io/badge/UC%20Davis-Statistical%20Learning-FFBF00?style=flat-square&labelColor=2a323d">
  <img alt="Term" src="https://img.shields.io/badge/Term-Spring%202023-2a323d?style=flat-square&labelColor=2a323d">
  <img alt="Author" src="https://img.shields.io/badge/Author-Solo-1f7a3d?style=flat-square&labelColor=2a323d">
  <img alt="Status" src="https://img.shields.io/badge/Status-Submitted-ec5800?style=flat-square&labelColor=2a323d">
  <img alt="Impl" src="https://img.shields.io/badge/Impl-from%20scratch-7B68EE?style=flat-square&labelColor=2a323d">
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
  <img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-notebook-F37626?style=flat-square&labelColor=2a323d&logo=jupyter&logoColor=white">
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-1.x-013243?style=flat-square&labelColor=2a323d&logo=numpy&logoColor=white">
  <img alt="SciPy" src="https://img.shields.io/badge/SciPy-1.x-8CAAE6?style=flat-square&labelColor=2a323d&logo=scipy&logoColor=white">
  <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-1.x-F7931E?style=flat-square&labelColor=2a323d&logo=scikitlearn&logoColor=white">
  <img alt="pandas" src="https://img.shields.io/badge/pandas-2.x-150458?style=flat-square&labelColor=2a323d&logo=pandas&logoColor=white">
  <img alt="matplotlib" src="https://img.shields.io/badge/matplotlib-3.x-11557C?style=flat-square&labelColor=2a323d&logo=python&logoColor=white">
</p>
<!-- BADGES_END -->

Individual project implementing K-Means and K-Medoids clustering algorithms from scratch in Python, then applying them to real datasets.

**Course:** STA 142B — Statistical Learning (Spring 2023, UC Davis)  
**Author:** Chiyang Chen

---

## Project Overview

| Part | Topic |
|---|---|
| Part 1 | Implement K-Means algorithm as a Python class |
| Part 2 | Implement clustering evaluation criteria (e.g., ARI) |
| Part 3 | Implement K-Medoids algorithm |
| Part 4 | Simulation study — compare K-Means vs K-Medoids |
| Part 5 | Real data analysis — US Arrests & Weather datasets |

---

## Files

| File | Description |
|---|---|
| `notebook.ipynb` | Full implementation and analysis notebook |
| `data/USArrests.csv` | US arrest statistics dataset |
| `data/weather.csv` | Weather dataset |
| `data/ref_data/` | Simulation reference data for Part 4 |

---

## Key Concepts

- **K-Means** — centroid-based clustering minimizing within-cluster variance
- **K-Medoids** — robust variant using actual data points as cluster centers
- **ARI (Adjusted Rand Index)** — metric for comparing clustering results

---

## Libraries

```
numpy · pandas · matplotlib · sklearn
```

---

## How to Run

```bash
jupyter notebook notebook.ipynb
```
