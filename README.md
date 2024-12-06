# Diwali Sales Analysis

This project performs **Exploratory Data Analysis (EDA)** on a dataset containing Diwali sales data. The analysis aims to uncover trends, customer insights, and key business metrics to inform marketing strategies and business decisions.

---

## Project Overview

1. **Data Cleaning**:
   - Removed unnecessary columns: `Status`, `unnamed1`.
   - Handled missing values by removing rows with null `Amount` values.
   - Converted `Amount` column to integer data type.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed customer demographics, purchasing behavior, and sales patterns.
   - Key categories analyzed: Gender, Age Group, State, Marital Status, Occupation, and Product Categories.

3. **Tools Used**:
   - **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`.
   - Visualized insights using **Seaborn** and **Matplotlib**.

---

## Insights & Findings

### 1. Gender Analysis
- **Female customers** placed the highest number of orders and contributed the most to sales revenue.

### 2. Age Group Analysis
- The **26-35 age group** (mostly females) made the most purchases and spent the most.

### 3. State Analysis
- States with the highest sales and orders:
  - **Uttar Pradesh**
  - **Maharashtra**
  - **Karnataka**

### 4. Marital Status
- **Married women** are the primary buyers and have higher purchasing power.

### 5. Occupation
- Top buying sectors:
  - **IT**
  - **Healthcare**
  - **Aviation**

### 6. Product Categories
- Most sold product categories:
  - **Food**
  - **Clothing**
  - **Electronics**
  - **Footwear**

### 7. Product IDs
- Identified the top 10 most-ordered products.

---

## Visualizations

1. **Gender-Based Orders and Sales**  
   ![Gender Analysis](assets/gender_analysis.png)

2. **Age Group vs. Sales**  
   ![Age Group Analysis](assets/age_group_analysis.png)

3. **Top 10 States by Orders and Sales**  
   ![State Analysis](assets/state_analysis.png)

4. **Marital Status and Purchasing Power**  
   ![Marital Status Analysis](assets/marital_status_analysis.png)

5. **Top Product Categories**  
   ![Product Category Analysis](assets/product_category_analysis.png)

---

## Conclusion

- Married women (age group **26-35**) from **Uttar Pradesh**, **Maharashtra**, and **Karnataka**, working in **IT**, **healthcare**, or **aviation**, are the most likely to purchase.
- Top categories include **food**, **electronics**, **footwear**, and **clothing**.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diwali-sales-analysis.git
