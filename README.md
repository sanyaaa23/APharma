# APharma

# Disease Classifier Based on Symptoms

## Introduction
The Disease Classifier Based on Symptoms is a machine learning-based application designed to assist healthcare professionals in diagnosing diseases efficiently and accurately based on symptoms and patient data. This project leverages various machine learning algorithms to predict diseases using patient records, medical history, and lab results.
This AI-powered system can help streamline diagnostic processes, reduce human error, and improve healthcare outcomes by automating disease classification. The model uses extensive datasets covering multiple diseases, enabling it to provide reliable and accurate predictions.

## Features
- **Machine Learning Models**: Implements multiple algorithms, including:
  - Decision Trees
  - Logistic Regression
  - Random Forest
  - Support Vector Machines (SVM)
  - Naïve Bayes
- **Comprehensive Datasets**: Utilizes structured datasets containing:
  - Symptoms
  - Patient demographic information
  - Lab test results
  - Disease labels (Prognosis)
- **Automated Data Processing**:
  - Handles missing values
  - Encodes categorical data
  - Splits dataset into training and testing sets
- **Data Visualization**:
  - Symptom distribution plots
  - Correlation heatmaps
- **Evaluation Metrics**:
  - Accuracy score
  - Confusion matrix
  - Classification report
- **Open Source & Extensible**: The repository includes code, datasets, and documentation to help users extend and modify the project.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy`: Data manipulation
  - `seaborn`, `matplotlib`: Data visualization
  - `scikit-learn`: Machine learning models and evaluation
- **Frameworks**:
  - Flask (if deployed as a web app)
  - Jupyter Notebook
- **Data Storage**: CSV files for structured datasets


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/sanyaaa23/APharma
   cd APharma
   ```
2. Install dependencies:
      ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook
   ```
4. Open pharmacy.ipynb and execute the cells.

## Usage
1. Load the dataset into the notebook.
2. Train the machine learning models using the provided scripts.
3. Input patient symptoms and get predictions.
4. Visualize model performance with evaluation metrics.

## Model Training
The disease classification models are trained on labeled datasets, with features including:
- **Symptoms**
- **Demographics**
- **Lab Results**
- **Medical History**

The models are evaluated using metrics such as accuracy, precision, recall, and F1-score.










