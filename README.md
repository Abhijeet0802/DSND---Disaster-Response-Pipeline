# DSND---Disaster-Response-Pipeline
Disaster Response Pipeline Project as part of the Udacity Data Scientist Nano Degree Program

## Project Overview
In this project, we will apply data engineering skills to analyze disaster data from Figure Eight to build a model for an API that classifies disaster messages.

In the Project Workspace, we have a data set containing real messages that were sent during disaster events. we will be creating a machine learning pipeline to categorize these events so that we can send the messages to an appropriate disaster relief agency.

The project also includes a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data. This project is put in place to highlight the software skills, including ability to create basic data pipelines and write clean, organized code!

### Project Components
There are three components of the project.

1. ETL Pipeline
We will write a Python script, process_data.py, a data cleaning pipeline that:
    Loads the messages and categories datasets
    Merges the two datasets
    Cleans the data
    Stores it in a SQLite database
    
2. ML Pipeline
We will write a Python script, train_classifier.py, a machine learning pipeline that:
    Loads data from the SQLite database
    Splits the dataset into training and test sets
    Builds a text processing and machine learning pipeline
    Trains and tunes a model using GridSearchCV
    Outputs results on the test set
    Exports the final model as a pickle file
    
3. Flask Web App
We will write a Python script, run.py, a web app that:
    First Creates a web app 
    Adds data visualization using Plotly
    Takes an input message and classifies it to categories
