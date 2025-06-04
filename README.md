# K-Nearest Neighbors (KNN) Classification

This repository contains the implementation of Task 6 for the AI & ML Internship, focusing on K-Nearest Neighbors (KNN) classification using the Iris dataset.

## Project Structure
- `task.ipynb`: Jupyter Notebook containing the complete implementation
- `Iris.csv`: Dataset used for the task
- `README.md`: This documentation file

## Implementation Details

### 1. Data Preprocessing
- Loaded the Iris dataset
- Dropped the unnecessary 'Id' column
- Explored the dataset characteristics

### 2. Data Visualization
- Created scatter plots to visualize relationships between features
- Examined the distribution of species in the dataset

### 3. Model Implementation
- Split the data into training and testing sets (80/20 ratio)
- Standardized the features using StandardScaler
- Implemented KNN classifier with different K values
- Determined optimal K value by analyzing error rates
- Evaluated the model using:
  - Confusion matrix
  - Classification report
  - Accuracy score

### 4. Decision Boundary Visualization
- Visualized decision boundaries using the
