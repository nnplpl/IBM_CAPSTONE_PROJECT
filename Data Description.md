
# Data Description
The data for this project has been retrieved and processed from different sources, gicing careful consideration to the accuracy of the methods used  
The data consists of three parts:  
* Borough data with postal code
* Geocoding data
* Venue data with borough details 

By joining the first two dataset, we are able to find the centriod of each borough. Then use the data of venue to cluster the boroughs and find the similariry with ***M2M***.  
## 1. Borough data with postal code
This data is gained from Wikipedia page *\'https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M \'*. 
* Geocoding data
## 2. Geocoding Data
The file is downloaded from *\'http://cocl.us/Geospatial_data \'*  
The latitude and longitude data are stored in this file. By reading these data into a dataframe, the geometric locations are able to be connected with different boroughs. 
## 3. Venue data 
The venue data is found out by passing the required parameters to the ***FourSquare API***, and creating another DataFrame to contain all the venue details along with the respective boroughs.
