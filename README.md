# Machine Learning Capstone Project

## Overview
End-to-end Machine Learning pipeline on the California Housing dataset. This project covers Data Acquisition, EDA, Preprocessing, and the implementation of three different algorithms:
- **Regression**: Predicting the median house value.
- **Classification**: Predicting if a house is "expensive" based on the median threshold.
- **Clustering**: Grouping similar regions using K-Means.

## Dataset
[California Housing Prices (Kaggle)](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## Project Structure
- `data/`: Contains the raw (`housing.csv`) and cleaned (`clean_housing.csv`) datasets.
- `notebooks/`: Contains the Jupyter Notebooks (`01_eda.ipynb` and `02_modeling.ipynb`).
- `results/`: Contains generated plots and figures.
- `project_report.pdf`: The full detailed project report.

## How to Run
You can view and run the notebooks directly on Google Colab:
- [EDA Notebook]([https://colab.research.google.com/drive/1w1awilMMnTxOcV-68gueH20Y_-LrI1ic?usp=sharing])
- [Modeling Notebook]([https://colab.research.google.com/drive/1aBYerlftp7ZD8Iz8BT512pQtZX3LBTN7?usp=sharing])

## Results Summary
| Task | Model | Key Metric |
| :--- | :--- | :--- |
| Regression | Linear Regression | R² = [ 0.60] |
| Classification | Logistic Regression | Accuracy = [0.82] |
| Clustering | K-Means (K=4) | Silhouette Score = [0.35] |

## Report
The full detailed report can be found here: [project_report.pdf](project_report.pdf)
