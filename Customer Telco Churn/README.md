![Logo](images/title.png)

## Dataset Info: 

**Customer Telco Churn**
Location:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The data set includes information about:

Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents


## Intial Steps 

Run `deploy.ipynb` to generate the pickle file.


# **Model Deployment** 

**Deploying Model as a Web-Service**
- Creating a virtual environment with pipenv.
- Creating a script for prediction.
- Putting the script into a Flask app.
- Packaging the app to Docker.


**Batch Model Deployment**
- Running the model regularly (hourly, daily, monthly, etc).
- Turn the notebook for training a model into a notebook for applying the model.

**Docker**  
- `docker build -t churn-prediction-service:v1 .`  
- `docker run -it -p 9696:9696 churn-prediction:latest`
