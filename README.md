# 🏠 House Price Prediction

This project focuses on **data cleaning, preprocessing, feature engineering, and regression modeling** to predict house prices using machine learning techniques.

---

## 📂 Project Structure
- `house_data.csv` → Dataset used for training and testing.
- `house_price_model.py` / `notebook.ipynb` → Main code for preprocessing and model training.
- `requirements.txt` → Python dependencies.
- `README.md` → Project documentation.

---

## 🔧 Steps Performed
1. **Data Preprocessing**
   - Dropped unnecessary columns (`id`, `date`).
   - Handled missing values.
   - Detected and removed outliers using **IQR method**.
   - Applied **log transformation** to skewed numerical features.

2. **Feature Engineering**
   - Checked correlations with target variable (`price`).
   - Removed irrelevant/low-correlation features.
   - Standardized numerical features using **StandardScaler**.

3. **Modeling**
   - Split dataset into **train (80%)** and **test (20%)**.
   - Trained a **Linear Regression model**.
   - Evaluated using:
     - Mean Absolute Error (MAE)  
     - Root Mean Squared Error (RMSE)  
     - R² Score  

4. **Visualization**
   - Boxplots & histograms for outlier detection and distributions.
   - Scatter plot for **Actual vs Predicted** values.

---

