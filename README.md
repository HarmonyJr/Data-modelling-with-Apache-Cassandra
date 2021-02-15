# Introduction

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app.
The analytics team is particularly interested in understanding what songs users are listening to. Currently, they don't have an easy way
to query their data, which resides in an event directory of csv logs on the app. Once created, the database would provide Sparkify 
with the capability to analyse and gain more insights from the song and user activity data they have been collecting. 

The project contains the events csv log files and Jupyter notebook script. To load the files into the tables, follow the steps below.


#### Project Files

* event_data - The folder contains the event csv log files. 

* event_datafile_new.csv - A user event sample data

* etl.ipynb - Reads and processes a single file from song_data and log_data and loads the data into our tables.

#### Steps To Read and Load Data 
* Execute the Jupyter notebook script to create the tables, read data from the log files and load the data into newly created tables.
* Execute the test file on the Jupyter Notebook to see the loaded data. 
