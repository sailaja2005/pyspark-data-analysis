PySpark Data Analysis 


This repository contains three different PySpark projects focusing on log analysis, movie ratings analysis, and trip data analysis. Each project generates synthetic data, processes it using PySpark, and extracts meaningful insights through transformations, aggregations, and visualizations.
Before running the scripts, install the required dependencies:
pip install pyspark faker plotly kaleido

1.Movie Ratings Analysis


This project simulates movie rating data and performs various analytics.

 Analysis Performed

 
 *Convert timestamps to human-readable format.
 
 *Compute average rating for each movie.
 
 *Identify users who have rated more than 5 movies.
 
 *Find top 5 highest-rated movies.
 
 *Visualize Users vs. Number of Movies Rated.


 2. Trip Data Analysis


This project processes trip data, calculating ride statistics and identifying trends.

 Analysis Performed

 
*Compute trip duration (EndTime - StartTime).

* Calculate fare per mile.

* Identify the top 3 longest trips based on distance.
  
* Find peak trip hours by grouping trips by the hour.
  
* Visualize: Number of Trips per Hour (Line Chart).

3.Log Analysis


This project generates log file data, processes logs using regular expressions, and extracts insights.

*Extract timestamp, log level, and message.

*Count the occurrences of each log level (INFO, ERROR, etc.).

*Filter and display only ERROR logs.

*Group logs by hour and analyze peak log activity.

Results & Visualizations


Users vs. Number of Movies Rated (Histogram)
Trips per Hour (Line Chart with Peak & Low markers)
Log Level Distribution
Visualizations are saved as images in order to display.
