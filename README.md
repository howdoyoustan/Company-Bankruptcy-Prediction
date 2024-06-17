# CaseStudy
Predicting Company Bankruptcy Using Financial Data

Objective: To perform an in-depth analysis of a financial dataset to predict the likelihood of a
company going bankrupt. The analysis involves data preprocessing, exploratory data analysis
(EDA), hypothesis testing, feature engineering and selection, and applying machine learning
techniques for classification.

Tasks Overview
Data Understanding and Preprocessing: Load dataset, handle missing values, and remove outliers.
Exploratory Data Analysis (EDA): Generate statistics, visualize data distributions, and analyze feature-target relationships.
Hypothesis Testing: Identify significant features influencing bankruptcy.
Feature Engineering and Selection: Create new features, apply dimensionality reduction, and select relevant features.
Modeling: Split data, train logistic regression model, and evaluate performance.
Model Interpretation and Insights: Interpret model coefficients, summarize key insights, and provide actionable recommendations.

Positive Coefficients:
Quick Assets/Current Liability (2.330434): This feature has the highest positive coefficient, suggesting that higher quick assets relative to current liabilities significantly increase the likelihood of bankruptcy.<p>
Total debt/Total net worth (1.638548): Higher total debt relative to total net worth increases the likelihood of bankruptcy.<p>
Borrowing dependency (1.276802): Higher borrowing dependency is associated with an increased likelihood of bankruptcy.<p>
Cash/Current Liability (0.694515): Higher cash relative to current liabilities increases the likelihood of bankruptcy.<p>
Current Liability to Equity (0.647164): Both instances of this ratio indicate that higher current liabilities relative to equity increase the likelihood of bankruptcy.<p>
Working Capital Turnover Rate (0.577829): Higher working capital turnover rate is associated with an increased likelihood of bankruptcy.<p>
Current Liability to Current Assets (0.416493): Higher current liabilities relative to current assets increase the likelihood of bankruptcy.<p>
Debt ratio % (0.340616): A higher debt ratio increases the likelihood of bankruptcy.<p>
Working Capital to Total Assets (0.081007): A higher ratio of working capital to total assets slightly increases the likelihood of bankruptcy.<p>
Operating Funds to Liability (0.062888): A higher ratio of operating funds to liability slightly increases the likelihood of bankruptcy.<p>

Negative Coefficients:
Equity to Long-term Liability (-0.088467): Higher equity relative to long-term liability slightly decreases the likelihood of bankruptcy.<p>
Current Liability to Assets (-0.326279): Higher current liabilities relative to assets decrease the likelihood of bankruptcy.<p>
Net worth/Assets (-0.340616): Higher net worth relative to assets decreases the likelihood of bankruptcy.<p>
Inventory and accounts receivable/Net value (-0.521923): Higher inventory and accounts receivable relative to net value decrease the likelihood of bankruptcy.<p>
Cash/Total Assets (-0.543420): Higher cash relative to total assets decreases the likelihood of bankruptcy.<p>
Cash flow rate (-0.800831): A higher cash flow rate significantly decreases the likelihood of bankruptcy.<p>
Current Ratio (-1.272814): A higher current ratio (current assets to current liabilities) significantly decreases the likelihood of bankruptcy.<p>
Quick Ratio (-1.497249): A higher quick ratio (quick assets to current liabilities) significantly decreases the likelihood of bankruptcy.<p>
Liability to Equity (-2.674568): This feature has the highest negative coefficient, suggesting that higher liabilities relative to equity significantly decrease the likelihood of bankruptcy.<p>

General Insights
High Positive Impact: Quick assets relative to current liability, total debt relative to total net worth, and borrowing dependency have the strongest positive impacts, indicating these are key risk factors for bankruptcy.<p>
Moderate Positive Impact: Ratios involving current liabilities, debt ratios, and cash to current liabilities have moderate positive impacts, suggesting they are important but not as influential as the top factors.<p>
High Negative Impact: Liability to equity, quick ratio, current ratio, and cash flow rate have the strongest negative impacts, indicating these are protective factors against bankruptcy.<p>
Moderate Negative Impact: Cash to total assets and inventory/accounts receivable to net value have moderate negative impacts, suggesting they contribute to financial stability.<p>

Inferences / Summary
Risk Factors: High quick assets to current liabilities, high total debt to net worth, and high borrowing dependency are significant indicators of increased bankruptcy risk.<p>
Protective Factors: High liability to equity ratio, high quick ratio, high current ratio, and high cash flow rate significantly reduce the risk of bankruptcy.<p>
Complex Relationships: Some features like current liability to equity and operating funds to liability have small coefficients, indicating their impact is less pronounced but still noteworthy.<p>

