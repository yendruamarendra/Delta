# Project - Delta


This is  Data Engineering Project with data of flight details such as flight number, date, time and status etc.
Our project is built in a way for all the flight data streamed we would be poviding data for flights with most recent status.


### Data
We will be working on Flight Leg Dataset Which consists of ~250000 records of flight data.

This projects consists of two tasks.
1. to write an sql query to get flights with most recent status.
2. To write python function with input parameters as file path, ingest the provided data and report all the available flights with their most recent status.

### Task 1:

Please refer to the note file with sql query where we used row_number and paritions to get latest status of flights.


### Task 2:

Please refer to ipynb file and run all the steps to get dataframe results for flights with most recent data.
1. Please use google collab to run the ipynd file.
2. We are using spark in this project so installed spark as first step.
3. 
