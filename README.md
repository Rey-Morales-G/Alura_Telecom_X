This project presents an exploratory data analysis (EDA) of a telecom customer dataset with the goal of understanding customer churn — the phenomenon where customers discontinue their service.

Customer churn represents a critical business challenge in the telecommunications industry, as retaining existing customers is generally more cost-effective than acquiring new ones.
This analysis aims to identify patterns and customer characteristics associated with churn, providing insights that can support data-driven retention strategies.

Objectives
Explore the structure and quality of the dataset
Analyze the distribution of customer churn
Identify relationships between churn and key variables such as:
contract type
customer tenure
monthly charges
Generate insights to help reduce customer attrition

Dataset
Source: Telecom customer dataset (JSON format)
Size: 7,267 customers × 21 features
Target variable: Churn

Data Preparation
The dataset was loaded directly from a JSON file and inspected for quality and consistency.
No missing values were found in the dataset
Column names and data types were preserved as provided
No transformations or feature engineering were applied at this stage
This approach ensures transparency and allows the analysis to reflect the original data.

Exploratory Data Analysis 
The exploratory analysis focused on understanding how churn is distributed among customers and how it relates to key features.
Main analyses include:
  Churn distribution across the customer base
  Churn vs. contract type
  Churn vs. customer tenure
  Churn vs. monthly charges
Visualizations were created using matplotlib to highlight trends and patterns.

Key Insights
Customers on month-to-month contracts show significantly higher churn rates.
Newer customers are more likely to churn than long-term customers.
Customers with higher monthly charges tend to churn more frequently.
Churn is not randomly distributed and is influenced by pricing and contract structure.

Reco
Based on the findings, the following actions are suggested:

Encourage long-term contracts through incentives or loyalty benefits.
Strengthen onboarding and engagement during the first months of service.
Review pricing strategies for customers with higher monthly charges.
Use the insights from this analysis as a foundation for future churn prediction models.

Tools & Technologies: Python, Google Colab. pandas, matplotlib

