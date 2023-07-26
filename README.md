# always-sunny-in-casablanca
 Historical Weather Forecast Comparison to Actuals (BASH SCRIPT)

# Purpose
This repository is to show the process of how I created this BASH script, the steps involved to create it, with of course the final script itself. 
This is the final project for the IBM LX0117EN Linux Commands & Shell Scripting course through edex. This write up is to demonstrate my understanding of the material and ability to apply the skills. 

# Scenario
You've been tasked by your team to create an automated Extract, Transform, Load (ETL) process to extract daily weather forecast and observed weather data and load it into a live report to be used for further analysis by the analytics team. As part of a larger prediction modelling project, the team wants to use the report to monitor and measure the historical accuracy of temperature forecasts by source and station.

As a proof-of-concept (POC), you are only required to do this for a single station and one source to begin with. For each day at noon (local time), you will gather both the actual temperature and the temperature forecasted for noon on the following day for Casablanca, Morocco.

At a later stage, the team anticipates extending the report to include lists of locations, different forecasting sources, different update frequencies, and other weather metrics such as wind speed and direction, precipitation, and visibility.

**You must extract and store the following data every day at noon, local time, for Casablanca, Morocco:

The actual temperature (in degrees Celsius)
The forecasted temperature (in degrees Celsius) for the following day at noon.
**
# Data Source
For this practice project, you'll use the weather data package provided by the open source project wttr.in, a web service that provides weather forecast information in a simple and text-based format. For further information, you can read more about the service on its GitHub Repo. https://github.com/chubin/wttr.in#readme

# Skills gained and used
Shell scripting (BASH);
Download raw weather data;
Extract data of interest from the raw data;
Transform the data as required;
Load the data into a log file using a tabular format;
Schedule the entire process to run automatically at a set time daily;






