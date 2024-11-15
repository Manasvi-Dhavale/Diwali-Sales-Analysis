# Diwali Sales Analysis

![image](https://github.com/user-attachments/assets/911b26f1-4d36-471e-86d1-a584b378211c)

![Screenshot 2023-10-31 213427](https://github.com/user-attachments/assets/a77bfc2f-733e-451a-8119-68ae2dcfa9ab)

![Screenshot 2023-11-06 114341](https://github.com/user-attachments/assets/09aaa166-74a3-472a-acd3-2e756c8c1d0f)



## Project Overview
This project conducts an **exploratory data analysis (EDA)** on a dataset representing Diwali sales to uncover purchasing patterns, trends, and insights. By leveraging Python libraries such as `Pandas`, `NumPy`, `Matplotlib`, and `Seaborn`, the analysis visualizes and interprets sales data effectively.

## Key Concepts and Functionalities

### 1. Data Preparation and Cleaning
- **Loading Data**: The dataset is loaded using `pandas.read_csv()` with appropriate encoding to handle special characters.
- **Data Cleaning**:
  - Removed unrelated/blank columns (`Status`, `Unnamed: 1`).
  - Handled missing values using `dropna()` to ensure data integrity.
  - Converted data types for numerical analysis (e.g., `Amount` column cast to `int`).

### 2. Data Exploration and Descriptive Statistics
- **Basic Information**:
  - Displayed data shape, column details, and types using `df.info()` and `df.head()`.
- **Descriptive Analysis**:
  - Used `df.describe()` to provide a statistical summary of relevant columns.
- **Renamed Columns**:
  - Columns were renamed for better readability (e.g., `Marital_Status` to `Shaadi`).

### 3. Data Visualization
- **Gender Analysis**:
  - Plotted gender counts and total sales by gender using `sns.countplot()` and `sns.barplot()`.
  - Conclusion: Females had higher purchasing power.
- **Age Group Analysis**:
  - Visualized total sales by age group.
  - Insight: Majority of buyers were in the 26-35 age range.
- **State-wise Analysis**:
  - Plotted total orders and total sales from top states.
  - Result: Uttar Pradesh, Maharashtra, and Karnataka showed the highest sales.
- **Marital Status Analysis**:
  - Count and sales distribution by marital status and gender.
  - Observation: Married women had the highest purchasing power.
- **Occupation Analysis**:
  - Bar charts showing order counts and total sales for different occupations.
  - Insight: High sales from IT, Healthcare, and Aviation sectors.
- **Product Category Analysis**:
  - Identified top-selling product categories and specific product IDs with the highest orders.
  - Result: Food, Clothing, and Electronics were the most popular categories.

### 4. Key Findings
- **Demographics**:
  - Majority of buyers were married women aged 26-35 from states like Uttar Pradesh, Maharashtra, and Karnataka.
- **Occupation**:
  - High sales were observed among individuals working in IT, Healthcare, and Aviation.
- **Products**:
  - Food, Clothing, and Electronics were the most purchased categories.

## Conclusion
The analysis provides valuable insights into consumer behavior during the Diwali season. The findings can guide targeted marketing strategies and inventory management.

## Technologies Used
- **Python**: Data manipulation and visualization
- **Libraries**:
  - `pandas` for data processing
  - `numpy` for numerical operations
  - `matplotlib` and `seaborn` for data visualization

