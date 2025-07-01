# 📦 Amazon Product Review Analysis – Capstone Project

## 🧩 Project Overview  
As a Junior Data Analyst at **RetailTech Insights**, I conducted an exploratory analysis of product and review data scraped from Amazon. The goal was to uncover insights into product pricing, customer ratings, and engagement trends to help e-commerce sellers make data-informed decisions around **marketing**, **product improvements**, and **inventory management**.

---

## 📂 Dataset Description  

The dataset consists of **1,465 Amazon products** with the following details:
- Product category, subcategory, and full hierarchy  
- Price and discounted price  
- Customer ratings (average) and number of reviews  
- Comma-separated customer reviews and metadata  
- Total fields: 16 columns

---

## 🛠️ Tools Used  

- **Microsoft Excel**
  - Pivot Tables
  - Calculated Columns (e.g., Discount %, Price Buckets)
  - INDEX + MATCH and COUNTIF formulas  
  - Conditional Formatting
  - Charts: Column, Pie, Bar, Histogram, Scatter

---

## ✅ Analysis Conducted  

### 1. Average Discount Percentage by Category  
- Overall average: **46.7%**
- Highest discounts found in:
  - **Home Improvement** – 57.5%
  - **Computers & Accessories** – 53.2%
  - **Health & Personal Care** – 53%

### 2. Number of Products per Category  
- **Electronics**: 490  
- **Home & Kitchen**: 448  
- **Computers & Accessories**: 375  
- Other categories had 1–31 products each

### 3. Total Number of Reviews per Category  
- **Electronics**: 14.2M reviews  
- **Computers & Accessories**: 6.3M  
- **Home & Kitchen**: 2.99M  
- **Total**: Over 23.8M reviews across all products

### 4. Products with the Highest Average Ratings  
- Two products with **5.0 rating**:
  - **Syncwire LTG USB Cable**
  - **Amazon Basics Wireless Mouse**

### 5. Average Actual Price vs Discounted Price  
| Category               | Avg Actual Price | Avg Discounted Price |
|------------------------|------------------|------------------------|
| Electronics            | ₹10,153.29       | ₹6,225.87              |
| Home & Kitchen         | ₹4,162.07        | ₹2,330.61              |
| Computers & Accessories| ₹1,857.75        | ₹947.49                |

### 6. Products with the Highest Number of Reviews  
- Product in **Cables category**: **109,100 reviews**  
- Top 5 most-reviewed items were all under ₹500 and had discounts over 50%

### 7. Products with ≥ 50% Discount  
- Many products qualified, especially in:
  - **Accessories & Peripherals**
  - **Kitchen Appliances**
  - **Consumer Electronics**

### 8. Rating Distribution  
- 1,351 rated products  
- Most clustered around 4.0 – 4.5  
- Few perfect 5.0 ratings

### 9. Total Potential Revenue by Category  
- **Electronics**: ₹107.5M  
- **Home & Kitchen**: ₹79.4M  
- **Computers & Accessories**: ₹23M

### 10. Product Count Per Price Range  
| Price Bucket     | Count |
|------------------|--------|
| < ₹200           | 159    |
| ₹200 – ₹500      | 342    |
| > ₹500           | 850    |

### 11. Rating vs Discount  
- No direct correlation (visualized via scatter plot)  
- Some 5-star products had 80%+ discount

### 12. Products with Fewer than 1,000 Reviews  
- Filtered using `COUNTIF(<1000)`  
- Useful for identifying low-engagement or niche items

### 13. Categories with Highest Max Discount  
| Category               | Max Discount % |
|------------------------|----------------|
| Computers & Accessories| 94%            |
| Electronics            | 91%            |
| Home & Kitchen         | 90%            |
| Office Products        | 75%            |

### 14. Top 5 Products by Rating × Reviews Score  
- **Deep Fat Fryer**: ₹79.4M  
- **Instant Water Heater**: ₹107.5M  
- Others: USB Cable, Wireless Mouse, Hand Blender

---

## 💡 Key Insights  

- 🛍️ Electronics, Home & Kitchen, and Computer Accessories dominate in product volume and revenue.
- 🔝 Products with top ratings are mostly **affordable and heavily discounted**.
- 💬 Over 23 million reviews reflect **strong customer engagement** across select categories.
- 💸 Potential revenue is highly concentrated in **a few high-volume, high-rating products**.
- 📉 There is **no clear linear relationship** between discounts and product ratings.

---

## 📌 Recommendations  

1. **Invest in high-performing categories** like Electronics and Kitchen Appliances.
2. **Optimize pricing strategies** for products with high reviews but low ratings.
3. **Promote products with few reviews but high ratings** to boost visibility.
4. Use **rating × review volume** score to identify **high-potential products**.
5. **Bundle or cross-promote accessories** that show high discount effectiveness.

---

## 📎 Files in This Repository  

- `Amazon.xlsx` – Cleaned product and review dataset  
- `README.md` – Project overview and results summary  

---
