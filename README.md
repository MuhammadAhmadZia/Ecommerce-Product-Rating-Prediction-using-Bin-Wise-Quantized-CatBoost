# Ecommerce-Product-Rating-Prediction-using-Bin-Wise-Quantized-CatBoost

This repository contains the official implementation of a green machine learning framework for sustainable e-commerce analytics. The study introduces a Bin-Wise Quantized CatBoost Regression approach for predicting ratings of newly launched products while minimizing computational energy consumption and carbon emissions.
Unlike conventional ML models that prioritize predictive accuracy alone, this work integrates environmental sustainability into the evaluation pipeline by measuring energy usage and CO₂ emissions during training.

Key Contributions:

> Implementation of Bin-Wise feature quantization (64, 128, 255 bins) before iterative boosting.

> Reduction of memory usage and training overhead.

> Up to 66% lower CO₂ emissions compared to standard CatBoost.

> Maintained or improved predictive accuracy.

> Achieved near-perfect performance (R² ≈ 0.99999 on Amazon dataset).

> Comparative evaluation against:

  >   Linear Regression

  >   Standard CatBoost

Datasets Used:

> Amazon product dataset

> Flipkart product dataset

Research Impact:

> This work bridges the gap between predictive performance and environmental responsibility by demonstrating that high-accuracy models can also be energy-efficient. The proposed framework positions Bin-Wise Quantized CatBoost as a sustainable alternative for large-scale e-commerce platforms.
