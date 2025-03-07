***PySpark Data Analysis***


This repository contains three different PySpark projects focusing on Log Analysis, Movie Ratings Analysis, and Trip Data Analysis. Each project:

Generates synthetic data
Processes data using PySpark
Extracts insights through transformations, aggregations, and visualizations
Installation
Before running the scripts, install the required dependencies:


pip install pyspark faker plotly kaleido


**Movie Ratings Analysis**

   
This project simulates movie rating data and performs various analytics.

Analysis Performed


*Convert timestamps to human-readable format

*Compute average rating for each movie

*Identify users who have rated more than 5 movies

*Find top 5 highest-rated movies

*Visualize: Users vs. Number of Movies Rated (Histogram)


**Trip Data Analysis**

   
This project processes trip data, calculates ride statistics, and identifies trends.

Analysis Performed

*Compute trip duration (EndTime - StartTime)

*Calculate fare per mile

*Identify top 3 longest trips based on distance

*Find peak trip hours by grouping trips by the hour

*Visualize: Number of Trips per Hour (Line Chart with Peak & Low markers)


**Log Analysis**

   
This project generates log file data, processes logs using regular expressions, and extracts insights.

Analysis Performed

*Extract timestamp, log level, and message

*Count the occurrences of each log level (INFO, ERROR, etc.)

*Filter and display only ERROR logs

*Group logs by hour and analyze peak log activity

Visualize: Log Level Distribution


**Results & Visualizations**

Users vs. Number of Movies Rated (Histogram)

Trips per Hour (Line Chart with Peak & Low markers)

Log Level Distribution (Bar Chart)

Visualizations are saved as images.







