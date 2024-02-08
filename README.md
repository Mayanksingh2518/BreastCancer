

```markdown
# Breast Cancer Classification

This repository contains a Python script for breast cancer classification using logistic regression. The script includes data loading, exploration, preprocessing, visualization, model building, and prediction.

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- NumPy
- Pandas
- scikit-learn
- Seaborn
- Matplotlib

You can install them using the following command:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/breast-cancer-classification.git
cd breast-cancer-classification
```

2. Run the Python script:

```bash
python breast_cancer_classification.py
```

3. Follow the instructions in the console to observe the results.

## Code Structure

- `breast_cancer_classification.py`: The main Python script.
- `README.md`: Documentation file.

## Dataset

The breast cancer dataset is loaded using scikit-learn's breast cancer dataset.

## Exploring the Data

- Displayed the first five rows of the dataset.
- Plotted a heatmap to visualize missing values (none in this dataset).
- Computed and displayed the correlation matrix.

## Data Preprocessing

- Added the target variable to the DataFrame.
- Explored basic information about the dataset.

## Data Visualization

- Created a large heatmap to visualize the correlation matrix.

## Feature Selection

- Defined a function to identify highly correlated features.
- Removed features with correlation above a specified threshold.

## Train-Test Split

- Split the data into training and testing sets.

## Logistic Regression Model

- Created and trained a logistic regression model.
- Made predictions on both training and testing sets.
- Displayed accuracy scores for both sets.

## Prediction for a New Data Point

- Provided a sample input data point.
- Used the trained model to predict the class of breast cancer.
- Printed the prediction result.

