# Customer-_Segmentation_Project

This project aims to analyze customer data and perform segmentation to help an automobile company target potential customers effectively. The goal is to predict the customer segments for new markets based on the existing customer behavior in their current markets.

## Dataset:

The dataset contains various attributes of customers, including gender, age, marital status, education, profession, work experience, spending score, family size, and an anonymized category. The target variable is the 'Segmentation', which represents the customer segment.

## Project Steps:

Data Preprocessing:
Handle missing values: Any missing values in the dataset were treated using appropriate imputation techniques, ensuring minimal data loss.
Encode categorical variables: Categorical columns were converted into numerical form using one-hot encoding for further analysis and modeling.
Scale numerical variables: Numerical columns were standardized to normalize their ranges and prevent any dominance of certain features.
Feature Selection/Engineering:

Correlation analysis: A correlation matrix was calculated to identify the relationships between each feature and the target variable. This helped select the most influential features for customer segmentation.
Correlation Analysis:

The correlation analysis revealed significant insights:
Age had a negative correlation, suggesting that older customers were less likely to belong to certain segments.
Family size exhibited a positive correlation, indicating that larger families were more likely to belong to specific segments.
Work experience showed minimal correlation, indicating it had little impact on customer segmentation.

##Findings:

The correlation analysis provided valuable insights into the factors influencing customer segmentation. Age and family size emerged as significant predictors of customer segments. Work experience, on the other hand, had a negligible impact on customer segmentation.

## Conclusion:

Based on the analysis, the automobile company can optimize its marketing efforts and product offerings for different customer segments. The findings indicate that older customers and those with smaller families should be targeted with tailored marketing strategies. Work experience was found to have limited significance in differentiating customer segments.

