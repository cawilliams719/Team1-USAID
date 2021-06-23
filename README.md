# Team 1 USAID Product 2

This repository features product 2 constructed as part of a final project in a Web Mapping course. This project is intended as an example of a potential USAID Web Map and is **NOT an official web map** for this organization as its creation is purely academic.

Tools Used:
Mapbox GL JS

Data Used:
USAID - [Activity Locations & Descriptions](https://data.usaid.gov/Evaluation/USAID-Activity-Locations-Activity-Descriptions/jusn-k97d)

NOTE: Although this dataset mentions location, it provides only country name information, therefore to represent this spatially, centroids by country were produced and joined with this dataset. It is important to recognize that these points do not represent an actual location of where the USAID activity is occurring but rather represents the country it is happening in. Lastly, this web map only shows some of the activity in this dataset. For more detail on USAID activity it is recommended that you view the raw dataset they provided.

Current Issues:
Some slight functionality issues that can be improved upon including...
  1. Toggle Double Click Issue - FIXED
  2. Loading large dataset -FIXED
  3. Popup window not closing when hiding layers - somewhat FIXED (could be improved: would be ideal if popup only closed if its respective layer closed rather than either layer is turned off)

*See [Issues page](https://github.com/cawilliams719/Team1-USAID/issues) for further detail
