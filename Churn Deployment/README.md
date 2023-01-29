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