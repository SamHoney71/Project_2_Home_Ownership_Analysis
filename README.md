<h1>Howme Ownership Analysis</h1>

<h3>Team 5:  Project 2 <br>Gary Jeter, Andrew Perez, Brent Meulebroeck, Michael Badinger<h/3><br><br>


<ul>This project includes the following apps and processes:</ul>

<strong>app.py is a Flask app that creates a MongoDB database and document and loads data into it from from the data_import py application.</strong> <br>The app creates routes for the following api calls: <br>
a. All annual economic data for all states.<br>
b. All annual economic data for a specific state.<br>
c. All state economic data for a specific year.<br>
d. Economic data for a specific year and state.<br>
e. All State economic data by range of years.<br>
f. Economic data for a specified state by range of years.<br>
g. Distinct states in the data set.<br>
h. Distinct years in the data set.<br>

<strong>data_import.py loads GeFred data from csv files in the resourses folder and returns the data as list of dictionaries to be used by the Flask app.</strong><br>

<strong>boxPlot.js generates the following box plots of the entire dataset</strong> <br>
a. Homeownership rate by year<br>
b. Median HH Income and Per Capita Income by year<br>
c. Total GDP by year<br>

<strong>dog_app.py generates pair plots for all of the fields in the dataset.</strong>
linePlot.js generates a state by state analysis bar line charts for: <br>
a. State GDP vs Home Ownership<br>
b. Median Household Income vs Home Onwership<br>
c. Per Capita Income vs Home Ownership<br>

<strong>map_ed.js generates an education analyis and provides:</strong> <br>
a. An animated scatter chart of education rates over time.<br>
b. HS Diploma and Bachelor's Degree Rate by State.<br>
c. A bubble chart of educational attainment by state.<br>
d. A series of choropleth maps for homeownership, educational attainment, and Median Hh Income.