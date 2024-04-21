
# Predicting Telco Customer Churn: An In-depth Analysis

## Overview
Welcome to my project repository, where I explore the Telco customer churn prediction using machine learning techniques. This project aims to provide valuable insights into the factors influencing customer churn and build a predictive model to help businesses identify customers at risk of churning. Leveraging Python for data analysis and machine learning, I uncover compelling trends and offer strategic recommendations for reducing customer churn.

## Key Insights
### Data Exploration
- Senior citizens are less likely to churn compared to non-senior citizens.
- Customers with phone services are more likely to churn.
- Customers with paperless billing are more likely to churn.
- Customers who pay with electronic checks are more likely to churn.

### Modeling
- XGBoost outperformed other models in terms of overall accuracy.
- Random Forest and Logistic Regression also showed promising results.
- Balancing the dataset using SMOTE improved the models' performance, especially in terms of predicting churn (True Positives).

### Recommendations
- Use XGBoost, Random Forest, or Logistic Regression for predicting churn.
- Focus on improving services for customers with phone services and paperless billing.
- Offer incentives for customers to switch to longer contract terms.
- Encourage customers to use alternative payment methods to electronic checks.
- Taking into consideration the threshold during churn predictions can also assist in identifying more customers likely to churn
- It is also key to note that in an attempt to ensure “customers who have been predicted to likely churn” do not churn, by probably intruding some discounts for such customers, there is a likelihood the model might have selected a few or some customers who are not likely to churn. This might cause financial constraint. To reduce this type of burden on the company, a good threshold which has a good balance of both true positives and false negative is essential.


## Getting Started
To get a local copy up and running, follow these steps:

1. Clone this repository to your desired folder:

   ```bash
   cd my-folder
   git clone https://github.com/tettehosabutey49/Telco-Customer-Churn-Prediction-using-Machine-Learning.git

Change into the cloned repository:
```sh
cd Indian-Startup-Project
```
Create a virtual environment:
```sh
python -m venv env
```
Activate the virtual environment:
On Windows:
```sh
env\Scripts\activate
```
On macOS/Linux:
```sh
source env/bin/activate
```

### License
This project is [MIT](./LICENSE) licensed.

## Author
 Author: Emmanuel Osabutey