# Customer Segmentation Using RFM Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-lightblue)

---

## 📌 Project Overview
This project demonstrates **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** model.  
By analyzing customer purchase behavior, businesses can identify key customer groups and tailor marketing strategies for improved engagement and revenue.

Dataset: **Online Retail Data**  
Language: **Python (Pandas, Matplotlib, Seaborn)**  

---

## ⚙️ Steps Performed
1. **Data Preprocessing**
   - Loaded `online_retail.csv`
   - Converted `InvoiceDate` to datetime
   - Removed missing `CustomerID`
   - Created `TotalAmount = Quantity × UnitPrice`

2. **RFM Calculation**
   - **Recency** = Days since last purchase  
   - **Frequency** = Number of unique invoices  
   - **Monetary** = Total spending  

3. **Scoring & Segmentation**
   - Assigned R, F, M scores on 1–5 scale  
   - Segmented customers into:
     - 🟢 Loyal Customers  
     - 🟡 Recent Buyers  
     - 🔵 Potential Loyalists  
     - 🔴 Lost Customers  
     - 🟠 Needs Attention  

4. **Visualization**
   - Bar chart: Customer count by segment  
   - Heatmap: Average RFM values  

5. **Outputs**
   - `RFM_Segmentation.csv` → Segmentation results  
   - `RFM_Summary_Report.txt` → Summary report  

---

## 🚀 Marketing Insights
- **Loyal Customers** → Reward loyalty with discounts & perks  
- **Recent Buyers** → Thank-you emails + recommendations  
- **Potential Loyalists** → Encourage repeat purchases  
- **Lost Customers** → Win-back campaigns  
- **Needs Attention** → Personalized offers  

---

## 🛠️ Technologies Used
- Python 3  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Repository Files
- `Customer Segmentation Using RFM Analysis.ipynb` → Main notebook  
- `RFM_Segmentation.csv` → Results  
---
🚀 How to Run
1.download file 

2.run on jupyter notebook

3.Don't forget to download given dataset extract it from zip
