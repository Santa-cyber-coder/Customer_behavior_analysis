📊 Customer Behavior Analysis

An end-to-end Data Analytics project that analyzes customer shopping behavior using Python, PostgreSQL, and Power BI. This project demonstrates the complete analytics workflow—from data cleaning and exploratory data analysis (EDA) to SQL-based business analysis and interactive dashboard development.



📌 Overview

The objective of this project is to analyze customer shopping behavior and uncover meaningful business insights from transactional data. The workflow includes data preprocessing, exploratory data analysis, SQL querying, dashboard creation, and reporting to support data-driven decision-making.



📂 Dataset

* Dataset Name: Customer Shopping Behavior
* Source: GitHub
* Format: CSV
* Records: 3,900 customer transactions
* Features: 18 columns

The dataset contains information about customer demographics, purchase history, product categories, shopping preferences, subscription status, discounts, shipping methods, and customer reviews.


🛠️ Tools & Technologies

Python

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
* PostgreSQL
* Power BI
* Gamma (Presentation)
* Jupyter Notebook

🚀 Project Workflow

1. Data Loading

* Imported the dataset using Pandas.
* Inspected the dataset structure and summary statistics.

2. Exploratory Data Analysis (EDA)

* Analyzed data distributions and relationships.
* Identified missing values and inconsistencies.
* Explored customer demographics and purchasing patterns using visualizations.

3. Data Cleaning

* Handled missing values in the **Review Rating** column.
* Renamed columns using snake_case naming conventions.
* Created new features such as:
 * Age Group
 * Purchase Frequency (Days)
* Removed redundant columns after consistency checks.

4. SQL Analysis (PostgreSQL)

Imported the cleaned dataset into PostgreSQL and answered key business questions using SQL, including:

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Comparison
* Subscribers vs Non-Subscribers
* Discount-Dependent Products
* Customer Segmentation
* Top Products by Category
* Repeat Buyers & Subscription Analysis
* Revenue by Age Group

5. Power BI Dashboard

Designed an interactive dashboard to visualize customer behavior and business performance using various charts, KPIs, and filters.

6. Reporting

* Prepared a detailed project report summarizing methodology and findings.
* Created a professional presentation using Gamma.


📊 Dashboard

The Power BI dashboard provides interactive insights into customer shopping behavior through:

* KPI Cards
* Sales & Revenue Analysis
* Customer Demographics
* Product Category Performance
* Subscription Analysis
* Shipping Method Comparison
* Age Group Analysis
* Interactive Filters and Slicers

📈 Results

This project successfully:

* Cleaned and transformed raw customer transaction data.
* Performed comprehensive exploratory data analysis.
* Extracted business insights using PostgreSQL.
* Developed an interactive Power BI dashboard.
* Generated a detailed report and presentation to communicate findings effectively.

Key recommendations include:

* Promote subscription programs to improve customer retention.
* Reward repeat customers through loyalty programs.
* Optimize discount strategies to balance sales and profitability.
* Highlight top-rated products in marketing campaigns.
* Focus marketing efforts on high-value customer segments.

📁 Project Structure


Customer-Behavior-Analysis/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── cleaned_customer_data.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── reports/
│   ├── Customer_Shopping_Behavior_Report.pdf
│   └── Customer_Behavior_Presentation.pdf
│
└── README.md




▶️ How to Run

1. Clone this repository.
git clone https://github.com/your-username/customer-behavior-analysis.git

2. Install the required Python libraries.
pip install pandas numpy matplotlib seaborn psycopg2

3. Open the Jupyter Notebook and execute all cells.

4. Load the cleaned dataset into PostgreSQL.

5. Run the SQL queries in the `sql` folder.

6. Open the Power BI (`.pbix`) dashboard to explore the interactive visualizations.

7. Refer to the report and presentation for detailed insights and business recommendations.

💡 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* PostgreSQL Querying
* Business Data Analysis
* Power BI Dashboard Development
* Data Visualization
* Business Intelligence
* Report Writing
* Data Storytelling


👨‍💻 Author

Santhiya S

Feel free to connect and provide feedback on this project.
