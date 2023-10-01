# Flask for ML model deployement

## Overview
This project demonstrates how to deploy a Machine Learning model using Flask to create a web application for making predictions online. The deployed model predicts fuel consumption in miles per gallon (mpg) based on input features.

![Screenshot](/screenshot/predicting.png)

## Run

1. Clone this repository to your local machine:

```bash
git clone git@github.com:Ewins518/Flask_ML_model_deployement.git
```

2. Navigate to the project directory:

```bash
cd Flask_ML_model_deployement
```

You can run the notebook to generate the model.pkl or just use the one in the project root

## Usage

### Local Deployment

To run the application locally, execute the following command:
```python app.py```

Open your web browser and visit http://localhost:5000 to access the application.

### Heroku Deployment
This project is Heroku-ready, so you can easily deploy it to Heroku for online access. 
Ensure you have the Heroku CLI installed.

1. Log in to Heroku via the CLI:
 
```bash
heroku login
```

2. Create a new Heroku app:

```bash
heroku create your-app-name --region eu
```

3. 
```bash
git init
```
4. 
```bash
git add .
```
5. 
```bash
git commit –am “initial change”
```
6. 
```bash
git push heroku master
```

Visit your deployed app using the URL provided by Heroku.

## Project Structure
The project structure is organized as follows:

`app.py`: The Flask application that serves the web interface and handles predictions.
`model.pkl`: The trained machine learning model for predicting fuel consumption.
`templates/`: HTML templates for the web interface.
`static/`: Static files (CSS) used in the web application.
`requirements.txt`: List of Python packages required to run the application.
`Procfile`: Configuration file for Heroku deployment.
`README.md`: This README file.
`autos_mpg.csv` : CSV file for model training
`ML_model.ipynb` : Jupiter notebook for model training