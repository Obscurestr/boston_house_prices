
This project builds a **multivariable linear regression** model to predict housing prices using the **Boston Housing Dataset**. The goal is to explore relationships between housing features and prices, and to use the model to estimate the value of a specific property.

---

## 📊 Dataset Information

The dataset includes various attributes of Boston neighborhoods, such as:

- `CRIM`: Crime rate per capita  
- `RM`: Average number of rooms per dwelling  
- `NOX`: Nitric oxide concentration (pollution)  
- `DIS`: Distance to employment centers  
- `LSTAT`: % of lower-status population  
- `PTRATIO`: Student-teacher ratio  
- ...and several others.

📦 **Source:** `sklearn.datasets.load_boston()` (Note: Deprecated in recent versions of scikit-learn)

---

## 🧠 Project Steps

1. **Exploratory Data Analysis (EDA)**  
   - Visualizing distributions and correlations  
   - Understanding outliers and feature importance  

2. **Data Preprocessing**  
   - Handling missing data  
   - Normalizing and transforming features if needed  

3. **Multivariable Regression**  
   - Building the linear regression model using scikit-learn  

4. **Model Evaluation**  
   - R² score  
   - Mean Squared Error (MSE)  
   - Residual analysis  

5. **Price Estimation**  
   - Predicting the value of a sample property based on chosen features  

---

## ⚙️ Technologies Used

- Python  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/Obscurestr/boston_house_prices.git
cd boston_house_prices

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook or script
jupyter notebook Boston_Housing_Regression.ipynb
```

---

## 📈 Sample Prediction

Estimate the price of a property with:
- 8 rooms  
- High pollution (NOX in 75th percentile)  
- Low poverty (LSTAT in 25th percentile)  
- Close distance to town  
- Reasonable student-teacher ratio

--- 

 
 

 

