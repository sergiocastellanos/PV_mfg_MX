This is the repo for the PV Manufacturing in Mexico project.

A set of scripts and raw files are included to replicate this work.

IPython Notebooks:
(1) "DistancesOnGoogleMaps.ipynb": Calculates distances between state capitals in Mexico by using Google's API
(2) "GeocodingCountiesOnOpenStreetMaps.ipynb": Calculates the lat,long coordinates for all counties in Mexico. This is used for other sub_projects where more detailed distances are required, or different ways of measuring (Manhattan, Euclidean, etc) distances might be required.

Data files:
(1) "counties.txt": Contains all the counties in Mexico, as published online at INEGI (http://www.inegi.org.mx/)
(2) "countiesLatLong.csv": Results from "Geocoding....ipynb" and slightly processed afterwards.
(3) "Distances-Mexico-Roads_Cleaned.xlsx": Results from "Distances....ipynb" and slightly processed afterwards.