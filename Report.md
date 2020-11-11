# Finding Similar Neighborhood in a Target City

## Problem Definition
Every time a person changes a job or finds a job a new city or just wants to locate to another city, the person would, typically, like to move to a similar neighborhood 
in the new city. I would like to solve this problem where a person would specify his current address in the current city and then specify the target city. 
The solution would produce a list of neighborhoods in the target city with similarity score.  
The target audience is anybody locating to another city, may be because of a job change or for any other reason. 
The solution would take into account personal weights for some of the attributes used to cluster the neighborhoods. 

**Audience**: Anybody locating to another city and wanting to find a place to live in a similar neighborhood in a new city.


## Data Source:
This solution will use venue data  including schools, dining places, parks, trails, museums, music venues and use it to cluster the neighborhoods 
in the source and target cities. It will use clustering to find the clusters of similar neighborhoods in each of the cities. Well, it will quanity the 
neighborhood aournd the current location of the person using similar vanues and not do clustering in the source city. To find the closest neighborhood 
it will use some of the appropriate recommendation models, for example K-Nearest Neighbors (KNN), to find the most similar neighborhood. 

**Primary Data Source**: I will mostly use Foursquare for venue data for neighborhoods in the source and target cities

**Secondary Data Source**: I may use GeoPy or Google Geocoder for longitude and latitude information to visualize the neighborhood clusters.
