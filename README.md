# Telco Customer Churn Analysis Dashboard

![Telco Churn Dashboard](screenshots/telco_churn_dashboard_screenshot.png)

## 📋 Project Overview

This project focuses on analyzing customer churn for a telecommunications company using Power BI. The goal is to identify key factors influencing customer churn and visualize the insights through an interactive dashboard. The dataset (`telco_cleaned_for_viz`) contains customer information such as contract type, monthly charges, tenure, internet service type, payment method, and churn status.

The project follows a structured approach:

- **Data Cleaning and Preprocessing**: Using Python (Jupyter Notebook) to clean and preprocess the raw data.
- **Exploratory Data Analysis (EDA)**: Analyzing patterns and correlations in the data.
- **Feature Engineering**: Creating new features like `InternetService_Type` and `PaymentMethod_Type` using DAX in Power BI.
- **Visualization**: Building an interactive dashboard in Power BI to present insights.
- **Reporting**: Summarizing findings in a report with actionable recommendations.

## 📊 Dashboard Features

The Power BI dashboard (`telco_churn_dashboard.pbix`) includes the following visualizations:

- **Overall Churn Rate**: Displays the overall churn rate (26.54%).
- **Churn Count by Contract Type**: A stacked column chart showing the total number of churned customers by contract type (Month-to-month, One year, Two year).
- **Monthly Charges Distribution by Churn**: A histogram showing the distribution of monthly charges for churned and non-churned customers.
- **Tenure Distribution by Churn**: A histogram showing the distribution of tenure (in months) for churned and non-churned customers.
- **Churn Count by Internet Service Type**: A pie chart showing the number of churned customers by internet service type (Fiber optic, DSL, No Internet).
- **Churn Count by Payment Method**: A stacked column chart showing the number of churned customers by payment method (Electronic check, Credit card, Mailed check, Bank transfer).
- **Filters (Slicers)**: Interactive filters for `contract_type` and `InternetService_Type` to dynamically explore the data.

## 📈 Key Insights

- **Overall Churn Rate**: 26.54% of customers have churned.
- **Contract Type**: Customers with a "Month-to-month" contract have the highest churn count, while those with a "Two year" contract have the lowest.
- **Monthly Charges**: Churned customers tend to have higher monthly charges, with a noticeable peak around $70-$100.
- **Tenure**: Customers with shorter tenure (less than 10 months) are more likely to churn.
- **Internet Service Type**: Customers using "Fiber optic" have a higher churn count compared to "DSL" or "No Internet".
- **Payment Method**: Customers paying via "Electronic check" have the highest churn count, while those using "Bank transfer (automatic)" have the lowest.

## 🛠️ Tools and Technologies

- **Power BI**: For creating the interactive dashboard (`telco_churn_dashboard.pbix`).
- **Python**: For data cleaning and preprocessing (Jupyter Notebook).
- **DAX**: For feature engineering in Power BI (e.g., `InternetService_Type`, `PaymentMethod_Type`).
- **Power Query**: For data transformation and binning (e.g., monthly charges and tenure histograms).

## 📂 Project Structure
telco-churn-analysis/
│
├── data/
│   └── telco_cleaned_for_viz.csv    # Cleaned dataset used for visualization
│
├── notebooks/
│   └── telco_data_cleaning.ipynb    # Jupyter Notebook for data cleaning and EDA
│
├── dashboard/
│   └── telco_churn_dashboard.pbix   # Power BI dashboard file
│
├── report/
│   ├── telco_churn_dashboard.pdf    # Exported PDF of the dashboard
│   └── telco_churn_report.docx      # Summary report with insights
│
├── screenshots/
│   └── telco_churn_dashboard_screenshot.png  # Screenshot of the dashboard
│
└── README.md                        # Project documentation
📧 Contact
For questions or feedback, feel free to reach out:

GitHub: KoreanBeaver
Email: [timeless0119@gmail.com]