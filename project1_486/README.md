# [Project 1 486:](/images/BmoreDist2Park.png)

## Topic: 
Determining average distance of residential properties from parks 

## Data: 
__Real_Property:__ http://gis-baltimore.opendata.arcgis.com/datasets/real-property

__Parks:__ https://data.baltimorecity.gov/Culture-Arts/Parks/3r8a-uawz

__Baltimore City__ Line: https://data.baltimorecity.gov/Geographic/Baltimore-City-Line/fy7v-tvcr

## Transformations/Subsets:
__Subsetting Real_Property:__ USEGROUP to R for Residential

__Fix Geometry:__ Residential Properties

__Join:__ Nearest neighbor with Residential Property

## Analysis: 
Nearest neighbor analysis 

Basic Statistics for distance values to determine average distance

## Outputs:
I will be creating a couple outputs. First, I will create an output subsetting the unique value of R from the field USEGROUP of Real_Property. Second I will create an output of fixed geometry for the Residential Property subset. Third, I will geocode the Park data from addresses into Lat/Long coordinates to display the data as a point style vector. Fourth, I will run a nearest neighbor analysis from residential propeties to parks in order to determine distance in feet. Fifth, I will be creating an output joining the output of the nearest neighbor analysis and the fixed geometry of residential property. Lastly, I will symbolize the newly joined distance and residential property and symbolize based on distance from nearest park.  

 








