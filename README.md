# Crop Classification Using Soil Features

This project identifies the most predictive feature for classifying crop types based on soil characteristics. Using a dataset of soil measures, it evaluates each feature's predictive performance and determines which single feature best classifies the target variable `crop`.

## Dataset Overview
The dataset includes the following columns:

- **N**: Nitrogen concentration in soil
- **P**: Phosphorus concentration in soil
- **K**: Potassium concentration in soil
- **ph**: Soil pH value
- **crop**: The target variable representing different crop types

## Key Output
The strongest predictive feature for classifying crops was determined to be **K** (Potassium), achieving an accuracy of approximately **0.291**.

## Methodology
1. **Data Loading**: The dataset is loaded and inspected to understand its structure.
2. **Feature Evaluation**: Each feature is evaluated individually for its predictive power using a simple decision tree classifier.
3. **Model Training**:
   - Split the dataset into training and testing sets (70% training, 30% testing).
   - Train a Decision Tree Classifier using one feature at a time.
4. **Performance Metric**: Accuracy is used as the evaluation metric.
5. **Result**: The feature with the highest accuracy is selected as the best predictive feature.

## Results
The feature `K` (Potassium) was found to have the highest predictive accuracy for classifying crop types in this dataset.
