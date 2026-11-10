# Car Price Prediction using Machine Learning

A machine learning project focused on predicting vehicle valuation based on physical and technical features using advanced regression analysis techniques.

## Dataset & Features
The model analyzes various automotive features to determine their impact on vehicle pricing. Key attributes evaluated include:
* **Engine Specifications:** Horsepower, engine size, fuel type.
* **Vehicle Dimensions:** Curb weight, wheel base, length, width, height.
* **Market Factors:** Mileage (highway/city MPG), brand prestige.

## Tech Stack & Libraries
* **Language:** Python
* **Data Processing:** Pandas, NumPy, SciPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn

## Machine Learning Methodology
1. **Exploratory Data Analysis (EDA):** Visualizing feature correlations using Seaborn heatmaps and Matplotlib distribution plots.
2. **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling.
3. **Model Training:** Implementing standard Linear Regression analysis.
4. **Model Refinement:** Utilizing **Ridge Regression** to prevent overfitting and applying **Grid Search** (`GridSearchCV`) for optimal hyperparameter tuning.

## Evaluation & Results
⚠️ **Work in Progress:** This project is actively under development. 

The baseline models are currently being trained. Once complete, this section will be updated with the finalized model performance metrics, including:
* **Mean Squared Error (MSE)** to evaluate prediction error variances.
* **R-squared ($R^2$) Score** to measure how well the vehicle features explain the price variations.
* **Residual plots** comparing baseline linear regression against the optimized Ridge regression model.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Sudhanshu-011/car-price-prediction-ml.git
   ```
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn
   ```
3. Run the python script or Jupyter Notebook to see the predictions.