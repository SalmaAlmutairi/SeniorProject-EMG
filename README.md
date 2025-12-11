# Senior Project - EMG

This repository contains the code and experiments for our senior project on **EMG-based neuromuscular assessment**.  
The goal of this project is to build machine learning models that classify neuromuscular strength levels using features extracted from **EMG (Electromyography) signals**.

## Repository Structure

- `SANDS_FINAL_VER_CATBOOST.ipynb`  
  Final notebook for training and evaluating the **CatBoost** model on the EMG dataset.

- `SANDS_FINAL_VER_RANDOM_FOREST.ipynb`  
  Final notebook for training and evaluating the **Random Forest** model.

- `SVM_RBF_Final_SANDS.ipynb`  
  Final notebook for training and evaluating the **SVM with RBF kernel** model.

> Each notebook includes: data preprocessing, feature selection/engineering, model training, evaluation, and result visualization.

## Project Objectives

- Use EMG-derived features to classify neuromuscular strength levels.
- Compare different machine learning models (CatBoost, Random Forest, SVM-RBF).
- Evaluate performance using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.
- Provide an interpretable and clinically useful decision-support tool.

## Dataset

- EMG data collected from subjects
- Each record contains:
  - EMG-derived features (time-domain and/or frequency-domain).
  - Clinical labels describing neuromuscular strength level or class.


## Requirements

Main libraries used in the notebooks include (but are not limited to):

- Python 3.x
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn` (if used)
- `catboost`

You can install the required packages via:

```bash
pip install -r requirements.txt

