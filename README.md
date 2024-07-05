# Customer Retention Analysis Dashboard

## Project Overview

This Power BI project aims to analyze customer churn and retention, providing actionable insights to help improve customer retention strategies. The analysis focuses on various factors such as demographics, tenure, service usage, and billing to identify key areas that influence customer churn.

## Dataset

The dataset used for this project includes the following columns:
- customerID
- gender
- SeniorCitizen
- Partner
- Dependents
- tenure
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies
- Contract
- PaperlessBilling
- PaymentMethod
- MonthlyCharges
- TotalCharges
- numAdminTickets
- numTechTickets
- Churn

## Project Details

### Churn Analysis by Internet Service
- **Device Protection Impact:** Customers without device protection have a higher churn rate (26.75%) compared to those with device protection (7.74%).
- **Internet Service Impact:** Customers without internet service have the lowest churn rate (1.60%).

### Churn Percentage by Demographics
- **Senior Citizens:** Senior citizens have a lower churn rate (7.67%) compared to non-senior citizens (19.78%).
- **Customer Base:** The majority of the customer base consists of non-senior citizens (64.01%).

### Churn Analysis by Tenure
- **Shorter Tenure:** The churn rate is highest for customers with a shorter tenure and decreases as tenure increases.
- **Long-Term Customers:** There is a significant drop in churn rate after the initial few months, indicating that long-term customers are less likely to churn.

### Churn Analysis by Monthly Charges
- **Higher Monthly Charges:** Customers with higher monthly charges (around $70-$100) exhibit a higher churn rate.
- **Lower Monthly Charges:** Lower monthly charges correlate with a lower churn rate, suggesting price sensitivity among customers.

### Churn Analysis by Total Charges
- **Lower Total Charges:** The churn rate is higher for customers with lower total charges, indicating that newer customers are more likely to churn.
- **Higher Total Charges:** As total charges increase, the churn rate decreases, reinforcing the idea that long-term customers tend to stay.

## Key Insights

The dashboard provides several key insights for improving customer retention:
- **Device Protection:** Promoting device protection plans could help reduce churn rates.
- **Demographic Targeting:** Tailoring retention strategies for different demographic groups, especially non-senior citizens.
- **Tenure-Based Strategies:** Focusing on retaining new customers in their initial months to decrease churn.
- **Pricing Strategies:** Reviewing pricing models to ensure they align with customer expectations, particularly for those with higher monthly charges.

## Conclusion

This Power BI dashboard offers a detailed view of customer churn, identifying key factors and providing actionable insights to help reduce churn and improve customer retention strategies.

## How to Use

1. **Download the Dataset:** Ensure you have the dataset with the columns specified above.
2. **Load into Power BI:** Import the dataset into Power BI.
3. **Dashboard Creation:** Use the dataset to create visualizations as described in the project details.
4. **Analysis:** Use the dashboard to analyze customer churn and develop effective retention strategies.


