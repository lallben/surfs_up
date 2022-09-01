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
# Summary statistics
## Summary Temperature statistics for June & December
![June Temp](https://github.com/lallben/surfs_up/blob/main/june_temps.png)
![Dec Temp](https://github.com/lallben/surfs_up/blob/main/dec_temps.png)
<p align="center">
  <img src="https://github.com/lallben/surfs_up/blob/main/June_Dec_temps_summary.png" alt="Temp Summary"/>
</p>

## Summary Precipitation statistics for June & December
![June Rain](https://github.com/lallben/surfs_up/blob/main/june_precip.png)
![Dec Rain](https://github.com/lallben/surfs_up/blob/main/dec_precip.png)
<p align="center">
  <img src="https://github.com/lallben/surfs_up/blob/main/June_Dec_precip_summary.png" alt="Temp Summary"/>
</p>

# Analysis based on Summary statistics
Based on the statistical analysis derived from the temperature and precipitation over a period of seven years it seems that the rainfall in December is more than in June, however the rainfall is not very high. The Mean rainfall in December is 21mm as compared to 13mm in June.<br>
Furthermore, the temperatures in both the months are quite comparable. The Mean temperatures for June & December are 74 & 71 degrees respectively.<br>
Overall, taking into account just the temperatures and rainfall, and assuming all other conditions are the same, it would seem that the shop could be open throughout the year.<br> 
However, there are many other variables that contribute to a perfect surfing environment like wind conditions etc. These would have to be taken into account as well in arriving at a informed decision.

# Further Analysis to help in decision making:
In order to help in arriving at a more informed decision I then did a further analysis to break up rainfall and temperature by each station. This will help identify the stations that would be more conducive to mantaining shops throughout the year or will help W Avy to promote and apprpriate resources accordingly.<br>
The reasoning is that not all stations need to be resourced in the same manner throughout the year.<br>
The code for this analysis can be found at the end in the [SurfsUp_Challenge.ipynb.](https://github.com/lallben/surfs_up/blob/main/SurfsUp_Challenge.ipynb)<br>
![June Station](https://github.com/lallben/surfs_up/blob/main/june_summary_by_station.png)
![Dec Station](https://github.com/lallben/surfs_up/blob/main/dec_summary_by_station.png)
