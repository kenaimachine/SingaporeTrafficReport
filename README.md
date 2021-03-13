# SingaporeTrafficReport

Design a Singapore traffic report system.

The system will collect data from the Singapore LTA data link as follow

* Read the road incidents from API http://datamall2.mytransport.sg/ltaodataservice/TrafficIncidents 

* Read the road traffic bands from API http://datamall2.mytransport.sg/ltaodataservice/TrafficSpeedBandsv2

Program collect the data from the mentioned API above and display on a visualization graph. 
The visualization graph should display the Singapore map with different markers to indicate the traffic incident and traffic bands at each location. 

1. Python program request the traffic incident URL and return the JSON data
2. Extract and format the traffic incident data require for display in Singapore map
3. Python program request the traffic band URL and return the JSON data
4. Extract and format the traffic band data require for display in Singapore map
5. Add the data into the display map with different markers to represent the traffic incident and traffic bands
6. When clicking on the marker on the display map it should show the information of either traffic incident or traffic bands
