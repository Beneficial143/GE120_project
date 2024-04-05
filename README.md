# GE120_project
A desktop GUI program I made during my first year for my project in GE 120 - Introductory Object-Oriented Programming for Geomatics.

		- This is a python tkinter GUI project I made as a requirement for GE 120, which is an introductory programming course for geodetic 
		engineering students. The main window of the GUI has three widgets:
 
			(1) Compass and Transit Rule
				- allows user to input distances and azimuths directly through the interface or through a csv file to be imported
				- calculates the corrections according to the Compass or Transit rule, and displays them
				- user may export the resulting calculations as a csv file
			(2) Lot Technical Description
				- allows user to input coordinates of the lot directly through the interface or through a csv file to be imported
				- displays the plot of the lot and calculates the technical description
				- user may export the technical description as a csv file
			(3) Plot to Google Earth
				- allows user to import a csv file containing WGS84 coordinates of the plot of land in decimal degrees
				- allows the user to export a kml file plot of the land that can be opened in google earth
