# 🛍️ Customer Shopping Behavior Analysis  

## 📌 Project Overview  

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories. The objective is to uncover insights into:

- Spending patterns  
- Customer segmentation  
- Product preferences  
- Subscription behavior  

These insights help guide **data-driven business decisions**.

---

## 📊 Dataset Summary  

- **Total Records:** 3,900  
- **Total Columns:** 18  

### 🔹 Key Features  

**Customer Demographics**
- Age  
- Gender  
- Location  
- Subscription Status  

**Purchase Details**
- Item Purchased  
- Category  
- Purchase Amount  
- Season  
- Size  
- Color  

**Shopping Behavior**
- Discount Applied  
- Promo Code Used  
- Previous Purchases  
- Purchase Frequency  
- Review Rating  
- Shipping Type  

### 🔹 Missing Data  
- 37 missing values in the **Review Rating** column  
- Handled using **median imputation per product category**

---

## 🧹 Data Preparation & Cleaning (Python)  

The following steps were performed using **Pandas**:

- Data loading and inspection (`df.info()`, `describe()`)
- Missing value handling using **category-wise median**
- Column standardization to **snake_case**
- Feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- Data consistency checks:
  - Removed redundant `promo_code_used`
- Integrated the clean dataset into **PostgreSQL**

---

## 🗄️ SQL Business Analysis  

The cleaned dataset was analyzed using **PostgreSQL**. Key business queries included:

1. Revenue by Gender  
2. High-Spending Discount Users  
3. Top 5 Products by Rating  
4. Shipping Type Comparison  
5. Subscribers vs Non-Subscribers  
6. Discount-Dependent Products  
7. Customer Segmentation  
8. Top 3 Products per Category  
9. Repeat Buyers & Subscription Likelihood  
10. Revenue by Age Group  

---

## 📈 Power BI Dashboard  

An interactive dashboard was created to visualize:

- Customer demographics  
- Revenue patterns  
- Purchase category trends  
- Subscription impacts  
- Seasonal behavior insights  

<img width="1265" height="627" alt="Screenshot 2025-12-07 193141" src="https://github.com/user-attachments/assets/8d97c869-10d0-48df-ab48-000a7e9f9f70" />

---

## 💡 Business Recommendations  

Based on the analysis, the following recommendations were derived:

- Boost subscriptions using exclusive member perks  
- Implement customer loyalty programs  
- Review discount strategies to protect profit margins  
- Highlight top-rated products  
- Target high-value age groups and express-shipping users  

---

## 🛠️ Tools & Technologies Used  

- **Python** (Pandas, NumPy, Matplotlib)  
- **PostgreSQL** (SQL Analytics)  
- **Power BI** (Interactive Dashboard)  
- **Jupyter Notebook**

---

## 📂 Project Status  

✅ Data Cleaning Complete  
✅ SQL Analysis Completed  
✅ Power BI Dashboard Created  
✅ Business Insights Generated  

---

## 👤 Author  

**M.H.R. Perera**  
Aspiring Data Analyst | Software Engineering Background  
📍 Sri Lanka  

---

## ⭐ If you find this project useful  
Feel free to **star this repository**, share feedback, or connect with me on LinkedIn!
