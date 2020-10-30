# LIVING LANDSCAPES: Exploring the Relationship between LA Parks and Encampments

[Project Proposal](https://github.com/rlaborde/up206a-rayne/tree/main/up206a%20Project)

**Status Update** 
I spend most of my time completely amazed that any of this is possible and so accessible, even though the problem solving struggle is real. My biggest barrier is still not knowing how to phrase what I want to ask/do in order to be able to search for similar work, questions, and tutorials - but I am getting better at interpreting error messages! I am very proud of my buffer maps that sort parks by # of encampment service request reports.

**Data Update**
I currently have [park shapes and general info (address, etc)](https://github.com/rlaborde/up206a-rayne/blob/main/up206a%20Project/data/LA_Parks_Information.geojson), 311 Homeless Encampment report data from [2016](), [2017](https://github.com/rlaborde/up206a-rayne/blob/main/up206a%20Project/data/2017-311_Homeless_Encampment_Requests_raw.csv), [2018](https://github.com/rlaborde/up206a-rayne/blob/main/up206a%20Project/data/2018_311_Homeless_Encampments_Requests_raw.csv), [2019](https://github.com/rlaborde/up206a-rayne/blob/main/up206a%20Project/data/2019-311_Homeless_Encampments_Requests_raw.csv), and [2020](https://github.com/rlaborde/up206a-rayne/blob/main/up206a%20Project/data/2020-311_Homeless_Encampments_Requests_raw.csv), and [census tract data on race, population density, income, and rent burden](https://github.com/rlaborde/up206a-rayne/blob/main/up206a%20Project/data/ACS-Data_Pop-Density_Race_Med-Income_Rent-Burden.csv). Because there is not a particularly strong correlation with any of that census data, I would also like to pull in home ownership rates. I am working on including transportation lines, as prior research has indicated links between transit accessibility and encampments, and my ideal data set is still resources available in parks (restrooms, etc) though I have yet to find a particuarly trustworthy source for that. 

**Concerns**

*Major Concerns:* Right now, I'm wondering if I need to pull some data into Stata to test for significant relationships, or if there is a way to do this in Python? I am concerned that I'm not finding particularly strong correlations between encampment reports and census tract data, though I am finding valuable information in terms of park correlation. How/where do I host a map that is too big to preview on GitHub?

*Minor Concerns:* I feel like I am doing something incorrectly or missing something when making charts - I feel like for every chart I have to slightly change the way I'm coding it and though I've gotten better at problem solving it, I don't quite get why the command input style needs to vary so much. I am also diving into the world of how to consolidate my year data to make a "scrollable" map - I know it's possible, but it's very intimidating and I'm concerned about notebook size limitations.
