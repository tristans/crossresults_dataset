#UCI Cyclocross Race Data
##Data Provided by Colin Reuter of crossresults.com

Broken down by year. File format is tab separated values. All files have a header row describing data.
Each year contains:
* average_field_strength - The average crossresults points for all starters per race and gender. Includes: 
** Region and Lat/Long information for that race.
* average_points - The average crossresults points for the top 10 finishers per race and gender. Includes: 
** Region and Lat/Long information for that race.
* predicted_points - The predicted crossresults points for the tenth place finisher, per race and gender. Includes: 
** Region and Lat/Long information for that race.
* race_list - a list of UCI CX races with their race ID number.


##Todo:
Normalize race data - move region, lat/long to the race_list file. Remove these fields from other files, and refer to race with race ID only.
Clean data - some races in race list do not have a race ID. Could make up an arbitrary ID.
