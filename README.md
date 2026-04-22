# K-Means and K-Medoids Clustering — UC Davis STA 142B Project 2

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
