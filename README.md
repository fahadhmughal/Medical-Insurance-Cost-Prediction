# Medical Insurance Cost Prediction

## Project Description
This project predicts individual medical insurance costs using machine learning techniques. Using a publicly available dataset from Kaggle, the model analyzes features like age, BMI, smoking status, and more to estimate the expected insurance charges. This can help insurance providers in risk assessment and individuals in planning their medical expenses.  

## Dataset
- **Source:** [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Description:** The dataset contains information on 1,338 individuals, including:
  - `age`: Age of primary beneficiary
  - `sex`: Gender of the individual
  - `bmi`: Body Mass Index
  - `children`: Number of children/dependents
  - `smoker`: Smoking status
  - `region`: Residential area
  - `charges`: Individual medical insurance cost (target variable)

## Features
- **Age:** Continuous numeric value.
- **Sex:** Categorical feature (male/female).
- **BMI:** Body Mass Index (numeric).
- **Children:** Number of children covered by insurance.
- **Smoker:** Categorical feature (yes/no).
- **Region:** Categorical feature representing location.
- **Charges:** Target variable (insurance cost).

## Techniques Used
- **Exploratory Data Analysis (EDA)**
  - Visualization of feature distributions
  - Correlation analysis
  - Outlier detection
- **Data Preprocessing**
  - Handling categorical features via one-hot encoding
  - Scaling numeric features
  - Train-test split
- **Machine Learning Models**
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- **Evaluation Metrics**
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

## Results
- **Best Model:** Random Forest Regressor  
- **Performance Metrics:**  
  - MAE: ~1200  
  - RMSE: ~1800  
  - R² Score: 0.87  

> Results indicate that the model can reasonably predict insurance charges based on personal attributes, with smoking status and BMI being the most significant factors.


## Technologies Used
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Future Work
- Incorporate additional datasets to improve model generalization.
- Test deep learning models for enhanced prediction accuracy.
- Develop a web-based interface for real-time insurance cost estimation.

## Author
**Fahad Mughal**  
[GitHub](https://github.com/fahadhmughal) | [LinkedIn](www.linkedin.com/in/muhammad-fahad-68580b299)

