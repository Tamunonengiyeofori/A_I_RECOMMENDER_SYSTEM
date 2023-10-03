

# AI-Based Recommender System for Electronic Products


## Overview

This repository contains an AI-based Recommender System for electronic products. The system recommends electronic products to users based on their preferences and past interactions. It utilizes a dataset containing information about 50 distinct electronic projects purchased by 6,493 distinct users.

## Dataset

The dataset used in this project can be found [here](https://www.kaggle.com/datasets/datafiniti/amazon-and-best-buy-electronics?select=DatafinitiElectronicsProductData.csv). It includes information about electronic products and user interactions, making it ideal for building a recommendation system.

## Methodology

### Machine Learning Models
Four supervised machine learning models were employed:
- Singular Value Decomposition (SVD)
- Non-Negative Matrix Factorization (NMF)
- K Nearest Neighbor (KNN)
- Co-Clustering

### Recommendation Process
- User-item ratings prediction was done using item-based Pearson similarity and cosine similarity.
- Models were cross-validated using 5-fold cross-validation to assess their performance.

### Model Selection
The Machine Learning models implemented Include SVD, NMF, CoClustering, KNN and the best machine learning model was selected based on performance metrics:
- Root Mean Square Error (RMSE)
- Mean Absolute Error (MAE)

## Results

- The SVD model demonstrated superior performance with low RMSE and MAE values, indicating high accuracy and consistency in predicting user-item ratings.
- NMF, Co-Clustering, and KNN models provided reasonable predictions but showed less consistent performance across different folds due to greater standard deviations in RMSE and MAE values.

## Usage

You can use this recommender system by following the instructions in the code provided in the project's GitHub repository: [GitHub Repository](https://github.com/Tamunonengiyeofori/A_I_RECOMMENDER_SYSTEM.git).

## Contributing

If you would like to contribute to this project, please follow our [Contributing Guidelines](CONTRIBUTING.md).



