# Task 1: Exploring and Visualizing the Iris Dataset
**DevelopersHub Corporation — AI/ML Engineering Internship**

## Objective
Load, inspect, and visualize the Iris dataset to understand data trends, feature distributions, and relationships between variables.

## Dataset
- **Name:** Iris Dataset
- **Source:** `sklearn.datasets.load_iris`
- **Size:** 150 samples × 4 features
- **Classes:** Setosa, Versicolor, Virginica

## Tools & Libraries
- Python 3.10
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

## What's Inside the Notebook
| Step | Description |
|------|-------------|
| Data Loading | Loaded via sklearn, converted to pandas DataFrame |
| Inspection | `.shape`, `.info()`, `.describe()`, class distribution |
| Scatter Plots | Sepal and petal feature relationships by species |
| Pair Plot | All feature combinations colored by species |
| Histograms | Value distributions for all 4 features |
| Box Plots | Outlier detection per feature per species |
| Heatmap | Feature correlation matrix |

## Key Results & Findings
- **Setosa is perfectly separable** from the other two species using petal length and petal width
- **Petal length and petal width are highly correlated** (r ≈ 0.96) — one could be dropped without losing much information
- **Sepal width** has the most visible outliers, especially in the Setosa class
- **Versicolor and Virginica overlap** in sepal space but are separable in petal space

## How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Task1_Iris_EDA.ipynb
```
Run all cells from top to bottom. No dataset download required — loads automatically.
