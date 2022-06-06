VISUM Scenario Manager Plot Extraction Tool
----------------------------------------------
----------------------------------------------

Contact: Aadil Nawaz 


Description
----------------------------
Tool to generate plots from active scenarios in the Scenario Manager
Can generate plots from multiple GPA files
Modifies Title of Legend based on scenario’s description

Requirements:
---------------------------------
Works on VISUM 2021.01-05 or later
Works for both Python 2 and Python 3 
Requires glob module which can be installed by command pip install glob2 in command prompt.



Procedure to run
-----------------------------
Copy relevant GPA files in the same folder containing the script
In ‘Edit Project’ window, set as active the scenarios for which plots needs to be generated
Run the script from the Scripts menu


Checks:
-----------------------------
Throws warning in case of missing GPA files.
Throws warning when there are duplicates in description of active scenarios
Informs about total no. of plots generated and no. of active scenarios
Informs total no. of uncalculated scenarios for which plots could not be generated 






