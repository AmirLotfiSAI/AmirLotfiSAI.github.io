---
title: "Project: Predicting Magnesium Alloy Corrosion with Machine Learning"
excerpt: "A comprehensive project where I developed an end-to-end machine learning workflow to predict the corrosion rate of magnesium alloys, achieving a predictive accuracy (R²) of 0.892. <br/><img src='/images/500x300.png'>"
collection: portfolio
---

This project addresses the slow and costly process of developing corrosion-resistant magnesium (Mg) alloys by creating a robust, data-driven predictive model. The goal was to build a powerful tool for the rapid, *in silico* screening of novel alloy compositions to accelerate the design of next-generation materials.

## Project Workflow

The project followed a systematic, multi-stage data-driven workflow:

1.  **Data Collection & Preprocessing:** I aggregated experimental data from approximately 30 peer-reviewed scientific articles, resulting in an initial dataset of 1347 points. This was followed by a rigorous preprocessing stage—including feature pruning, sample filtering, and a custom encoding scheme—to produce a final, high-quality dataset of 746 points for model development. 
2.  **Model Development & Evaluation:** I systematically trained and evaluated twelve different machine learning algorithms, including Linear Regression, K-Neighbors Regressor (KNN), a Multi-layer Perceptron (MLP), and XGBoost (XGB). All models were optimized using Grid Search with Cross-Validation to tune their hyperparameters.
3.  **Final Model Selection:** A custom-weighted Voting Regressor was identified as the optimal model. It combines the predictive strengths of three diverse, high-performing algorithms: K-Neighbors Regressor (weight=0.15), MLP Regressor (weight=0.24), and XGBoost (weight=0.61).

## Key Results

* The final Voting Regressor model achieved a high predictive accuracy, with a **coefficient of determination (R²) of 0.892** on the unseen test data. 
* The model's feature importance analysis, using SHAP values, confirmed well-established metallurgical principles, identifying the concentrations of NaCl, Mg, Zn, and Al as key drivers of corrosion.

This project successfully demonstrates a workflow for creating a reliable predictive tool that can significantly shorten the development cycle for new, high-performance magnesium alloys. 
