
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

**Approach**
------------------------------------------------------------------------------------------------------------------------
Descriptive statitics has been employed to run this analysis and the insights have been presented in form of interactive maps to better understand the underlyings of the data and popularity of various industries.
Following are some of the screenshots from the interactive maps for the most number of businesses in a zipcode:

<img src="https://github.com/charvi5/SF-Industry-Analysis/blob/master/image1.png" height="500" width = "500">

The interactive map here can be zoomed into smaller areas and help figure number of businesses in each area on the basis of its latitude, longitude coordinates. The businesses have been grouped together on the basis of similar coordinates and the cluster size helps determine the number of businesses in that area.  
This approach was applied over a machine learning approach to determine similar businesses because it is much more intuitive and easier for business to derive insights using visual method of data storytelling. Such methods are easily scalable across business and makes it easier for product teams to build a solution on top of it. 
Although, as a future work a more statiscal, machine learning approach can be applied to build predictive insights out of this.

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
```pip install package-name ```
- If pip throws an error due to packages not being a part of pip anymore, use ```condo install package-name``` , this is an Anaconda command and directly downloads packages in Anaconda

**Windows:**
- Open Windows command prompt and enter ```py -3.6 -m pip install package-name```

-------------------------------------------------------------------------------------------------------------------------
