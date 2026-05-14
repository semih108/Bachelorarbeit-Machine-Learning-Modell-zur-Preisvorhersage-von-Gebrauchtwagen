# Used Car Price Prediction – Training & Evaluation

## Overview
This project was developed as part of a Bachelor's thesis focusing on the prediction of used car prices using machine learning methods.  
The goal of the project is to analyze real-world vehicle market data and develop a prediction model capable of estimating vehicle prices based on selected features.

The implementation was created using Python and Jupyter Notebook.

---

## Features
- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Correlation analysis and heatmap visualization
- Feature engineering
- Multiple Linear Regression model
- Decision Tree Regression model
- Model evaluation using:
  - MAE (Mean Absolute Error)
  - R² Score
- Visualization of prediction results

---

## Dataset
The dataset contains real-world used car listings including features such as:

- Vehicle model
- Price
- Year of manufacture
- Mileage
- Fuel type
- Horsepower
- Transmission type
- Drive type

The data was collected and processed for research purposes within the scope of the thesis.

---

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Structure
```text
.
├── UsedCarPricePrediction_Training.ipynb
├── dataset.csv
├── README.md
└── images/
```

---

## Machine Learning Models

### Multiple Linear Regression
The first implemented model uses multiple linear regression to identify linear relationships between vehicle attributes and price.

### Decision Tree Regression
A decision tree model was additionally implemented to compare prediction performance with the linear regression approach.

---

## Evaluation Metrics

### Mean Absolute Error (MAE)
The MAE measures the average deviation between predicted and actual vehicle prices.

### R² Score
The R² score indicates how much variance of the target variable can be explained by the model.

---

## Example Results
| Model | MAE | R² |
|---|---|---|
| Linear Regression | ~7,554 € | 0.723 |
| Decision Tree | Improved compared to LR | Higher R² |

---

## How to Run the Project

### 1. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 2. Start Jupyter Notebook
```bash
jupyter notebook
```

### 3. Open the notebook
Open:
```text
UsedCarPricePrediction_Training.ipynb
```

and execute all cells.

---

## Purpose of the Project
The project demonstrates how machine learning techniques can be applied to real-world market data in order to support price estimation tasks in the automotive domain.

The focus of the thesis lies not only on prediction quality, but also on the comparison between interpretable statistical models and more complex machine learning approaches.

---

## Author
Semih Sönmez  
Bachelor of Science in Informatics  
FH Vorarlberg

---

## License
This project was created for academic purposes only.