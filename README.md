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
- Software: SQLlite, Flask
# Summary Temperature statistics for June & December
![Temp summary](https://github.com/lallben/surfs_up/blob/main/June_Dec_temps_summary.png)
# Summary Precipitation statistics for June & December
![Temp summary](https://github.com/lallben/surfs_up/blob/main/June_Dec_precip_summary.png)
