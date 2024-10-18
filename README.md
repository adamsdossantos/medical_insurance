# Medical Insurance Cost Prediction with Linear Regression


## 1. Project Overview

This project implements a **Linear Regression** model to predict medical insurance costs based on various factors such as age, BMI, smoking status, number of children, and region. The goal is to create a model that can accurately predict the cost of medical insurance premiums based on these features.


## 2. Dataset Source

https://www.kaggle.com/datasets/mirichoi0218/insurance


## 3. Features
- **Data Preprocessing**: Data cleaning, feature engineering, handling missing values, and splitting into training and testing sets.
- **Model Training**: Training a Linear Regression model using scikit-learn to predict medical insurance costs.
- **Model Evaluation**: Evaluating the performance of the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
- **Visualization**: Visualization of relationships between features and predictions versus actual values.


## 4. Project Structure
    ├── insurance.csv                # Dataset file
    ├── medica)insurance_price.ipynb # Jupyter notebook with end-to-end implementation
    ├── README.md                    # Project documentation
    ├── requirements.txt             # Python dependencies
    └── .gitignore                   # Files to be ignored in version control

## 5. Getting Started

### Prerequisites
- Python 3.9 or higher
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- numpy
- seaborn

### Installation
1. Clone the repository:

```python
    git clone https://github.com/adamsdossantos/medical_insurance.git
    
```
2. Create a virtual environment and activate it:
```python
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:
```python
   pip install -r requirements.txt
```

4. Launch the Jupyter Notebook:
```python
    jupyter notebook medical_insurance_price.ipynb
```
## 6. Usage

Open the medical_insurance_price.ipynb file and follow the step-by-step instructions provided in the notebook. The notebook includes:

- **Data Loading and Preprocessing**: Load data from insurance.csv and perform data preprocessing, including encoding categorical variables like smoking status and region.
- **Model Training**: Train a Linear Regression model using features such as age, BMI, and smoking status to predict insurance costs.
- **Model Evaluation**:  Evaluate the model using metrics such as MAE, MSE, and R² to assess the accuracy of the predictions.
- **Visualization**:  Visualize relationships between various factors and insurance costs using scatter plots and residual analysis to validate model accuracy.


## 7. Results in Test

| Metric    | Value |
|-----------|-------|
| Mean Absolute Error  | 4260   |
| Root Mean Squared Error	 | 6182  |
| R-squared (R²)    | 75%   |
| 


## 8. Contributing

Feel free to open issues or submit pull requests if you find any bugs or want to improve the project.

## 9. License

This project is licensed under the MIT License - see the LICENSE file for details.







