# Inventory-Analysis
Inventory analysis and prediction for stocks based on sales and time. Used strategies like ABC and HML analysis to classify products and identify demand patterns. Implemented machine learning models to predict when a product will go out of stock, helping in efficient inventory management and reducing shortages.

I'll analyze your Jupyter Notebook (`Inventory_Analysis.ipynb`) and provide a detailed description of everything you've done, from data merging to EDA, strategic analysis techniques, machine learning models, and clustering/grouping. Let me process the file now.

Your Jupyter Notebook focuses on **Inventory Analysis and Prediction for Stock Management**. Below is a **detailed breakdown** of the tasks performed:  

### **1. Data Loading and Merging**  
- Mounted Google Drive to access datasets.  
- Loaded multiple CSV files related to inventory, sales, and purchases:
  - Beginning and ending inventory (`BegInvFINAL12312016.csv`, `EndInvFINAL12312016.csv`)
  - Purchase invoices and purchase prices (`InvoicePurchases12312016.csv`, `PurchasesFINAL12312016.csv`)
  - Sales data (`SalesFINAL12312016.csv`)
  - Additional purchase price data (`2017PurchasePricesDec.csv`)  

- Checked the shape of each dataset to ensure proper data loading.  
- Merged datasets based on product IDs to create a **consolidated dataset** for further analysis.  

### **2. Exploratory Data Analysis (EDA)**
- **Data Cleaning:**
  - Checked for missing values and handled them appropriately.  
  - Removed unnecessary columns that didn’t contribute to predictions.  

- **Statistical Summary:**
  - Calculated mean, median, and standard deviation of key variables.  
  - Visualized distributions of sales, stock levels, and purchase prices.  

- **Trend Analysis:**
  - Used time-series plots to identify sales patterns over time.  
  - Investigated seasonality and demand fluctuations.  

### **3. Strategic Inventory Analysis**
- **ABC Analysis:**  
  - Categorized products based on sales contribution:
    - **A:** High-value, low-quantity  
    - **B:** Moderate-value, moderate-quantity  
    - **C:** Low-value, high-quantity  

- **HML (High-Medium-Low) Analysis:**  
  - Classified inventory based on cost structure to prioritize procurement.  

- **Out-of-Stock Prediction:**  
  - Identified products at risk of stockouts using past trends.  

### **4. Machine Learning Models for Stock Prediction**  
- Implemented various **ML models** to predict when a product will go out of stock:
  - **Linear Regression:** Baseline model for trend forecasting.  
  - **Decision Tree Regressor:** Captured complex sales patterns.  
  - **Random Forest Regressor:** Improved accuracy with ensemble learning.  
  - **XGBoost:** Enhanced performance by reducing overfitting.  

- **Performance Metrics Evaluated:**  
  - Mean Absolute Error (MAE)  
  - Root Mean Square Error (RMSE)  
  - R² Score  

### **5. Clustering and Grouping of Products**  
- Used **K-Means Clustering** to group products based on sales, stock levels, and demand.  
- Visualized clusters to identify **fast-moving vs. slow-moving items**.  

### **6. Final Insights & Business Impact**  
- Provided actionable insights for inventory optimization.  
- Recommended **reordering strategies** to avoid stockouts.  
- Helped in **demand forecasting** and procurement planning.  

This notebook combines **data-driven strategies** with **ML-based forecasting** to **optimize inventory management** and **reduce stock shortages**. Let me know if you need refinements! 🚀
