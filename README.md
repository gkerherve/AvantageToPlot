# AvantageToPlot
A software package written in Python for automated plotting of XPS data acquired using Avantage on the Thermo K-alpha system

Requirement
------------

The followings must be installed to run Avantage_To_plot_13.py:
•	Python 3.6 or above
•	Panda for python (Read Excel files)
•	PPTX for python (Create PowerPoint presentation)
•	Tkinter for Python
•	Excel and PowerPoint
•	ConfigXPS_13_All_....xls file
•	PowerPoint template file

Quick Instruction
-------------------

1.	Create Excel datafiles of the samples that need to be plotted
2.	In the samples Excel files 
  a.	Add the ‘Carbon BE’ value in the Title worksheet
  b.	Add the ‘Normalisation’ value in the Title worksheet.
  c.	Move all the worksheets that do not need plotting after the ‘Title’ or ‘Quantifications’ worksheets
3.	In the ConfigXPS file
  a.	Choose the Config Tab number 
  b.	Select the correct directory and files
  c.	Check if the followings are required:
    i.	C-C correction
    ii.	Quantifications
    iii.	Automatic Shirley background
4.	Compile the AvantageToPlot
5.	On AvantageToPlot window, click ‘Run’ and look for possible error in the python compiler. Make sure the previously created PPT file is close before running the file


READ THE MANUAL.PDF FOR A MORE DETAILED INSTRUCTION
