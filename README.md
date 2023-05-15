# Intelligent Automation of SFO Crime Prediction using Different AI Methods

# Analysis

The important features that are responsible for analysis are incident date, time, and location and they are highly correlated attributes. The attributes such as day of the week, time of the day and seasons of the year are important factors for the crimes. It is observed that most of the crimes are happening on Friday and most frequently occurring crimes are theft, burglary, robbery, missing person, and drugs. More crimes are committed in the north-east part of San Francisco. There are quick resolutions for cases like robbery, burglary, and assault. The seasons like summer and fall are attracting more crimes. It is clearly visible that the number of crimes had decreased during 2020, it might be because of Pandemic.  The crimes are mostly occurring during afternoon hours, and few are happening during evening hours. If we analyze the yearly trends, the occurrence of the crimes has changed from fall to winter after the pandemic. The attributes timeofday, hour, latitude, longitude, and police distinct are highly correlated attributes. Analysis of historical data from 2003 to 2018 gives more meaningful insights on the data pattern, trend and how to build the model. The different models like Random Forest, K-nearest neighbor, ANN, Tablet and time series analysis are created to understand the behavior of the data with the model.

# WebApp

To create the webapp start with YAML code as the first line of the jupyter notebook by providing the required filters as part of the code. Define the dashboard name as part of the WebAPP page. The webapp needs the mercury libraries hence install the libraries for python and use the command such as jupyter trust, mercury add, and mercury watch on the created file. This will initiate the webapp in the link “http://127.0.0.1:8000” .

# Interactive Dashboard

The interactive dashboard needs different python libraries for map and interactive display and methods. The folium library to display the map and ipywidgets library for interactive display are installed for python. The next step is to identify the important features for the dashboard and
followed by initialization of the widgets for the features that are part of filter conditions.
The description and layout specify the display of the filter in specific format. The function should be defined to get the data and transform the data if necessary to required aggregation. Use folium method to display map and any other graph or chart if necessary. Use widget interactive method to invoke the function and required widget that are part of filters to display the interactive dashboard.

# Dataset Link: https://data.sfgov.org/browse
