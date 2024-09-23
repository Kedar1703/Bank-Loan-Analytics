# Bank Loan Analytics Dashboard Project

## 📊 Project Overview

The **Bank Loan Analytics** project aims to provide comprehensive insights into the performance of loan applications, disbursements, and repayments through dynamic Power BI dashboards. By analyzing key metrics such as loan application trends, total funded amounts, average interest rates, and borrower profiles, this project helps financial institutions make data-driven decisions to improve loan operations and customer relationships.

The project includes three dashboards:

1. **Dashboard 1: Summary**
![Summary Dashboard](path_to_summary_dashboard_image.png)

2. **Dashboard 2: Overview**
![Overview Dashboard](path_to_overview_dashboard_image.png)

3. **Dashboard 3: Details**
![Details Dashboard](path_to_details_dashboard_image.png)

---

## 📝 Problem Statement

The main objective of this project is to monitor and analyze the performance of loan applications and disbursements across various dimensions such as loan terms, regional differences, borrower profiles, and loan purposes. The key insights are visualized using a range of Power BI charts and KPIs that help financial teams make informed decisions and optimize the loan portfolio.

---

## 💡 Key Performance Indicators (KPIs)

1. **Total Loan Applications**: Track the total number of loan applications and observe trends Month-to-Date (MTD) and Month-over-Month (MoM).
2. **Total Funded Amount**: Measure the total funds disbursed as loans and analyze MTD and MoM changes.
3. **Total Amount Received**: Understand the repayment patterns and cash inflow from borrowers.
4. **Average Interest Rate**: Calculate the average interest rate across loans and monitor trends.
5. **Average Debt-to-Income Ratio (DTI)**: Gauge the financial health of borrowers with the average DTI.
6. **Good Loan vs. Bad Loan Metrics**: Compare metrics such as application percentages, funded amounts, and amounts received for both good and bad loans.

---

## 🛠️ Dashboards

### **Dashboard 1: Summary**
This dashboard presents the key metrics in an aggregated view for a high-level understanding of the bank's lending performance:

- **Key KPIs**: Total Loan Applications, Funded Amount, Amount Received, Interest Rate, DTI.
- **Good Loan vs Bad Loan Comparisons**: Visualize application percentages, total funded amount, and repayment status.
- **Loan Status Grid View**: Provides a breakdown of loans by status, including the total number of applications, funded amount, and average DTI.

### **Dashboard 2: Overview**
A deep dive into specific dimensions to help understand the distribution and trends:

- **Monthly Trends (Line Chart)**: Track loan applications over time to identify seasonality or anomalies.
- **Regional Analysis (Filled Map)**: Visualize loan activity by state and uncover regional disparities.
- **Loan Term Analysis (Donut Chart)**: View how loans are distributed across various term lengths.
- **Employment Length (Bar Chart)**: Analyze how borrowers’ employment history influences loan application trends.
- **Loan Purpose Breakdown (Bar Chart)**: A visual breakdown of loan purposes.
- **Home Ownership (Tree Map)**: Explore how home ownership status affects loan disbursements.

### **Dashboard 3: Details**
A detailed view to access specific borrower and loan performance data:

- **Grid View**: Provides an extensive grid layout with all relevant metrics, including borrower profiles, loan performance, and other critical data points.

---
## 🔍 Key Findings
### **Dashboard 1: Key Findings**

- **Positive Loan Growth:** The total number of loan applications and the amount funded have seen a steady increase, indicating strong demand.
  
- **Good Loan Dominance:** Good loans represent **86.2%** of the total portfolio, suggesting a healthy lending process with lower risk.

- **Interest Rate and Risk Correlation:** Higher interest rates seem to be associated with bad loans, as seen with the **13.88%** rate for charged-off loans versus **11.64%** for fully paid loans. This indicates that riskier borrowers may be charged higher interest rates.

- **Improved Cash Flow:** The **Month-over-Month (MoM)** growth in total repayment is **15.84%**, showing positive signs of loan recovery and improved borrower repayment behavior.

- **DTI Insight:** The **Average Debt-to-Income (DTI) ratio** for the overall loan portfolio stands at **13.3%**, reflecting borrowers' ability to manage debt within their income levels.

### **Dashboard 2: Trends and Patterns**
- **Seasonality**: Loan applications exhibit seasonal variations, with peaks during specific times of the year.

- **State-Specific Demand**: Loan demand varies significantly across different states, highlighting regional preferences.

- **Loan Term Preferences**: The most favored loan term among borrowers is 36 months.

- **Employee Length & Loans**: Employees with longer tenures tend to apply for loans more frequently.

- **Loan Purpose Analysis**: The top reasons for loan applications include debt consolidation, credit card payments, and home improvement projects.

- **Home Ownership & Loans**: Individuals who hold mortgages are more likely to apply for additional loans.


## 📈 Visuals & Charts

1. **Line Chart**: Visualizes monthly trends in loan applications.
2. **Filled Map**: Displays regional analysis by state.
3. **Donut Chart**: Highlights the loan term distribution.
4. **Bar Charts**: Breaks down employment length and loan purpose.
5. **Tree Map**: Analyzes home ownership impact.

---

## 🧑‍💻 Technology Stack

- **Power BI**: Data visualization and dashboard creation
- **DAX (Data Analysis Expressions)**: Custom calculations and KPIs
- **SQL**: Data extraction and manipulation
- **Excel**: Data pre-processing and cleaning

---

## 🔑 Key Insights

- **Loan Application Trends**: Identified seasonal peaks and lows in loan applications, helping optimize marketing efforts.
- **Regional Disparities**: Detected high loan activity in specific regions, indicating market saturation and opportunities for expansion.
- **Impact of Employment History**: Employment length significantly affects loan approval rates.
- **Loan Purpose Analysis**: Certain loan purposes, such as housing and personal loans, dominate the portfolio, offering room for new product development.

---

## 🚀 How to Run the Project

1. Download the `.pbix` file from the [Power BI Dashboard File](https://github.com/Kedar1703/Bank-Loan-Analytics/tree/main/Power%20BI%20File).
2. Open the `.pbix` file using Power BI Desktop.
3. Connect to the necessary data sources (SQL/Excel).
4. Review the visualizations and interact with filters to explore different insights.

---

## 📸 Screenshots

| **Dashboard** | **Preview** |
|---------------|-------------|
| **Summary**   | ![Summary Dashboard](assets/summary.png) |
| **Overview**  | ![Overview Dashboard](assets/overview.png) |
| **Details**   | ![Details Dashboard](assets/details.png) |
