# Project - Delta


This is  Data Engineering Project with data of flight details such as flight number, date, time and status etc.
Our project is built in a way for all the flight data streamed we would be poviding data for flights with most recent status.


### Data
We will be working on Flight Leg Dataset Which consists of ~250000 records of flight data.

This projects consists of two tasks.
1. to write an sql query to get flights with most recent status.
2. To write python function with input parameters as file path, ingest the provided data and report all the available flights with their most recent status.

### Task 1:

Please refer to the rtf file with sql query where we used row_number and paritions to get latest status of flights. ( Also writted the same in spark.sql
in ipynb file.


### Task 2: Run Steps

Please refer to ipynb file and run all the steps to get dataframe results for flights with most recent data.
1. Please use google collab to run the ipynd file.
2. We are using pyspark in this project so installed spark as first step.
3. Upload the Dummy_Flight_Leg_Data.csv file into the google collab folders
4. (https://user-images.githubusercontent.com/91281151/209038656-c70d557c-8c54-4030-880d-776b77e65d16.png)

5. 
