# Financial Health Assessment of Companies
---

## Company Bankruptcy Prediction using Financial Leverage-Based Features
## Introduction

The "Company Bankruptcy Prediction using Financial Leverage-Based Features" project aims to develop a predictive model that can accurately determine the likelihood of a company filing for bankruptcy. By analyzing historical financial data, including key ratios such as profitability, liquidity, and solvency, the model provides valuable insights for investors, lenders, and regulatory bodies. Utilizing PySpark for efficient data processing and logistic regression for predictive modeling, this project not only identifies early warning signs of financial distress but also aids in informed decision-making and effective risk management.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Team Members](#team-members)
3. [Objectives](#objectives)
4. [Dataset](#dataset)
   - [Key Financial Ratios](#key-financial-ratios)
5. [Methodology](#methodology)
   - [Data Preprocessing](#data-preprocessing)
   - [Feature Engineering](#feature-engineering)
   - [Model Training](#model-training)
   - [Model Evaluation](#model-evaluation)
   - [Model Deployment](#model-deployment)
6. [Business Objectives](#business-objectives)
7. [Benefits and Applications](#benefits-and-applications)
8. [Data Insights](#data-insights)
9. [Conclusion](#conclusion)
10. [How to Use](#how-to-use)
    - [Clone the Repository](#clone-the-repository)
    - [Install Dependencies](#install-dependencies)
    - [Run the Model](#run-the-model)
    - [Example Workflow](#example-workflow)
11. [Contact](#contact)

## Project Overview

This project aims to predict the likelihood of a company filing for bankruptcy by developing a machine learning model trained on financial leverage-based features. The model leverages historical financial data, incorporating factors such as profitability, liquidity, and solvency ratios, to provide valuable insights for investors, lenders, and regulatory bodies. The project utilizes PySpark for efficient large-scale data processing and logistic regression for predictive modeling.

## Team Members

- **Sharjeel Nawaz**
- **Siddhesh Mishra**
- **Tirth Shah**

## Objectives

- **Develop a Predictive Model:** Create a robust model to predict company bankruptcy.
- **Leverage PySpark:** Use distributed computing to handle large datasets efficiently.
- **Identify Key Financial Factors:** Determine which financial metrics are most indicative of bankruptcy risk.

## Dataset

- **Source:** Kaggle Datasets, Yahoo Finance
- **Instances:** 6819
- **Variables:** 96 (focused on 6 key financial variables)
- **Key Financial Ratios:**
  1. **Current Ratio:** Measures a company's ability to pay its short-term obligations.
  2. **Quick Ratio:** A conservative liquidity ratio excluding inventories from current assets.
  3. **Gross Margins:** Percentage of revenue left after deducting the cost of goods sold.
  4. **Net Income:** Total earnings or losses.
  5. **Leverage Ratio:** Measures the extent of debt financing.

## Methodology

### Data Preprocessing
- **Cleaning:** Remove or impute missing values.
- **Transformation:** Scale and normalize financial features to prepare them for modeling.

### Feature Engineering
- **Derive Features:** Create additional features from existing data to capture complex relationships and enhance predictive power.

### Model Training
- **Algorithm:** Use logistic regression for its interpretability and effectiveness in binary classification tasks.
- **PySpark:** Employ PySpark for distributed computing, enabling efficient handling of the large dataset.

### Model Evaluation
- **Metrics:** Evaluate the model using accuracy, precision, recall, and F1-score.
- **Risk Stratification:** Categorize companies into different risk levels based on their predicted bankruptcy risk.

### Model Deployment
- **Integration:** Deploy the model as a service or integrate it into existing financial analysis workflows for real-time bankruptcy prediction.

## Business Objectives

1. **Identifying Early Warning Signs:** Detect specific patterns or thresholds in financial leverage-based features that indicate potential bankruptcy.
2. **Assessing Profitability Impact:** Analyze how profitability metrics like gross margins and net income contribute to bankruptcy prediction.
3. **Evaluating Industry-Specific Factors:** Determine if the model's predictive capabilities vary across different industries and adjust accordingly.
4. **Determining Leverage Significance:** Assess the importance of leverage ratios compared to other financial metrics.
5. **Temporal Analysis:** Examine how predictive patterns change over time by analyzing trends in financial data.
6. **Risk Stratification:** Stratify companies into risk categories to help stakeholders prioritize interventions.

## Benefits and Applications

- **Risk Assessment:** Provide a tool for investors and lenders to assess the risk of potential bankruptcies.
- **Portfolio Management:** Enable financial institutions to monitor and manage investment portfolios, reducing potential losses.
- **Early Warning System:** Serve as an early warning system to alert stakeholders of potential financial distress.
- **Regulatory Compliance:** Help regulatory bodies identify companies at risk of bankruptcy, ensuring proper oversight and investor protection.
- **Industry Analysis:** Offer insights into financial health and risk factors specific to different industries.

## Data Insights

- **Correlation Analysis:** Identified a moderate negative correlation between "Bankrupt?" and "ROA(C) before interest and depreciation before interest," indicating that lower returns on assets are associated with a higher risk of bankruptcy.
- **Importance of Ratios:** Quick and current ratios were found to be particularly important in predicting bankruptcy.

## Conclusion

By leveraging financial leverage-based features, Python, PySpark, and logistic regression, this project successfully developed a predictive model for company bankruptcy. The model's ability to analyze large datasets and provide accurate predictions offers significant benefits to investors, lenders, and regulatory bodies, enabling informed decision-making and effective risk management.

## How to Use

### Clone the Repository
```bash
git clone https://github.com/yourusername/Financial-Health-Assessment-of-Companies.git
cd Financial-Health-Assessment-of-Companies
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Model
- Use the provided Jupyter Notebook `Prediction_Analysis.ipynb` to train and evaluate the model.
- Input a company ticker symbol to fetch real-time data from Yahoo Finance and predict bankruptcy risk.

### Example Workflow
1. **Enter Ticker Symbol:** Input the ticker symbol of the company you want to analyze.
2. **Fetch Financial Data:** The model fetches the company's financial data from Yahoo Finance.
3. **Predict Bankruptcy Risk:** The model processes the data and outputs a prediction indicating whether the company is at high risk of bankruptcy.

## Contact

For any questions or further information, please contact the project team members:

- **Sharjeel Nawaz:** [sharjeel@umd.edu](mailto:sharjeel@umd.edu)
- **Siddhesh Mishra:** [sidm@umd.edu](mailto:sidm@umd.edu)
- **Tirth Shah:** [shah00@umd.edu](mailto:shah00@umd.edu)

---
