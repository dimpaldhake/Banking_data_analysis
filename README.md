# 🏦 Banking Customer Analytics Dashboard

## 📌 Project Overview

The **Banking Customer Analytics Dashboard** is a data analytics project designed to explore banking customer information, analyze financial activities, and present meaningful insights through interactive Power BI dashboards.

The project uses Python for Exploratory Data Analysis (EDA) and Power BI for interactive data visualization. It focuses on customer demographics, loan distribution, deposits, account balances, income groups, and banking relationships.

The objective is to transform raw banking data into meaningful visual insights that can support better business understanding and data-driven decision-making.

## 🎯 Project Objectives

* Analyze banking customer demographics and financial information.
* Explore customer income and loyalty classifications.
* Understand loan and deposit distribution.
* Analyze banking activities across different occupations and nationalities.
* Identify patterns in customer financial behavior.
* Build interactive dashboards for effective data visualization.

## 🛠️ Technologies & Tools

| Technology       | Purpose                           |
| ---------------- | --------------------------------- |
| Python           | Data analysis                     |
| Pandas           | Data manipulation and cleaning    |
| NumPy            | Numerical operations              |
| Matplotlib       | Data visualization                |
| Seaborn          | Statistical visualization         |
| Jupyter Notebook | Exploratory Data Analysis         |
| Power BI         | Interactive dashboard development |
| CSV              | Dataset storage                   |

## 📂 Project Structure

```text
Banking-Customer-Analytics/
│
├── Banking.csv
│
├── Banking_EDA.ipynb
│
├── Banking Dashboard (2025).pbix
│
└── README.md
```

## 📊 Dataset Description

The dataset contains **3,000 banking customer records** with 25 columns covering customer demographics, financial information, and banking relationships.

### Key Features

**Customer Information**

* Client ID
* Name
* Age
* Gender ID
* Nationality
* Occupation
* Location ID

**Banking Information**

* Joined Bank
* Banking Contact
* Fee Structure
* Loyalty Classification

**Financial Information**

* Estimated Income
* Superannuation Savings
* Credit Card Balance
* Bank Loans
* Bank Deposits
* Checking Accounts
* Saving Accounts
* Foreign Currency Account
* Business Lending

**Additional Information**

* Amount of Credit Cards
* Properties Owned
* Risk Weighting

## 🔍 Exploratory Data Analysis (EDA)

Performed exploratory data analysis using Python to understand the dataset and identify patterns.

### Analysis Performed

1. **Data Understanding**

   * Examined dataset dimensions.
   * Checked column information and data types.
   * Generated descriptive statistics.

2. **Income Classification**

   * Created income categories using estimated income.
   * Classified customers into Low, Medium, and High income bands.

3. **Categorical Analysis**

   * Analyzed nationality.
   * Examined occupation.
   * Explored fee structures.
   * Analyzed loyalty classifications.
   * Examined risk weighting and customer categories.

4. **Numerical Analysis**

   * Analyzed estimated income.
   * Examined superannuation savings.
   * Explored credit card balances.
   * Analyzed bank loans and account balances.

5. **Correlation Analysis**

   * Created a correlation matrix.
   * Used heatmaps to visualize relationships between numerical variables.

## 📈 Power BI Dashboard

Developed an interactive Banking Dashboard with multiple analytical sections.

### 1. Home Dashboard

Provides an overview of banking customer and financial metrics.

Includes:

* Total Clients
* Total Loans
* Total Deposits
* Checking Accounts
* Savings Accounts
* Business Lending

### 2. Loan Analysis

Focuses on understanding loan distribution across different customer segments.

Includes:

* Total Loan
* Bank Loan
* Business Lending
* Credit Card Balance
* Bank Loans by Banking Relationship
* Bank Loans by Occupation
* Bank Loans by Income Band
* Bank Loans by Nationality

### 3. Deposit Analysis

Provides insights into customer deposits and account balances.

Includes:

* Total Deposits
* Bank Deposits
* Savings Account Amount
* Checking Account Amount
* Bank Deposits by Banking Relationship
* Bank Deposits by Occupation
* Bank Deposits by Income Band
* Bank Deposits by Nationality

### 4. Summary Dashboard

Provides an overview of customer and financial information.

## 💡 Key Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Manipulation
* Data Cleaning and Understanding
* Statistical Analysis
* Data Visualization
* Customer Segmentation
* Financial Data Analysis
* Dashboard Development
* Business Intelligence

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Run the Python Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open `Banking_EDA.ipynb` and execute the cells.

Make sure `Banking.csv` is available in the same directory.

### Step 4: Open Power BI Dashboard

1. Install Microsoft Power BI Desktop.
2. Open `Banking Dashboard (2025).pbix`.
3. Refresh the dataset if required.
4. Explore the dashboard pages and available interactions.

## 👩‍💻 Author

**Dimpal Dhake**

Aspiring Python Full Stack Developer | Data Analytics Enthusiast

[LinkedIn](https://www.linkedin.com/in/dimpal-dhake/)

---

⭐ If you find this project interesting, feel free to explore the repository!
