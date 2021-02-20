# Movies-ETL

This project takes movie data from Kaggle and Wikipedia and merges it into a postgres database.
Using ETL, the data is extracted into a json and two csv files, then the data is cleaned up in order to combine the Kaggle and Wikipedia data from the movies. The information available here can update regularly (though the ratings data does take about 40 minutes to enter into the database). A config.py file with the appropriate postgres password for the local host is required to write this data to a database.