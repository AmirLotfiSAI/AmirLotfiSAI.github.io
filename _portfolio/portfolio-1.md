---
title: "Project: Predicting Magnesium Alloy Corrosion with Machine Learning"
[cite_start]excerpt: "A comprehensive project where I developed an end-to-end machine learning workflow to predict the corrosion rate of magnesium alloys, achieving a predictive accuracy (R²) of 0.892. [cite: 7]"
collection: portfolio
---

[cite_start]This project addresses the slow and costly process of developing corrosion-resistant magnesium (Mg) alloys by creating a robust, data-driven predictive model. [cite: 3] [cite_start]The goal was to build a powerful tool for the rapid, *in silico* screening of novel alloy compositions to accelerate the design of next-generation materials. [cite: 8]

## Project Workflow

The project followed a systematic, multi-stage data-driven workflow:

1.  [cite_start]**Data Collection & Preprocessing:** I aggregated experimental data from approximately 30 peer-reviewed scientific articles, resulting in an initial dataset of 1347 points. [cite: 41, 42] [cite_start]This was followed by a rigorous preprocessing stage—including feature pruning, sample filtering, and a custom encoding scheme—to produce a final, high-quality dataset of 746 points for model development. [cite: 35, 52]
2.  [cite_start]**Model Development & Evaluation:** I systematically trained and evaluated twelve different machine learning algorithms, including Linear Regression, K-Neighbors Regressor (KNN), a Multi-layer Perceptron (MLP), and XGBoost (XGB). [cite: 82] [cite_start]All models were optimized using Grid Search with Cross-Validation to tune their hyperparameters. [cite: 83]
3.  [cite_start]**Final Model Selection:** A custom-weighted Voting Regressor was identified as the optimal model. [cite: 39] [cite_start]It combines the predictive strengths of three diverse, high-performing algorithms: K-Neighbors Regressor (weight=0.15), MLP Regressor (weight=0.24), and XGBoost (weight=0.61). [cite: 88]

## Key Results

* [cite_start]The final Voting Regressor model achieved a high predictive accuracy, with a **coefficient of determination (R²) of 0.892** on the unseen test data. [cite: 7]
* [cite_start]The model's feature importance analysis, using SHAP values, confirmed well-established metallurgical principles, identifying the concentrations of NaCl, Mg, Zn, and Al as key drivers of corrosion. [cite: 241, 243]

[cite_start]This project successfully demonstrates a workflow for creating a reliable predictive tool that can significantly shorten the development cycle for new, high-performance magnesium alloys. [cite: 438]
