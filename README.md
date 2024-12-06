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
   <img width="600" alt="Screenshot 2024-12-06 at 8 14 48 PM" src="https://github.com/user-attachments/assets/4fc5d799-d6b4-4c9a-bd46-f4431596547f">

2. **Age Group vs. Sales**  
   <img width="609" alt="Screenshot 2024-12-06 at 8 15 20 PM" src="https://github.com/user-attachments/assets/bb915a4f-f6ad-4ea5-b5f5-b30adfe4f250">

3. **Top 10 States by Orders and Sales**  
   <img width="915" alt="Screenshot 2024-12-06 at 8 15 54 PM" src="https://github.com/user-attachments/assets/94114496-5261-4498-a42e-a5d520c649eb">

4. **Marital Status and Purchasing Power**  
   <img width="484" alt="Screenshot 2024-12-06 at 8 16 13 PM" src="https://github.com/user-attachments/assets/f242057e-64a9-4ba6-ada9-3369bc10cf02">

5. **Top Product Categories**  
  <img width="913" alt="Screenshot 2024-12-06 at 8 16 41 PM" src="https://github.com/user-attachments/assets/3cb99154-6f03-4f67-a277-ccade001b97b">

---


## Conclusion

- Married women (age group **26-35**) from **Uttar Pradesh**, **Maharashtra**, and **Karnataka**, working in **IT**, **healthcare**, or **aviation**, are the most likely to purchase.
- Top categories include **food**, **electronics**, **footwear**, and **clothing**.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diwali-sales-analysis.git
