# Machine_Learning_Projects_2025
# 🏡 House Price Prediction using Linear Regression

This project uses **Linear Regression** to predict house prices based on various features from a housing dataset (like area, number of rooms, location features, etc.).

---

## 📁 Project Structure
 data/ # Dataset CSV (optional)
├── house_price_model.py # Main Python script (or Jupyter Notebook)
├── requirements.txt # Required Python packages
└── README.md # Project documentation


---

## 📊 Dataset

This project assumes a dataset where:
- Each row represents a house
- Columns include features like area, number of rooms, etc.
- The target variable is `SalePrice` (the house price)

If you're using the **California Housing dataset** or your own `.csv` file, make sure `"SalePrice"` exists as a column.

---

## 🧠 What the Model Does

- Splits the data into **training (80%)** and **testing (20%)**
- Trains a **Linear Regression model** on the training data
- Predicts the prices of houses in the test data
- Evaluates the model using **Root Mean Squared Error (RMSE)**

---

## 🛠️ How to Run
**Clone the repo:**

   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction

**Install the required package**

bash
Copy code
pip install -r requirements.txt

**Run the model:**

If using a .py file:

bash
Copy code
python house_price_model.py
If using a Jupyter Notebook:
Open it with Jupyter and run all cells.
