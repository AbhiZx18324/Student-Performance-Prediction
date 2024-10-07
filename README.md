# Student Performance Prediction

This repository contains a project focused on predicting the final exam scores (G3) of secondary school students based on various features. The project uses a dataset from the UCI Machine Learning Repository and applies different machine learning techniques to forecast student performance.

## Dataset

- **Source**: UCI Machine Learning Repository
- **Dataset URL**: [Link to Dataset](https://archive.ics.uci.edu/ml/datasets/student+performance)
- **Author**: P. Cortez, A. Silva
- **Paper**: Using Data Mining to Predict Secondary School Student Performance (2008)

### Dataset Features:
1. **Demographic features**: Gender, age, family size, etc.
2. **Social and educational factors**: Study time, parental education, and school support.
3. **Alcohol consumption and health status**.
4. **Grades**: G1 (first period), G2 (second period), and G3 (final grade - target variable).

## Objective

The objective of this project is to predict the final grade (G3) of students using the given features.

## Project Structure

- **`student-performance-prediction.ipynb`**: Main Jupyter notebook that contains the data loading, preprocessing, feature exploration, model training, and evaluation processes.
- **`requirements.txt`**: Lists the required dependencies to reproduce this project.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/student-performance-prediction.git
    cd student-performance-prediction
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook student-performance-prediction.ipynb
    ```

## Dependencies

- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn

To install the dependencies, run:

```bash
pip install -r requirements.txt
