
Description
-------------------------------------------------------------------------------------------------------------------------
This analysis has been performed to see which new industries have sprung up over time in San Francisco area and which of these industries have potential for maximum growth.
This dataset includes the locations of businesses that pay taxes to the City and County of San Francisco.
The dataset was obtained by Treasurer and Tax Collector's office of California. 

Notes
-------------------------------------------------------------------------------------------------------------------------
- The code has been written used Python3 using Jupiter notebook as interface

- The code needs to be executed in a sequential fashion as in certain case previously created tables are referred to later

- The encoding of the input dataset has been taken as ‘ISO-8859-1’ instead of default ‘UTF-8’ . Due to some special characters mentioned in the file, UTF-8 encoding threw errors while reading files

Installing libraries and packages
-----------------------------------------------------------------------------------------------------------------------
To run the notebook, following list of packages must be installed in the system:
-  Pandas
-  Numpy
-  matplotlib
-  geopandas
-  folium
-  shapely
-  zipcode

**Mac OS:**
- To download libraries and packages being loaded in first block of the code, go to Terminal and download packages using 
'''pip install package-name'''
- If pip throws an error due to packages not being a part of pip anymore, use ‘condo install package-name’ , this is an Anaconda command and directly downloads packages in Anaconda

**Windows:**
- Open Windows command prompt and enter py -3.6 -m pip install package-name

-------------------------------------------------------------------------------------------------------------------------
