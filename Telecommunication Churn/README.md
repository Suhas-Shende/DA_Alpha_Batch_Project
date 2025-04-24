# Telecom Churn Analysis

This project focuses on analyzing customer churn in a telecom dataset. The goal is to clean and analyze the data to extract meaningful insights and build visualizations to understand customer behavior and churn patterns. The project involves data cleaning, exploratory data analysis (EDA), and the creation of an interactive dashboard using Streamlit for visualization.

## Project Overview

Customer churn is a critical metric for telecom companies, as retaining customers is more cost-effective than acquiring new ones. This analysis aims to identify factors contributing to churn and provide insights into customer retention strategies.

## 🔍 Objective

The primary goal is to understand **why customers are leaving (churning)** and help the company **retain more customers** by analyzing usage patterns, service preferences, and demographics. Insights derived can be used to:

- Predict customers at risk of churning.
- Develop targeted retention campaigns.
- Improve service offerings based on customer preferences.

## Dataset

The dataset used for this project contains information about telecom customers, including their demographics, services, and usage patterns. The columns in the dataset are:

- **customerID** (object): Unique identifier for each customer.
- **gender** (object): Gender of the customer.
- **SeniorCitizen** (object): Whether the customer is a senior citizen (1 or 0).
- **Period** (float64): Length of time the customer has been with the company.
- **PhoneService** (object): Whether the customer has phone service (Yes or No).
- **InternetService** (object): Type of internet service (DSL, Fiber optic, or No).
- **OnlineBackup** (object): Whether the customer has an online backup service (Yes or No).
- **DeviceProtection** (object): Whether the customer has device protection service (Yes or No).
- **TechSupport** (object): Whether the customer has tech support (Yes or No).
- **StreamingTV** (object): Whether the customer has streaming TV service (Yes or No).
- **Contract** (object): Type of contract (Month-to-month, One year, Two year).
- **PaymentMethod** (object): Payment method used by the customer.
- **MonthlyCharges** (float64): Monthly charges for the customer.
- **Churn** (object): Whether the customer has churned (Yes or No).
- **ChargeBin** (category): Binned monthly charges (Low, Medium, High).
- **RoundedCharges** (float64): Rounded monthly charges.


## 📚 Libraries Used

The following Python libraries were used in the project:

### 🔧 Data Handling & Manipulation
- **pandas**: For data loading, manipulation, and analysis.
- **numpy**: For numerical operations and handling missing data.

### 📊 Visualization
- **matplotlib**: For creating static, animated, and interactive visualizations.
- **seaborn**: For enhanced statistical data visualization.

<!-- ## Project Tasks

The tasks are divided among the team members as follows:

- **Rutuja**: Data Cleaning, Count by Churn, Churn by Gender.
- **Suhas**: Churn by Senior Citizen, Period, PhoneService to StreamingTV.
- **Kewal**: Contract, Monthly Charges.
- **Chirag**: Payment Method. -->

## Data Cleaning

The following data cleaning steps were performed:

- Handled missing values.
- Removed irrelevant columns.
- Ensured data integrity.

## Exploratory Data Analysis (EDA)

In this phase, the following analyses were conducted:

- Churn distribution and its correlation with different customer features.
- Gender-based churn analysis.
- Churn analysis based on customer tenure (Period).
- Service usage analysis (Phone Service, Internet Service, etc.).
- Churn distribution based on contract type and payment methods.


## 📊 Key Analyses & Insights

- **Churn vs Contract Type**: Customers on month-to-month contracts are more likely to churn.
- **Churn vs Monthly Charges**: Higher charges are associated with increased churn.
- **Churn vs Senior Citizens**: Senior citizens show slightly higher churn rates.
- **Gender**: No significant correlation with churn, but still analyzed for completeness.
- **Services**: Customers lacking additional services (e.g., TechSupport, Backup) tend to churn more.
- **There are more insights find it**



<!-- ## Streamlit Dashboard

A Streamlit dashboard was created to visualize insights from the data. Key features of the dashboard include:

- **Gender Filter**: A sidebar option to filter churn data by gender.
- **Churn Statistics**: Display total counts, churned counts, and their percentages.
- **Visualizations**: Graphs showing churn distribution, gender-based churn, service usage, and more.

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/telecom-churn-analysis.git
   cd telecom-churn-analysis -->
