 # INFM600 Information Organisation
This is the dataset created for the INFM600 Information Organisation assignment

-----------
Version 
-----------  
Version 1.0 (October 2015)  

---------------- 
Description 
----------------
This dataset is a combination of the two datasets: Libraries and Presubmission Meetings. This dataset includes the list of all the presubmission community meetings that have taken place in the Howard County since the year 2002 and all the libraries present in the county with their accurate geographical locations and unique identification numbers.This dataset can be further combined with the Open Space Natural Resource Dataset and used to answer questions which cannot be answered by any individual dataset.

---------------- 
Question
---------------- 
What places will be ideal to start new development projects and hold presubmission meetings taking into account the location and type of the project ?

From the combined dataset, the open spaces available for development and the type of zoning in that area can be found out. By comparing this with the older or the ongoing projects mentioned in the rows with an FID of presubmitted meeting, new and unique project ideas for particular areas can be formed.  This will ensure that all the projects in particular areas are unique. Also, the available open spaces and libraries close to the location of the project location can be easily located. This will help in planning the presubmission meetings for that particular project.\
This analysis can be plotted on a map with the help of the geometrical positions along with the type of the project, zonings, its acreage, meeting locations etc. The map key can connect the locations plotted with another document containing a table with the other information like meeting dates, meeting times etc.This will help in future planning and organisation of new development projects.

---------------- 
Data Sources
----------------
 * Libraries 
	This dataset describes the locations of all the libraries present in the Howard County by describing the city, zip code and geometrical locations of the libraries. It has unique identification numbers assigned to each library.  

* Presubmission Community Meetings
	This dataset includes the list of the presubmission community meetings held in the Howard County since the year 2002. It describes the statistics related to the meeting which include the project name, meeting dates, locations of the meetings and the details about the proposed development projects.

* Open Space Natural Resource
	This dataset has the list of the open spaces present in the Howard County. It describes these locations with accurate geometrical locations, acreage and zones. This data can be used to make plans for future development of these spaces.

---------------- 
Files
---------------- 
* Libraries & Presubmitted Community Meetings.xlsx
	- This file is the combined dataset 

* README.txt
	- Contains the description of the repository

* Processing Document 
	- Contains details of the processing steps involved in the combing of the documents.\

---------------- 
License
---------------- 
This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc/4.0/.

--------------------------
Acknowledgements
--------------------------
I thank the Howard County for creating and allowing to use the datasets used in this repository.

---------------
References
---------------
Chitale, J. (2015). Libraries & Community Meetings. Retrieved from https://drive.google.com/open?id=0B4Z3HU_4lhcLVjc5dm1xMDhPYmc

Howard County. (n.d.). Libraries. Retrieved from Howard County. (n.d.). Data Downloader and Viewer. Retrieved 12 October 2015, from https://gis.howardcountymd.gov/geoserver/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=general:Libraries&outputFormat=shape-zip\

Howard County. (n.d.) Presubmission Community Meetings. (n.d.). Data Downloader and Viewer. Retrieved 12 October 2015, from https://gis.howardcountymd.gov/geoserver/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=general:vPublic_PresubmissionCommunityMeetings&outputFormat=shape-zip

Howard County. (n.d.). Open Space Other. (n.d.). Data Downloader and Viewer. Retrieved 12 October 2015, from https://data.howardcountymd.gov/geoserver/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=general:Open_Space_Natural_Resource&outputFormat=shape-zip
