Each of these were made using the sankey.ipynb (now slippy lodes project) that has been uploaded to the folder.
The ipynb also has an example of making a folium map where a work location has been reverse-searched, and a folium map for Richmond workers.

A point to make an Origin and Destination for a census tract was done by making a point in the centroid of the tract.

Each county shapefile has a:
	w_tract : census tract where work location is
	h_tract : census tract where home location is
	workers : count of workers who do this O-D commute
	w_county : county where work location is
	h_county : county where home location is
	HomeX : centroid X for home location
	HomeY : centroid Y for home location
	WorkX : centroid X for work location
	WorkY : centroid Y for work location


