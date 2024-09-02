# Contributors: Jinyoung Suh, Harshitha Rasamsetty

# SourceSavvy: Showcasing User's Recent Activities with Strava API

# Overview: This project showcases a user's recent activities using the strava API. 

# Steps to Execute:
  1. Create an account on Strava's Developer Portal
  2. Create an application on strava.com/setting/api
     - Get authorization code from authorization page
     - Exchange authorization code for access token & refresh token
     - View my activities using the access token just received
  4. Download and install postman
     - Use refresh token to get new access tokens
  5. Request our recent record api from Strava via email
  6. Install QGIS and make a map for recent activities
  7. Export as a qgz file and convert it to shapefiles
  8. Create pyhton code for make a plot using geopandas and matplotlib
  9. Execute unittest


# Requirements
- geopandas==0.12.2
- matplotlib==3.8.0
