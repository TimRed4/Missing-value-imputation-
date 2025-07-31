GAN-Based Imputation of Missing Time Series Data
This repository contains research and experimentation on applying Generative Adversarial Networks (GANs) for imputing missing values in time series data.

Overview
Time series data often suffers from missing values due to various reasons such as sensor failures, data corruption, or transmission issues. Traditional imputation methods (e.g., mean/median imputation, linear interpolation) may not capture the complex temporal patterns inherent in the data.

This project explores the use of GAN-based models, particularly TimeGAN and its variants, to learn realistic temporal dependencies and generate plausible replacements for missing values.

Contents
notebooks/ – Jupyter notebooks with experiments, model training, and visualizations

src/ – Source code for model implementations, preprocessing, and evaluation

data/ – Sample datasets and preprocessing scripts (if public datasets are used)

README.md – This file

 Models Explored
Vanilla GANs (adapted for time series)

TimeGAN

Conditional GANs for imputation

Baselines: Mean/median imputation, Kelman filter MICE, Interpolation

📊 Evaluation Metrics
RMSE (Root Mean Square Error)

Visualization of reconstructed sequences
