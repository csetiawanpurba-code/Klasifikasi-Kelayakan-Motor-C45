# Motorcycle Sale Eligibility Classification Using C4.5

## Project Overview

This project focuses on classifying motorcycle sale eligibility using a decision tree approach based on the C4.5 algorithm concept.

The model analyzes motorcycle attributes, including model, year, engine capacity, mileage, fuel type, modifications, engine condition, oil type, transmission, engine type, and displacement, to determine whether a motorcycle is eligible for sale.

## Project Objectives

- Classify motorcycle sale eligibility.
- Apply data preprocessing and transformation techniques.
- Calculate entropy, information gain, split information, and gain ratio.
- Analyze feature importance.
- Evaluate classification model performance.
- Visualize decision tree rules and prediction results.

## Methodology

1. **Data Selection**
   - Load motorcycle data from an Excel dataset.
   - Select relevant features and the target variable.

2. **Data Preprocessing**
   - Remove duplicate records.
   - Handle missing values using mode for categorical features and median for numerical features.
   - Convert categorical variables into numerical values using Label Encoding.

3. **Data Transformation**
   - Normalize selected numerical features using MinMaxScaler.

4. **Data Mining**
   - Calculate dataset entropy.
   - Calculate information gain, split information, and gain ratio.
   - Identify the feature with the highest gain ratio.
   - Train an entropy-based Decision Tree classifier.

5. **Model Evaluation**
   - Split the dataset into 80% training data and 20% testing data.
   - Evaluate the model using accuracy, precision, recall, and F1-score.
   - Generate a confusion matrix and classification report.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Excel


## How to Run

1. Clone this repository.


git clone https://github.com/csetiawanpurba-code/Klasifikasi-Kelayakan-Motor-C45.git

2. Install the required libraries.


pip install pandas numpy seaborn matplotlib scikit-learn colorama openpyxl tabulate


3. Open `KasifikasiMotor.ipynb` using Jupyter Notebook or Google Colab.
4. Make sure the dataset path in the notebook matches the actual Excel filename.
5. Run the notebook cells sequentially.

## Author

**Christy Setiawan Purba**

GitHub: https://github.com/csetiawanpurba-code
