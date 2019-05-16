# Introduction
Emergency (911) Calls: Fire, Traffic, EMS for Montgomery County, PA

We will be analyzing some 911 call data from Kaggle. 

# Data

The data contains the following fields:

lat : String variable, Latitude

lng: String variable, Longitude

desc: String variable, Description of the Emergency Call

zip: String variable, Zipcode

title: String variable, Title

timeStamp: String variable, YYYY-MM-DD HH:MM:SS

twp: String variable, Township

addr: String variable, Address

e: String variable, Dummy variable (always 1)

# Techniques used:

- Feature engineering: Using lambda expressions to derive reason; hour, month, day of week, date, day/night from timeStamp, 

- Extensive data visualization - ordered countplots, pie charts, lineplot, heatmaps, clustermaps, Facetgrid
