# surfs_up
# Background
W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.
# Objective
The purpose of this project is to essentially determine the summary statistics for the month of June & December. This analysis is conducted from data collected over a period of seven years (2010 - 2017).
# Sources
There are essentially two tables 'Measurement' and 'Station' that are contained within an SQLite database called hawaii.sqlite.<br>
The 'Measurement' table has the following columns:<br>
- ID
- Station
- Date
- Prcpt (precipitation)
- tobs (temperatures)<br>

The 'Station' table has the follwing columns:<br>
- id
- station
- name
- latitude
- longitude
- elevation
# Tools used:
- Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper
- Software: SQLlite, Flask<br>

The code for data storage and retrieval can be found in the [SurfsUp_Challenge.ipynb.](https://github.com/lallben/surfs_up/blob/main/SurfsUp_Challenge.ipynb)
# Summary Temperature statistics for June & December
![June Temp](https://github.com/lallben/surfs_up/blob/main/june_temps.png)
![Dec Temp](https://github.com/lallben/surfs_up/blob/main/dec_temps.png)
<p align="center">
  <img src="https://github.com/lallben/surfs_up/blob/main/June_Dec_temps_summary.png" alt="Temp Summary"/>
</p>

# Summary Precipitation statistics for June & December
![June Rain](https://github.com/lallben/surfs_up/blob/main/june_precip.png)
![Dec Rain](https://github.com/lallben/surfs_up/blob/main/dec_precip.png)
<p align="center">
  <img src="https://github.com/lallben/surfs_up/blob/main/June_Dec_precip_summary.png" alt="Temp Summary"/>
</p>
