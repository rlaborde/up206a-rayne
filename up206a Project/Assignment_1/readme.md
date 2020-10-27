# Initial Data Exploration
The *Laborde_Week3* files show my initial data exploration, through 2017 LA 311 calls and a geojson file of LA Parks.

The *2017-LA* files are my first pass at some data analysis. *Parks_w_Encampment* shows the number of Encampment Service Requests directly within the park polygons, while *Park_Areas_w_Encampment* uses buffers to include an approximately 1/2 block radius around each park, within which encampments are also counted. This is important because most addresses are - by admission of the 311 operators - approximated, including to intersections not avaialble within parks. This permeter zone is then crucial to capture.
