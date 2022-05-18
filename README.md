# Path_Planning
Get and set latitude and longitude for your location and the distnation you want to go to and with help of some functions which i implement you can get path betwwen the to points with dirations. this is part of my graduation projects the geolocation of your current location we get it by using GPS Module with Arduino and the distnation is one of set of location the user should enter it an choose from it. 

### Instructions:

- first get the your `current location` (latitude and longitude) 
- then, set them by using `set_curr_location(long,lat)` function
- then, you can set your distnation location by using `set_dist_location(long,lat)` function
- after that use the function: `get_directions()` without any parameters and it will get the direstion and the distance from your location untill reach the distnation.
- finally call the function: `converting_list(list)` and pass the output list from the previous one and its output will be the final instraction which will be sent to the embedded system directly. 

### bouns functions:
- `get_curr_location()` which return your current location
- `get_dist_location()` which return your distination location
