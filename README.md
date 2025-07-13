# Black-Friday
**🛍️ Black Friday Sales Analysis**

This repository contains an Exploratory Data Analysis (EDA) of the Black Friday 
sales dataset. The project aims to uncover meaningful trends and customer behaviors using 
transaction-level retail data from a major Indian retail store.

**📌 Project Objective**

The goal of this project is to perform a detailed exploratory analysis of customer 
purchasing behavior during Black Friday sales. By understanding who buys what, when, and 
how much they spend, businesses can improve their marketing strategies and customer segmentation.

**📂 Dataset Information**
- File Name: train.csv
- Records: 550,068 transactions
- Features: 12 columns including user demographics, product information, and purchase amount.

**Key Columns:**

| Column Name                    | Description                         |
| ------------------------------ | ----------------------------------- |
| User\_ID                       | Unique identifier for each customer|
| Product\_ID                    | Unique identifier for each product  |
| Gender                         | Gender of the customer              |
| Age                            | Age group of the customer           |
| Occupation                     | Customer’s occupation code          |
| City\_Category                 | Category of city (A, B, or C)       |
| Stay\_In\_Current\_City\_Years | Duration of stay in current city    |
| Marital\_Status                | Marital status of the customer      |
| Product\_Category\_1           | Product category (mandatory)        |
| Product\_Category\_2           | Product category (optional)         |
| Product\_Category\_3           | Product category (optional)         |
| Purchase                       | Purchase amount in INR              |

**🛠 Tools & Technologies Used**
  - Language: Python
  - Libraries: pandas, numpy – data cleaning and manipulation
  - matplotlib, seaborn – data visualization
  - missingno – missing value analysis
  - plotly – interactive plots
-Platform: Jupyter Notebook / Google Colab

📊 **Exploratory Data Analysis Highlights**

🔍 **Data Cleaning**
 - Handled missing values in Product_Category_2 and Product_Category_3
 - Converted categorical columns into appropriate types
 - Verified uniqueness of IDs and value ranges

👥 **Demographic Analysis**
 - Most buyers are male and aged between 26-35 years
 - A majority of customers are from City Category B
 - Most customers have stayed in their current city for 1 year or more

💸 **Purchase Behavior**
 - Male customers tend to spend slightly more than female customers
 - Purchase value is highly concentrated between ₹5,000 and ₹15,000
 - Category 1 products are the most purchased, followed by Categories 2 and 3
  
🧾 **Product Trends**
 - Identified top-selling products and their popularity across age groups
 - Customers aged 26-35 are the most active buyers across all categories

📌 **Key Insights**
 - The 26–35 age group is the most active demographic during Black Friday.
 - City Category B is the largest contributor to sales.
 - Males dominate the customer base and purchasing power.
 - Most purchases are for Category 1 products, showing strong primary product interest.
 - Unmarried customers showed slightly higher engagement.

**📁 Repository Structure**

                 Black-Friday-Sales-EDA/
              │
              ├── train.csv                       # Dataset file
              ├── Black_Friday (1).ipynb          # Jupyter Notebook with EDA and visuals
              ├── README.md                      # Project documentation


🔮 Future Scope
 - Feature engineering for predictive modeling (e.g., customer lifetime value)
 - Create customer segments based on spending behavior
 - Develop a dashboard using Power BI or Tableau
 - Build machine learning models to predict purchase amounts

🚀 How to Run
1. Clone this repository:
2. Launch Jupyter Notebook or upload the .ipynb file to Google Colab.
3. Run all cells to explore the insights and visuals.




