# **Sales Analysis Project**

## **Introduction**
This project analyzes sales data to uncover trends, profitability, and shipping efficiency across different product categories. Using Python, Pandas, and Matplotlib, the goal is to derive key insights that can help businesses optimize their sales strategies and maximize revenue.

---

## **Project Overview**
This project explores a sales dataset using Python and its analytical libraries, with Google Sheets as an auxiliary tool for data preparation. It serves as a demonstration of my proficiency in Python for data analysis, as well as my ability to think critically and derive actionable insights from data.

---

## **Dataset Description**
The dataset consists of key sales metrics, including:

- **Order Date & Ship Date** – To analyze shipping efficiency
- **Category & Sub-Category** – For performance evaluation of product categories and sub_categories
- **Sales & Profit** – To understand revenue generation and losses
- **Order Priority** – To assess Shipping speed and its impact on customer satisfaction
- **Customer & Region Details** – To analyze regional trends and customer preferences

The dataset is available in CSV format. Click [here](https://www.kaggle.com/datasets/laibaanwer/superstore-sales-dataset/data) to access it.

---

## **Objectives**
The main goals of this analysis are to:

- Analyze **sales trends** over the years
- Identify **best-selling products & categories**
- Measure **profitability & the impact of discounts**
- Evaluate **shipping efficiency based on order priority**
- Detect **patterns in yearly sales and profit**
- Assess **customer segments & regional sales performance**

---

## **Data Analysis Steps**

### **1. Ask (Defining the Problem)**
This stage involves defining Goals and understanding stakeholder expectations from the analysis.

### **2. Data Preparation**
Data preparation was done using Google Sheets, where:
- The **profit column** was split to separate **losses** from actual profits.
- A **shipping duration column** was created by subtracting **order date** from **ship date** to analyze efficiency.

### **3. Data Cleaning & Processing**
Using **Pandas** in Python, the dataset was imported into a Jupyter Notebook for cleaning:
- Checked for **data types, missing values, and duplicates**.
- Used `.info()`, `.shape`, and `.describe()` for initial exploration.
- Ensured **date columns** and **sales-related data types** were correct.
- Conducted **further transformations** during analysis based on key metrics.

### **4. Exploratory Data Analysis (EDA)**
The analysis focused on:
- **Sales & Profit Trends Over the Years**
- **Category and Sub_Category Performance Analysis**
- **Shipping Efficiency Evaluation**
- **Impact of Discounts on Profitability**
- **Regional and Customer Segment Insights**

---

## **Key Findings**

- **Sales Performance:**
  - Sales have **increased over the years**.

    <img src="Sales Trend over time.png" alt="Sales Trend" width="500">
    
  - The **Central region** had the **highest sales and profit**.
    
     <img src="Sales per region.png" alt="Sales Trend" width="500">
   
    
  - The **Consumer segment** had the Highest sales.
    
     <img src="Sales per segment.png" alt="Sales Trend" width="500">
 
 
- **Category Insights:**
  - **Technology leads** in both sales and profit.
  - 
     <img src="Sale per Category.png" alt="Sales Trend" width="500">
     
  - **Furniture, despite being the second-highest selling category, had the highest losses and the lowest profit**.
  - **Office Supplies, with the lowest sales, generates the second-highest profit and experiences the least loss**.

- **Product Performance:**
  - **Phones are the highest-selling sub-category** and are heavily discounted, causing potential losses. Fortunately, the Profit earned is higher than that of loss.
  - The **least sold product is also the least discounted**, which may indicate low demand due to pricing.
  - **Apple Smartphones are the best-selling product**, while **Disposable Bags have the lowest sales**.

- **Impact of Discounts on Profitability:**
  - **Sales with discounts greater than 50% is Observed to result in a loss**.
  - There is a strong **correlation between high discounts and Loss**.

- **Shipping Efficiency:**
  - **Order priority is well-managed**, ensuring shipping efficiency.
  - The time taken to ship products aligns with the order priority system.

---

## **Recommendations**

### **1. Optimize Discount Strategy**
- Since **Phones attract losses due to high discounts**, but for, the discount structure should be **reconsidered to balance profitability and demand**
- Least sold Product should be considered for **seasonal discount or promotions**.
- **Re-evaluate discount policies** to ensure they **do not negatively impact profit margins**.

### **2. Boost Sales for Low-Demand Products**
- **Low-selling sub-categories** like **Labels** could benefit from **targeted promotions**.
- **Seasonal discounts or marketing campaigns** could help improve demand.

### **3. Improve Shipping & Order Fulfillment**
- **Higher priority orders should be processed faster** to **maintain customer satisfaction**.
- Investigate and address **delays in the supply sector** to further improve shipping efficiency.

### **4. Focus on High-Profit Categories**
- Since **Technology yields the highest profit**, consider **expanding offerings in this category**.
- **Invest in marketing strategies** for high-margin products to maximize revenue. By doing this, We are taking Advantages of the positive

### **5. Improve Regional Sales Strategies**
- The **Central region leads in sales and profit**, suggesting that **other regions may need targeted campaigns Especially Canada**.
- Implement **regional promotions, localized marketing, or better distribution channels** to boost sales.

### **6. More Data Collection**
- It is advisable to implement a structured data collection method (e.g., surveys, customer feedback) to gather additional insights on customer satisfaction and ratings. This can help improve sales strategies and customer experience.

---

## **Conclusion**
This analysis provides key insights into **sales trends, profitability, discount strategies, and shipping efficiency**. By **adjusting discount structures, optimizing shipping logistics, and focusing on high-profit categories**, businesses can **maximize their revenue while maintaining efficiency**.

---

## **Tools Used**
- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Google Sheets**

---

## **Challenges Encountered**
- **Incomplete dataset**: The dataset would be more comprehensive with **Cost** and **Cost per Quantity** columns. These additional data points would allow for a more precise profit margin analysis.
- **High discount impact**: The dataset lacks details on promotional strategies, making it difficult to determine if high discounts are part of a pricing strategy or a reaction to low sales.
- **Limited customer insights**: More demographic data on customers would help refine purchasing behavior analysis.


---

Data Analyst: Felix Idowu.
