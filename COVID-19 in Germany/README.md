This project is a simple jupyter notebook which returns and plots the daily number of people in Germany who are infected with the Corona Virus SARS-CoV-2.
I was tired of looking up the relevant numbers on various pages and institutions. Once I found out about the HTTP API created by Jan-Philip Gehrcke (https://gehrcke.de/), 
which gives convenient access to the relevant data (Thank You!!!), I created this notebook to have it all in one place.

## The Data Set
The data used in this notebook is retrieved from the HTTP API created by Jan-Philip Gehrcke (https://gehrcke.de/).
To read all about the data sources and the API, check out this GitHub Repository: https://github.com/jgehrcke/covid-19-germany-gae#attribution

As a summary:

These are official numbers published by individual state health ministries in Germany. The numbers from the individual (hundreds of) public German health offices (Gesundheitsämter) are first collected and aggregated on the state level, by the individual state health ministries. From here, they are further collected and published through "situation reports" by the Robert Koch-Institut (yielding the data points in this database before March 17), but also by ZEIT ONLINE (yielding the data points in my database from March 17 on).
The dataset includes historical data for individual Bundesländer (states). Manually curated from RKI "situation reports", until March 17. Since then, based on the more up-to-date reports by the individual states themselves. To my knowledge that is unique and the main reason I started this project.
