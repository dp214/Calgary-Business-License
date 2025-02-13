# Calgary-Business-License

# Calgary Business Licenses Analysis

## Overview

This Jupyter Notebook provides an in-depth analysis of business licenses issued in Calgary. The goal is to explore various trends such as license type distribution, business license status, growth patterns, and the lifespan of businesses. The analysis uses data from Calgary's business licenses database and employs several data science techniques such as classification models, clustering, Principal Component Analysis (PCA), and exploratory data analysis (EDA) to uncover key insights and support potential decision-making.

## Dataset

The dataset used in this analysis is the "Calgary Business Licenses" dataset, which contains details of businesses, including their issue and expiration dates, license types, and more. The data is used to examine trends in business licensing, growth, and renewal status over time.

### Columns:
- `GETBUSID`: Unique business identifier
- `TRADENAME`: Name of the business
- `HOMEOCCIND`: Home-based business indicator
- `ADDRESS`: Address of the business
- `COMDISTCD`: Community district code
- `LICENCETYPES`: Type of license
- `FIRST_ISS_DT`: Date of issue
- `EXP_DT`: Expiration date
- `JOBSTATUSDESC`: License status (e.g., "Renewal Licensed" or "Pending Renewal")
- `POINT`: Geographical coordinates
- `GLOBALID`: Unique global identifier

## Purpose

The purpose of this analysis is to:
1. Understand trends in business licenses issued over time.
2. Identify the types of licenses most commonly issued in Calgary.
3. Analyze the renewal rates and statuses of businesses.
4. Apply clustering and classification models to predict business license trends.
5. Perform Principal Component Analysis (PCA) to explore the most influential features.

## Steps Taken

1. **Data Preprocessing**:
   - Data cleaning and feature engineering.
   - Encoding categorical variables for modeling.

2. **Exploratory Data Analysis (EDA)**:
   - Distribution analysis of business license types and statuses.
   - Temporal trends of business licenses over time.

3. **Modeling**:
   - K-Means clustering to segment businesses based on their growth rates and license types.
   - Logistic regression and Random Forest models to predict license renewal status.

4. **Principal Component Analysis (PCA)**:
   - Used to reduce the dimensionality of the dataset and visualize key components.

## Requirements

To run this notebook, you will need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the necessary libraries by running:


pip install pandas numpy matplotlib seaborn scikit-learn
How to Run the Notebook
Clone this repository to your local machine:


Copy
git clone https://github.com/yourusername/Calgary_Business_Licenses_Analysis.git
Navigate to the project directory:


Copy
cd Calgary_Business_Licenses_Analysis
Open the Jupyter notebook:


Copy
jupyter notebook Calgary_Business_Licenses_Analysis.ipynb
Follow the instructions in the notebook to run the analysis.

## Insights
Business License Status: A large proportion of businesses are in the "Renewal Licensed" or "Pending Renewal" statuses, indicating a steady flow of business renewals.
Home-Based vs Non-Home-Based Businesses: Non-home-based businesses represent a significant portion of the dataset, highlighting the dynamic commercial landscape of Calgary.
Temporal Trends: Certain business types tend to have seasonal renewal patterns, indicating economic cycles influencing renewal behaviors.
PCA: The PCA analysis shows that community district and job status are the most important factors influencing business operations.

# Acknowledgements
Calgary Business Licenses dataset
Jupyter, pandas, seaborn, matplotlib, scikit-learn



## Conclusion
This analysis reveals several key trends about Calgary's business environment, including high renewal rates, preference for non-home-based businesses, and the importance of community district location for business success. These insights can help investors, policymakers, and business owners better understand the landscape and make informed decisions.
