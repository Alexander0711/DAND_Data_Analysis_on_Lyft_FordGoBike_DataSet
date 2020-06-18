# Exploration of FordGoBike and BayWheels data from Lyft in San Francisco to elaborate growth and business oportunities 

## by Alex (DAND 2020)


## Dataset

For the last project of the Udacity Data Analyst Nano Degree (DAND) program I will work on the FordGoBike / Baywheels dataset.  

FordGoBike and Baywheels is a public bicycle sharing company in the San Francisco Bay Area, California. 

The company share a lot of their user data through a specific Data License Agreement (https://baywheels-assets.s3.amazonaws.com/data-license-agreement.html).

FordGoBike/ Baywheels dataset changed a little during those years, but here you'll find data available through all the datasets :
- duration_sec
- start_time
- end_time
- start_station_id
- start_station_name
- start_station_latitude
- start_station_longitude
- end_station_id
- end_station_name
- end_station_latitude
- end_station_longitude
- bike_id
- user_type
- bike_share_for_all_trip
- rental_access_method

All data was stored in zipped CSV files. I had to download and unzip the files to reach the csvs.

Some of the data was incomplete or needed to be cleaned in more specific form.

## Technical Stack

Python in Jupyter notebook by anaconda.
The following librairies are used for this project in a Jupyter notebook:

- pandas
- numpy
- matplotlib
- seaborn
- datetime
- requests
- os
- io import BytesIO
- zipfile import ZipFile
- math
- calendar
- glob


## Summary of Findings

- Subscribers are doing most of the rides compared to Customers.

- Customers are doing longer rides compared to subscribers.

- In summer the subscribers and customers have done the most rides with peaks during March and October for 2018 and 2019.

- The bike sharing service seems to be used by subscribers to go to and back from work and also maybe from students to go to and back from university. Therefore subscriber use the bike sharing service mainly between Monday and Friday.

- At 8AM and 5PM is recorded the most rides of the day for subscribers and customers. But for subscribers with higher numbers.

- Most rides have a duration between 2 to 12 minute

- Potential for growth and gaining profit is for example to raise the bookings during the times between the rush hours by placing special offers. 



## Feedback to the draft version

- Better use same size and style with default settings for all graphs 

- Better use "darkgrid" for seaborn

- Heat map is needed for the start of the rides (optional also for the ends)



## Key Insights

- Please see the PDF file "Explanatory_visualization_D01_AGO" for the key insights and visualizations