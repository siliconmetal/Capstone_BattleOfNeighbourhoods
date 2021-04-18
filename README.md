# Capstone_BattleOfNeighbourhoods

### Overview:
In this project, Foursquare API is used to abstract cartographical features about Ahmedabad city i.e. hotels, top-picks, fun points, and restaurants(using Requests & geolocator library). And using json_normalise, the abstracted semi-structured JSON data is normalized into flat tables using pandas data frames and filtering them. After filtering the data frame, folium is used for the visualizations as markers on the map.      


#### Libraries used:
* pandas
* numpy
* requests
* geopy
* folium
* json_normalize
* random



It includes a link to my IBM-Watson studio notebook:
https://eu-gb.dataplatform.cloud.ibm.com/analytics/notebooks/v2/23b76889-0398-48a8-88b6-69b0f72135c9/view?access_token=913eaace54d0c8c8bf47944cbf4f366d93277d7d087ce5d3d2241dc736f23001


___In this notebook; geopy.geocoder, folium, json_normalize, pandas, and numpy is used to abstract cartographical data from Foursquare API and normalize the semi-structured JSON data into data frames and then using the abstracted data, all the cartographical details is pointed on the map with folium.___  
