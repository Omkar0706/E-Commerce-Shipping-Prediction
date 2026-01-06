# 📦 E-Commerce Shipping Prediction

A **Machine Learning-based project** to build a predictive model that determines whether an e-commerce shipment will be delivered **on time or late** using real customer shipping data.  
This system helps logistics teams and e-commerce platforms make **data-driven decisions** to improve delivery performance.

---

## 🧠 Project Overview

Shipping performance plays a crucial role in customer satisfaction for online retail platforms.  
This project analyzes historical e-commerce shipping data to:

- Understand delivery patterns  
- Identify key factors affecting shipment delays  
- Build and evaluate machine learning models to predict delivery punctuality  

⚙️ **Problem Type:** Binary Classification  
- **Target Variable:** `Reached.on.Time_Y.N`  
  - `0` → On Time  
  - `1` → Late  

📊 **Dataset Source:**  
E-Commerce Shipping Data (e.g., Kaggle)

---

## 📊 Features Used

| Feature | Description |
|------|------------|
| Warehouse_block | Warehouse identifier |
| Mode_of_Shipment | Delivery mode (Flight / Road / Ship) |
| Customer_care_calls | Number of customer care calls |
| Cost_of_the_Product | Product price |
| Discount_offered | Discount applied |
| Weight_in_gms | Package weight |
| Reached.on.Time_Y.N | Target label (1: Late, 0: On Time) |

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **pandas**
- **scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## 🔍 Methodology

1. **Data Collection**  
   - Load and inspect the dataset  

2. **Exploratory Data Analysis (EDA)**  
   - Analyze data distributions  
   - Identify correlations  
   - Visualize insights  

3. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical features  
   - Scale numerical features  

4. **Model Training**  
   Trained and evaluated multiple classification models:
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - XGBoost 

5. **Evaluation Metrics**  
   - Accuracy  
   - Confusion Matrix  
   - Precision, Recall  
   - F1-score  

6. **Best Model Selection**  
   - Selected the model with highest overall performance  

---

## 🧪 Sample Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Omkar0706/E-Commerce-Shipping-Prediction.git
cd E-Commerce-Shipping-Prediction
```
### 2️⃣ Install Dependencies
``` bash
pip install -r requirements.txt
```
### 3️⃣ Run the Notebook
``` bash
jupyter notebook
```
---

## 📈 Expected Outcomes

✔ Predict whether a shipment will be **on time or delayed**  

✔ Gain valuable business insights such as:

- Heavy-weight packages are more likely to be delayed  
- High-discount orders often impact delivery timelines  
- Shipment mode significantly affects delivery performance
---

## 🗂 Project Structure
``` bash
E-Commerce-Shipping-Prediction/
│
├── dataset/                # Dataset files
├── notebooks/              # Jupyter notebooks
├── models/                 # Saved ML models (if any)
├── requirements.txt
└── README.md
```
---
## 💡 Use Cases

- Predict shipment delays before dispatch  
- Improve logistics planning  
- Enhance customer satisfaction  
- Reduce operational costs  

---

## 🤝 Contributing

Contributions are welcome!  
You can enhance this project by:

- Adding more ML models  
- Improving feature engineering  
- Deploying the model using Flask or Streamlit  

---

## 📄 License

This project is **open-source** and available for **educational and learning purposes**.  
Feel free to use, modify, and share.

