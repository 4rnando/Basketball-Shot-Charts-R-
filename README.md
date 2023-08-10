**Creating Charts on Basketball Shot Attempts using R**

The chart is based on information from data using the BasketballAnalyzeR package to extract the information given the inputted player within the NBA 2017-2018 Basketball Season.  

The following list was stated to find insights on a player: 
	• What was the time taken for the player to attempt the shot?
	• Is the player well-rounded around the court? If not, what specific place of the court does the player seem to prefer?
	• Is the player consistent? Furthermore, the percentage of shots made at specific places on the court.


How it Works 
	• Load the BasketballAnalyzeR package to upload the data 
	• Load the data into a frame format by running the PbP manipulation script
	• Filter through the Pb data by the player (Stephen Curry) 
	• Create the distance between the Hoop and the center of the court (10-41.75)
	• Create the chart by running the 'shotchart' script
	• Create the chart to plot the points of the attempted shots that were Missed or Made (z = result)
	• Run the same chart with a different color background (Line 22, script)
	• Split the graph/court into 5 sectors and categorize by playlength of time based on Color (Line 16, script)
	
The pictures of the final plot graph should look like the images I uploaded (Steph Curry Playlength.pdf) (Steph Curry Made-Missed.pdf) ![image](https://github.com/4rnando/Basketball-Shot-Charts-R-/assets/51896140/2ea00777-3480-430c-85f8-155c27b62987)


