# Disaster Response Pipeline Project

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.fdfd
    `python run.py`

3. Go to http://0.0.0.0:3001/

### Github Repo

<https://github.com/SRI-HARI-M/Udacity_DSND_Disaster_Pipeline>

### Summary

 The aim of this DSND term 2 project is to create Machine Learning based Disaster Response Data Pipelines to filter the messages and help deliver essentials to the really needed people. In this project, we clean and categorize the provided disaster_messages and then use GridSearchCV ML method to identify patterns in the messages to zero in on legitimate requests for help. In the end, the project is deployed as an app using flask framework.

### Results & Conclusion

The ML model is sucessfully developed and deployed as an app using flask microframework.			
			