# Smart Manufacturing Analytics & Prediction System

## Overview
This project uses Machine Learning techniques to predict manufacturing defect rates using production and sensor-related data.

The system analyzes factors such as:
- Temperature
- Machine Speed
- Downtime
- Humidity
- Material Age

and predicts the probability of manufacturing defects.

---

## Dataset Information

- Total Samples: 1000
- Features Used: 5
- Target Variable: Defect Rate

### Features
1. Temperature (C)
2. Machine Speed (RPM)
3. Downtime (min)
4. Humidity (%)
5. Material Age (months)

---

## Machine Learning Models Used

### 1. Linear Regression
Baseline regression model used for prediction.

### 2. Random Forest Regressor
Advanced ensemble learning model used to improve prediction accuracy.

---

## Linear Regression Results

- RMSE: 0.1004
- MAE: 0.0783
- R² Score: 0.3409

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Files

- `manufacturing_project.ipynb` → Complete notebook with code and visualizations
- `results.txt` → Model output results
- `requirements.txt` → Required Python libraries
- `README.md` → Project documentation

---

## How to Run the Project

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Then open:
`manufacturing_project.ipynb`

---

## Key Learnings

- Data preprocessing and feature engineering
- Model training and evaluation
- Comparing machine learning algorithms
- Visualization of manufacturing data
- Using Git and GitHub for project management

---

## Author

Shalini Reddy  
B.Tech CSE (AI)
