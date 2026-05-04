Customer Churn Prediction & Automated Email Alert System
Overview

This project is an end-to-end Customer Churn Prediction System built using Machine Learning. It predicts whether a customer is likely to churn and extends the solution by automatically sending email alerts to high-risk customers, simulating a real-world retention workflow.

Key Features
Churn prediction using Logistic Regression
Customer risk segmentation (Low / Medium / High)
Data analysis and visualization
Automated email notification system
End-to-end pipeline from data processing to action
Dataset
Telecom Customer Churn Dataset (~7000 records)
Includes:
Customer demographics
Services subscribed
Billing details
Contract information
Target variable: Churn

Note:
The dataset does not contain real email addresses. Email data is simulated for demonstration purposes.

Tech Stack
Language: Python
Libraries:
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Environment: Jupyter Notebook / Google Colab
Email Service: SMTP (Gmail)
Project Workflow
1. Data Preprocessing
Handle missing values
Convert data types
Remove unnecessary columns
2. Exploratory Data Analysis
Analyze churn distribution
Identify relationships between features
Extract patterns
3. Feature Engineering
Label encoding for categorical variables
Feature scaling using StandardScaler
4. Model Building
Logistic Regression
Train-test split
Model training and evaluation
5. Risk Segmentation

Customers are categorized into:

Low Risk
Medium Risk
High Risk
6. Automation Layer
Identify high-risk customers
Trigger automated email alerts
Include customer-specific information
Results
Model Accuracy: Approximately 81 percent
Successfully identified high-risk customers
Automated email alerts triggered for selected users
Email Alert System
Implemented using Python smtplib
Sends structured HTML emails
Includes:
Tenure
Monthly charges
Risk notification
Important Setup (Email Feature)

To enable email functionality:

Enable 2-step verification in your Google account
Generate an App Password
Update the following in code:
sender_email = "YOUR_EMAIL@gmail.com"
password = "YOUR_APP_PASSWORD"

Important: Do not upload your real password to GitHub.

How to Run
git clone https://github.com/your-username/churn-project.git
cd churn-project
jupyter notebook

Alternatively, run the notebook in Google Colab.

Project Structure
churn_project.ipynb
dataset.csv (optional)
README.md
Key Insights
Month-to-month contracts have higher churn rates
Higher monthly charges increase churn probability
Customers with shorter tenure are more likely to churn
Unique Contribution

This project extends beyond basic machine learning by including:

Risk-based segmentation
Automated alert system
Business-oriented workflow
End-to-end implementation
Future Enhancements
Use advanced models such as XGBoost
Build an interactive dashboard
Integrate with real CRM systems
Enable real-time predictions
Author

Abhijith
Data Analytics Project
