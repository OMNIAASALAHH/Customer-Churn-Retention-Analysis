# Customer Churn Retention Analysis

## Project Overview
This project aims to analyze customer churn rates and associated risks, using data visualization and insights derived from a well-structured Power BI dashboard. The analysis includes key performance indicators (KPIs) related to customer behavior, contract types, payment methods, and service usage. The goal is to identify trends, highlight churn risk factors, and provide actionable insights for decision-making.

---

## Dashboard Pages and Key Metrics

### 1. Customer Churn Retention Dashboard
This page provides a high-level summary of customer churn and its financial impact.

#### Key Metrics and KPIs:
- **Overall Customers**: 7,043
- **Churn Customers**: 1,869
- **Churn Rate**: 26.5%
- **Total Revenue per Year**: $5.47M
- **Lost Revenue per Year**: $1.67M
- **Cumulative Charges**: $16M

#### Insights:
- **Payment Method**:
  - Highest churn is observed with **Electronic Check (34%)**.
  - Other methods like **Mailed Check, Bank Transfer (Auto), and Credit Card (Auto)** exhibit churn rates of ~22-23%.
- **Contract Type**:
  - **Month-to-Month Contracts** have the highest churn rate (**55.02%**).
  - Longer contracts (e.g., 2 years) exhibit significantly lower churn rates (**~20%**).
- **Subscription Time**:
  - Shorter tenure customers (e.g., **1 year**) show higher churn rates.

---

### 2. Customer Risk Dashboard
This page focuses on churn risk factors, providing a detailed breakdown by contract type, tenure, payment method, and billing preferences.

#### Key Metrics and KPIs:
1. **Churn by Contract Type**:
   - Highest churn is among **Month-to-Month Contracts**.
2. **Churn by Tenure**:
   - Customers with shorter tenure (e.g., **1 year**) show the highest churn rate.
3. **Churn by Payment Method**:
   - **Electronic Checks** have the highest churn count.
4. **Paperless Billing Risk**:
   - Customers using **Paperless Billing** exhibit a higher churn risk.

#### Visualized Trends:
- **Contracts and Tenure**:
  - Clear correlation between shorter contracts or tenures and increased churn.
- **Billing Methods**:
  - Paperless billing correlates with higher churn risk, while mailed checks show lower churn.

---

### 3. Service Performance Dashboard
This page evaluates churn in the context of service usage, such as internet services, streaming, and technical support.

#### Key Metrics and KPIs:
1. **Churn Rate (Fiber Optic)**: 42%
2. **Internet Adoption**: 78%
3. **Internet Service Churn Rate**: 32%
4. **Tickets by Type**:
   - **Admin Tickets**: 3,632
   - **Tech Tickets**: 2,955

#### Service-Specific Observations:
- **Streaming Services**:
  - Higher churn rates are linked to customers using streaming TV and movies.
- **Online Security and Tech Support**:
  - Customers lacking these services are more likely to churn.
- **Device Protection**:
  - Customers without device protection services also show elevated churn rates.

---

## Tools and Techniques
- **Data Visualization**: Power BI
- **Data Modeling**: DAX (Data Analysis Expressions)
- **KPI Calculation**: Focused on churn rates, financial impact, and service utilization.
- **Trend Analysis**: Identifying risk factors and high-churn customer segments.

---

## Key Insights for Resume
- Designed an interactive dashboard using **Power BI** to analyze customer churn and risks.
- Highlighted critical KPIs, such as **churn rate, revenue loss, and service usage trends**, to provide actionable insights.
- Leveraged **DAX** for custom measures and calculations, including tenure risk and churn by contract type.
- Developed data-driven solutions for churn reduction and customer retention strategies.

---

## How to Use the Dashboard
1. **Filters**:
   - Navigate using slicers to filter by contract type, payment method, and other dimensions.
2. **Drill-through Analysis**:
   - Click on charts and visuals to explore detailed insights.
3. **Key Visuals**:
   - Monitor churn trends, service performance, and risk factors through interactive visuals.

---

## Conclusion
This dashboard provides a comprehensive analysis of customer churn and risk factors, empowering stakeholders to make informed decisions to reduce churn and improve customer satisfaction.

