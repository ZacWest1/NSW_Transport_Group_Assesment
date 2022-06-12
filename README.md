# NSW_Transport_Group_Assesment
 
This was created as a three (3) person team for our major assessment in the unit "Data Science". Here we took New South Wales Public Transport data for three (3) months to analyse where is the best location to place a coffee shop and where to advertise for it. We also looked at what are the best times to open and advertise based on demographic densities at different hours during normal work weeks and holidays. The group consisted of Zac West (me), John Benstead and Najib Rezai. We scored a High Distinction (HD) in this project including 100% in our initial pitch and 100% in our video presentation summarising our project and findings.

Below is a summation of our key files:


GeoPandas Heatmap:

	GeoPandas was used for visualisation. The code here used the "The 2000" files to generate a heatmap of the postcodes from our other data sets.
	This helped us to visualise any patterns in the postcode data.

Group 60 Final:

	Contains the project summary and goals of the project as well as the initial analysis for the updated data files. The pie charts and histograms
	were part of understanding the data as well as analysing population density and movement for the suburbs. This is also where the top five
	highest commuter volume suburbs was found: Sydney CBD, Parramatta, Bondi Junction, Chatswood and Strathfield.

Kernel Density Estimation:

	KDE was used to generate a probability density function to the histograms of the time data for the 5 highest commuter volume suburbs.
	From these density estimations, the best time periods for proportion of commuter exposure could be determined. This was completed using
	the trapezoidal rule for area under a curve to determine the time period with the greatest proportion of commuters for each suburbs stations.
	This process was conducted for two seprarted cases: weekdays (Monday-Friday) and weekends (Saturday and Sunday) as their distributive 
	functions were significantly different (as found in Group 60 Final).

Parsing and Renaming Locations:

	This was the data cleaning portion of the notebooks. The data contained location information which was a mix of postcodes, station names, 
	building names and street names. This was converted to only be postcodes to help with overall analysis for each suburb.
