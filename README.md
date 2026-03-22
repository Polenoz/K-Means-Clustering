
# K-Means Clustering Project

**Note:** This project was developed and tested primarily in **Google Colab**. All instructions and code are fully compatible with Colab, and the recommended way to run and reproduce results is via the Colab badge below.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/K-Means-Clustering/blob/main/K_Means_Clustering_Projekt.ipynb)

## Overview
This project demonstrates how to use K-Means clustering to group colleges based on their features. The notebook includes data exploration, clustering, and comparison with actual labels.

## Contents
- `K_Means_Clustering_Projekt.ipynb`: Colab notebook with the full workflow
- `College_Data`: Dataset used for clustering
- `requirements.txt`: List of required Python packages

## Dataset
The dataset (`College_Data`) contains features of various colleges. It is loaded automatically from the repository when running in Colab.

## How to Run

### Google Colab (Recommended)
1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom. The dataset loads automatically from the repository.
4. No manual data upload or extra setup is required.

### Local (Jupyter, also possible)
1. Clone or download this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook with Jupyter: `jupyter notebook K_Means_Clustering_Projekt.ipynb`
4. Run all cells.

## Expected Results
- Data exploration and visualizations of college features
- K-Means clustering and comparison with actual labels
- Example output:

```
Confusion Matrix:
[[89  123]
 [ 12 553]]

Classification Report:

              precision    recall  f1-score   support

           0       0.88      0.42      0.57       212
           1       0.82      0.98      0.89       565

    accuracy                           0.83       777
   macro avg       0.85      0.70      0.73       777
weighted avg       0.84      0.83      0.80       777

```

Example installation:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
