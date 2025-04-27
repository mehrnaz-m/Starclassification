# Star Classification: Comparative Model Analysis

This project aims to classify stars into spectral classes based on various features using four different machine learning models. It includes a comparative analysis of their performance across multiple evaluation metrics.

## Dataset
- 240 stars
- 7 spectral classes
- Features:
  - 2 categorical features
  - 4 continuous numerical features
  - 1 discrete numerical feature
- No missing or duplicate entries.

## Exploratory Data Analysis (EDA)
- Histograms were plotted to understand numerical feature distributions.
- Scatter plots were used to study feature relationships with spectral classes.

## Models Used
- **Logistic Regression**: Chosen for its simplicity and baseline performance.
- **K-Means Clustering**: An unsupervised method to explore natural groupings.
- **Multilayer Perceptron (MLP)**: A neural network capturing non-linear patterns.
- **Convolutional Neural Network (CNN)**: Designed to leverage spatial patterns in the data.

## Evaluation Metrics
- **Accuracy**: Main metric used for comparison.
- **Precision, Recall, F1 Score**: To address the dataset imbalance and give a more nuanced performance analysis.

## Key Notes
- The dataset is unbalanced; this was considered when interpreting results.
- Although Random Forest was considered, logistic regression was chosen due to time constraints and its previous use in earlier assignments.

## Project Structure
- `EDA.ipynb`: Data exploration and visualization.
- `models/`: Model training and evaluation scripts.
- `results/`: Accuracy, precision, recall, and F1 score summaries.

## How to Run
1. Clone the repository.
2. Install required packages (`requirements.txt` if available).
3. Run the Jupyter notebooks or scripts step-by-step.
