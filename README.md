# 📊 **E-commerce Regression Analysis**  

## 📌 Project Overview  
This project focuses on performing **regression analysis** on an E-commerce dataset to predict customer spending and analyze key factors influencing revenue. By leveraging **Linear Regression**, we aim to understand purchasing patterns, optimize pricing strategies, and enhance marketing decisions.  

---

## ⚙️ **Installation**  
Ensure you have Python 3 installed along with the following dependencies:  

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## 📊 **Data Exploration**  
The dataset includes multiple features related to customer orders, such as:  
- **Customer Data** (User ID, Location, Purchase History)  
- **Product Details** (Category, Price, Discount)  
- **Transaction Information** (Order Value, Payment Method, Order Status)  

### 📌 Key Questions Explored:  
1. What factors impact **sales revenue** the most?  
2. How do **discounts and promotions** affect customer spending?  
3. Can we predict **customer purchase behavior** using regression models?  

---

## 🏢 **Implementation**  
### **1⃣ Data Preprocessing:**  
- Handling missing values  
- Encoding categorical features  
- Normalizing numerical values  

### **2⃣ Exploratory Data Analysis (EDA):**  
- Visualizing data distributions  
- Identifying key patterns  

### **3⃣ Regression Model:**  
We implemented **Simple Linear Regression** and **Multiple Linear Regression** to predict order values.  

The **Linear Regression equation** used:  

$$
Y = \beta_0 + \beta_1X_1 + \beta_2X_2 + ... + \beta_nX_n + \epsilon
$$

where:  
- \( Y \) = Predicted Sales Revenue  
- \( X_1, X_2, ..., X_n \) = Independent Variables (Price, Discount, etc.)  
- \( \beta \) = Coefficients  
- \( \epsilon \) = Error term  

---

## 📈 **Results & Insights**  
👉 **Feature Importance:**  
- Product price and order quantity were the strongest predictors of revenue.  
- Discounts had a moderate impact on sales volume.  

👉 **Model Performance:**  
- Achieved **R² Score:** *0.85* (indicating a strong predictive model).  
- **Root Mean Square Error (RMSE):** *Low error rate indicating good accuracy.*  

👉 **Business Impact:**  
- Insights can be used for **targeted marketing and pricing optimization**.  





