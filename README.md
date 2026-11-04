# F20DL 2026/2027 — Rice Variety Classification

**Course:** Data Mining and Machine Learning (F20DL)  
**Topic:** Multi-Modal Rice Variety Classification  
**Datasets:** UCI Rice (Cammeo & Osmancik) + Kaggle Rice Image Dataset

## Project Structure

```
f20dl-rice-classification/
├── data/
│   ├── tabular/        # UCI Rice morphological features (CSV)
│   └── images/         # Kaggle Rice Image Dataset
├── notebooks/
│   ├── 01_eda.ipynb            # Exploratory Data Analysis (R2)
│   ├── 02_clustering.ipynb     # K-Means / EM clustering (R2)
│   ├── 03_baseline_models.ipynb # Decision Tree, Naive Bayes, kNN, etc. (R3)
│   ├── 04_mlp.ipynb            # Multi-Layer Perceptron (R4)
│   └── 05_cnn.ipynb            # Convolutional Neural Network (R4)
├── src/
│   ├── preprocessing.py
│   ├── models.py
│   └── evaluate.py
├── models/             # Saved model weights
├── results/            # Plots, tables, metrics
├── report/             # Final 6-page PDF report
├── environment.yml
└── README.md
```

## Datasets

- **Tabular:** [UCI Rice (Cammeo and Osmancik)](https://archive.ics.uci.edu/dataset/545/rice+cammeo+and+osmancik)
- **Images:** [Rice Image Dataset on Kaggle](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)

## Requirements Coverage

| Requirement | Notebooks |
|---|---|
| R1 — Project direction | All |
| R2 — EDA + Clustering | 01, 02 |
| R3 — Baseline ML models | 03 |
| R4 — Neural Networks | 04, 05 |

## Setup

```bash
conda env create -f environment.yml
conda activate f20dl-rice
jupyter lab
```

## Team Members

| Member | Responsibility |
|---|---|
| 1 | Data acquisition & preprocessing |
| 2 | EDA & clustering |
| 3 | Baseline ML models |
| 4 | MLP & CNN |
| 5 | Report & evaluation |
