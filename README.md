# Customer Analysis for Grocery Chain

## 📌 Project Objective
The objective of this project is to analyze customer transaction data from a chain of grocery stores to uncover patterns in customer behavior, particularly focusing on loyalty engagement patterns across different age groups. The analysis aims to provide actionable insights for improving customer retention and optimizing marketing strategies.

## 📂 Dataset Overview
The dataset is sourced from `Grocery Database.xlsx`, which contains detailed transaction records from a chain of grocery stores. The dataset includes two sheets:
- **Grosto DB**: Contains the main transactional data with details about purchases.
- **Fact Summary**: Provides metadata describing the columns in the dataset.

The dataset includes the following key columns:
- **Receipt Number**: Unique transaction identifier
- **Date, Year, Month, Time**: Temporal details of the transaction
- **Mobile Number, Membership ID**: Customer identifiers
- **Loyalty Card Points**: Points earned by customers (10 points per unit of currency spent)
- **Age, Gender**: Demographic information of customers
- **City, Country**: Store location details
- **Category, Sub_Category, Items, Brand, Description**: Product details
- **Price, QTY, DISC**: Transaction details (price per unit, quantity, discount)

### 🔍 Key Steps Performed
1. **Data Loading and Exploration**:
   - Loaded the `Grocery Database.xlsx` file using pandas.
   - Inspected sheet names and parsed the `Fact Summary` sheet to understand column descriptions.
   - Displayed initial rows of the dataset to verify content.

2. **Data Analysis**:
   - Analyzed loyalty card points across different age groups to identify engagement patterns.
   - Calculated correlations to assess the relationship between age and loyalty behavior.

3. **Visualization** (assumed, based on common practice):
   - Used libraries like seaborn and matplotlib to visualize loyalty engagement trends (though not explicitly shown in the provided notebook snippet).

## 📊 Key Insights & Conclusions
- **Loyalty Engagement Patterns**:
  - Youngest customers (10-19) exhibit the highest loyalty card usage, averaging ~19.8 points.
  - Middle-aged customers (40-49) show the lowest engagement, averaging ~17.2 points.
  - Older customers (50-59) demonstrate a rebound in engagement with ~19.3 points.
  - Senior customers (60-79) maintain moderate but declining engagement (~16-16.7 points).
  - A weak overall correlation (-0.02) between age and loyalty points indicates that age alone is not a strong predictor of loyalty behavior.
- **Implications**:
  - Targeted marketing strategies could focus on boosting engagement among middle-aged customers.
  - The high engagement among younger and older age groups suggests effective loyalty programs for these segments, which could be studied for replication.

### 📊 Tools & Libraries
- **Python**: Core programming language for data analysis.
- **Pandas**: For data loading, manipulation, and analysis.
- **Seaborn**: For statistical data visualization.
- **Matplotlib**: For creating plots and visualizations.
- **NumPy**: For numerical computations.
- **Jupyter Notebook**: For interactive analysis and documentation.
- **ExcelFile (pandas)**: For reading and parsing Excel files.

## 📁 Repository Structure
```
customer_analysis_grocery_chain/
│
├── customer_analysis_grocery_chain.ipynb  # Jupyter notebook with the analysis
├── Grocery Database.xlsx                  # Source dataset (not included in repo, referenced)
├── README.md                             # Project documentation
```

