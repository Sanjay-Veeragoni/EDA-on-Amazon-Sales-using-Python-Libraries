# EDA-on-Amazon-Sales-using-Python-Libraries


## 📊 **Project Summary & Insights**  

### ✅ **Steps Performed in This Project**  

1️⃣ **Loaded and Explored the Dataset**  
- Imported necessary libraries (`pandas`, `numpy`, etc.).  
- Read the dataset and checked the number of rows and columns.  
- Displayed the first and last 5 rows for an overview.  

2️⃣ **Performed Data Cleaning**  
- Identified missing values in key columns.  
- Checked for duplicates and handled them accordingly.  
- Converted `InvoiceDate` into **datetime** format for proper analysis.  

3️⃣ **Analyzed Sales by Country**  
- Counted the **number of invoices** per country to identify sales distribution.  
- **Finding:** All transactions in the dataset come from the **USA**, with **100,000 total transactions**.  

4️⃣ **Calculated Total Revenue**  
- Created a new column for **total revenue** using:  
  \[
  \text{Revenue} = \text{Quantity} \times \text{UnitPrice}
  \]  
- **Total Revenue Generated:** **$132,941,776.74** (from the USA).  

5️⃣ **Sorted Sales & Revenue by Country**  
- Grouped data by country to check which regions contribute the most revenue.  
- **Finding:** Since all sales come from **one country (USA)**, no direct comparisons were made.  

6️⃣ **Derived Business Insights**  
- The dataset represents **a high-revenue business**, with over **$132M in a single month**.  
- The **USA** is the sole market, meaning further regional/state-wise analysis could be useful.  
- Potential to analyze **customer spending habits** and **seasonal trends** for business optimization.  

---

🔹 **This project provides valuable insights into sales performance and revenue trends. Future work could involve**:  
- Expanding the dataset to include multiple countries for a **comparative analysis**.  
- Analyzing customer behavior for **segmentation and retention strategies**.  

🚀 **This analysis is crucial for understanding sales distribution and revenue generation in an e-commerce business!**  

