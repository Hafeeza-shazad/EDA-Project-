# ECOMMERCE PURCHASE ANALYSIS - EDA PROJECT

##  Project Overview
This project is an Exploratory Data Analysis (EDA) of a dataset containing customer purchase information. The goal is to uncover insights into **purchase behavior, spending patterns, and trends** based on different attributes such as job title, email provider, and time of purchase.

## 📂 Dataset Details
The dataset contains the following key columns:
- `Purchase Price` – Amount spent on a transaction.
- `AM or PM` – Time of purchase.
- `Job` – Customer's profession.
- `E-provider` – Email domain of the customer.
- `CC Exp Date` – Credit card expiration date.
- `CC Provider` – Credit card type (Visa, Mastercard, etc.).

##  Key Insights from EDA
###  Spending Analysis
- The **maximum purchase price** is `$99.99`, while the **minimum is $0.00`.
- The average spending varies significantly across different **job titles**.

###  Purchase Timing
- **AM Purchases:** `4932`
- **PM Purchases:** `5068`
- Slightly more purchases occur at **night (PM).**
- A pie chart was used to visualize the **AM vs. PM purchases**, showing the distribution clearly.

###  Job Title Analysis
- The **top 10 most common job titles** among customers were identified.
- A bar chart was used to illustrate the distribution, with a color gradient indicating the most common to least common jobs.

###  Email Provider Analysis
- The top 5 email domains used by customers:
  - `hotmail.com` - 1638 users
  - `yahoo.com` - 1616 users
  - `gmail.com` - 1605 users
- A bar chart was used to visualize the most common **email providers among customers**.

## 📌 Technologies Used
- **Python** 
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization
- Jupyter Notebook for analysis
