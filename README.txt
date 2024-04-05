
Program Creator:   Jeremiah L. Marimon

Instructions:  

	1.) Open the Marimon-FinalProject folder
		(make sure to not delete any of the files in the folder such as the pictures etc.)
	2.) Once there, open Jupyter notebook, and then open Marimon-FinalProject.ipynb
		(make sure you have Internet connection while using Widget 3) 
	3.) Install the simplekml module using the command prompt by entering:  pip install simplekml
		(all other modules used are native to the anaconda distribution)
	4.) Run the first two cells
	5.) In the main window, you will have 3 widgets to choose: Widget 1, Widget 2, or Widget 3
	6.) To choose Widget 1, click "Compass and Transit Rule"
	7.) You may choose "Input data" to input data directly or "Import csv file"
	8.) For "Import csv file" in Widget 1, you can open ex_points input.xlsx from the Widget 1 folder
		(the expected output when exported will be the file named 
			ex_points_expected_output.xlsx found in the Widget 1 folder)
	9.) Go back to the main window by clicking the "Back" button
	10.) To choose Widget 2, click "Lot Technical Description"
	11.) You may choose "Input data" to input data directly or "Import csv file"
	12.) For "Import csv file", you can open ex_points_td input.xlsx, ex_points_td2 input.xlsx, or ex_points_td3 input.xlsx,
		found in the Widget 2 folder
	13.) After inputting data from any of the two options, click "Generate", the calculations will be displayed.
	14.) You may export the data containing the Lot Technical Description by clicking "Export"
		(the expected exported output for ex_points_td input.xlsx, ex_points_td2 input.xlsx, or ex_points_td input.xlsx
			are ex_points_td_expected_output.xlsx, ex_points_td2_expected_output.xlsx, and
			 ex_points_td_expected_output.xlsx, respectively, found in the Widget 2 folder)
	15.) Go back to the main window by clicking the "Back" button
	16.) To choose Widget 3, click "Plot to Google Earth"
		(make sure that you have internet connection when using this widget, without internet connection
			the widget might still work but the point icon might change back to the default yellow pin)
	17.) You can import KML_ex1 input.xlsx or KML_ex2 input.xlsx from the Widget 3 folder. 
		(the expected outputs are KML_ex1_expected_output.kml and KML_ex2_expected_output.kml, respectively,
			from the Widget 3 folder)
		Restrictions:  -the points must be in WGS84 coordinates and in decimal degrees
				- to close the plot, the last point must be the first point 
	18.) You can export the kml accordingly after importing the csv file.
	19.) Go back to the main window by clicking the "Back" button
	20.) Click the exit button on the upper right to close the GUI
			
			
References:

	GE10 - Lecture 9 - Horizontal Position Computation by Traverse
	GE10 - Lecture 13a - Simple Subdivision
	Python Tkinter GUI Tutorial - https://www.youtube.com/watch?v=Aim_7fC-inw
	Open Files Dialog Box - Python Tkinter GUI Tutorial #15 - https://www.youtube.com/watch?v=Aim_7fC-inw
	Python simplekml tutorial - https://www.youtube.com/results?search_query=simplekml
	Treeview - Python Tkinter GUI Tutorial #116 - https://www.youtube.com/watch?v=YTqDYmfccQU
	Scrollbar Tkinter - https://www.youtube.com/watch?v=0WafQCaok6g
	Multilple Windows Tkinter - https://www.youtube.com/watch?v=bl5xdJ-b8GQ



