# K-Means Clustering Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/K-Means-Clustering/blob/main/K_Means_Clustering_Projekt.ipynb)

This repository reproduces the K-Means Clustering exercise from the course `Python für Data Science, Maschinelles Lernen & Visualization` for `Prüfungsaufgabe 1`.

## Overview

This project demonstrates how to use K-Means clustering to group colleges based on their features. The notebook includes data exploration, clustering, and comparison with actual labels.

## Contents

- `K_Means_Clustering_Projekt.ipynb`: Jupyter notebook with the full workflow
- `College_Data`: Dataset used for clustering
- `requirements.txt`: List of required Python packages

## Dataset

The dataset (`College_Data`) contains features of various colleges and is loaded directly from the repository when running the notebook.

## How to Run

### Google Colab (Recommended)

1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom in order.
4. No manual data upload is required.

### Local (Jupyter)

1. Clone or download this repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook with Jupyter:

```bash
jupyter notebook K_Means_Clustering_Projekt.ipynb
```

4. Run all cells from top to bottom.

## Expected Results

The notebook should reproduce the K-Means clustering example on the college dataset and show:

- data exploration and visualizations of college features
- K-Means clustering
- comparison of predicted clusters with actual labels
- confusion matrix
- classification report

Example output:

```text
Confusion Matrix:
[[ 89 123]
 [ 12 553]]

Classification Report:

              precision    recall  f1-score   support

           0       0.88      0.42      0.57       212
           1       0.82      0.98      0.89       565

    accuracy                           0.83       777
   macro avg       0.85      0.70      0.73       777
weighted avg       0.84      0.83      0.80       777
```

## Notes

This repository is intended as one of the required exercise repositories for `Prüfungsaufgabe 1`.
