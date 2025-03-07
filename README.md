# MAP671 Final Project
## United States National Parks
Created by: Maya Miller 

Project created for MAP 671 at the University of Kentucky

### Map Data
Map data retrieved from:

United States Census, Tiger/Line Shapefiles https://www.census.gov/cgi-bin/geo/shapefiles/index.php

National Park Service, Department of the Interior, NPS Data Store (Unit Boundaries) https://irma.nps.gov/DataStore/Reference/Profile/2224545?lnv=True

National Park Service, Department of the Interior, NPS Data Store 2005. Geospatial data for the Vegetation Mapping Inventory Project of Badlands National Park https://irma.nps.gov/DataStore/Reference/Profile/2233241


Map projection:

* National Parks Overview: EPSG 4269
* South Dakota Parks: ESRI 103523
* Badlands National Park Vegetation: ESRI 103523

Map scale:

* Nation Parks Overview: 1:27000000
* South Dakota Parks: 1:2000000
* Badlands National Park Vegetation: 1:54000


### Map Descriptions

**National Parks Overview:**

This map displays all of the National Parks found in the United States as defined by the National Park Service. The primary focus of this map is the parks found in the states themselves. Therefore, the data was filtered to remove any parks found within the US territories such as the Virgin Islands or American Samoa. 
This map can be viewed below and in the final index page.
![markdownsummary](/Project%20Maps/National%20Parks%20Overview1200.jpg)


**South Dakota Parks**

This map is a zoomed in version of the larger National Parks Overview. It displays the National Parks within the state of South Dakota. All of the parks are found within the western side of the state. There are five total parks of varying sizes: Badlands National Park, Mount Rushmore National Memorial, Wind Cave National Park, Jewel Cave National Monument, and Minuteman Missile National Historic Site.
This map can be viewed below and in the final index page.
![markdownsummary](/Project%20Maps/South%20Dakota%20Parks1200.jpg)

**Badlands National Park Vegetation** 

The Badlands National Park Vegetation Map displays the wide variety of vegetation that is present in and around the Badlands National Park. I utilized Geospatial vegetation data from the National Park Service for this particular park. I specifically imported the "BADL_VegPolys" from the zip file as this contained the vegetation data. Then, I viewed the attributes table to identify the attribute that labeled the types of vegitation. In this case, it was the "MapUnit_Name". Therefore, in the symbology tab, I used the "MapUnit_Name" to categorize the vegetation. Because there is a wide variety of vegetation in this park, I felt it was best to use the random color generator. I randomized a few times to find a color combonation that I felt went well together. Ultimately, there were many types of vegetation, and while I contomplated eliminating some types from the categories and merging the eliminated with the "others" category, I felt this would decrease the accuracy of the map. Although I have visited and lived in the area, I do not know enough about vegetation to accurately eliminate one over another. Therefore, I left all types of vegetation in the map. Additionally, in contrast to my previous maps, I made the borders of the national park white so the boundaries are still visible while still viewing the park's vegetation as the geospatial data displays vegetation from outside the park boudaries as well. This map can be viewed below and in the final index page.
![markdownsummary](/Project%20Maps/Badlands%20National%20Park80000.jpg)



Link to final index page
