# parkinsons_synthetic_data_generation

# Parkinson's Progression Prediction


## Overview

This project focuses on predicting the progression of Parkinson's disease using machine learning techniques. The dataset used is the Parkinson's Progression dataset, containing clinical and biomedical features related to Parkinson's disease progression. We explore the use of Generative Adversarial Networks (GANs) to generate synthetic data and enhance the performance of machine learning models.

## Motivation

In the field of machine learning, having a robust and diverse dataset is crucial for building effective models. Generating synthetic data using GANs and evaluating its impact on model performance is a key aspect of this project. By combining original and synthetic data, we aim to improve model generalization and performance.

## Results

- **Simple GAN:** Trained a basic Generative Adversarial Network to generate synthetic data.
  
- **Wasserstein GAN (wGAN):** Implemented a Wasserstein GAN and achieved a similarity of 49.9% between original and synthetic data.

- **Random Forest Model:**
  - Trained a Random Forest model on the original data, resulting in a Mean Absolute Error (MAE) of 0.2.
  - Trained a Random Forest model on the combined dataset (original + synthetic data), achieving a significantly lower MAE of 0.002.

## Acknowledgments

[- Mention any resources, datasets, or libraries you found helpful.](https://www.kaggle.com/datasets/thedevastator/unlocking-clues-to-parkinson-s-disease-progressi)https://www.kaggle.com/datasets/thedevastator/unlocking-clues-to-parkinson-s-disease-progressi


