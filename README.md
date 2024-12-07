
# Mouse Movement Detection: Human vs. Bot Prediction

This repository contains a machine learning project that analyzes mouse movement patterns to predict whether the user is a human or a bot. The project leverages various data processing and machine learning techniques to build an effective prediction model.

## Project Overview

The main notebook, `MouseMovementDetection.ipynb`, performs the following tasks:

1. **Data Analysis and Visualization:** 
   - Exploratory data analysis (EDA) of mouse movement patterns.
   - Visualization of user actions and directions using heatmaps, count plots, and correlation matrices.

2. **Feature Engineering:** 
   - Identification of significant features from raw data.
   - Dimensionality reduction techniques like PCA and T-SNE.

3. **Model Training and Evaluation:** 
   - Implementation of various classification models:
     - Decision Trees
     - Support Vector Machine (SVM)
     - Random Forest
     - AdaBoost
     - Multi-Layer Perceptron (MLP)
     - LightGBM

   - Evaluation using metrics like accuracy, classification reports, and ROC curves.

4. **Hyperparameter Tuning:** 
   - Use of GridSearchCV to fine-tune hyperparameters for models like AdaBoost and Random Forest.

## How to Use

- Clone the repository:
  ```bash
  git clone https://github.com/AnnonymousBanda/MouseMovementDetection.git
  cd Mouse-Movement-Detection
  ```

- Open `MouseMovementDetection.ipynb` in Jupyter Notebook or another compatible environment.

- Run the notebook cells sequentially to:
  - Explore the dataset.
  - Train and evaluate the models.
  - Visualize the results.

## Project Highlights

- **Visualization:** Clear and insightful plots to understand mouse movement behavior.
- **Machine Learning Models:** Comparison of multiple classifiers to identify the best-performing model.
- **Interpretability:** Focus on understanding which features are most influential in distinguishing between humans and bots.
