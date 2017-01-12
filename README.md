# indego_opr
Our code for the class project of OPR 624 Class

Rebalancing Indego Bike Share Stations
OPR 624 Final Project
Xiaoqin Yi, Dinesh Hemnani
Bike share programs provide the missing link between public transportation systems, keeping the user healthy and reducing the environmental pollution. That's why they are becoming popular and every major city is moving towards using them.
Keeping the bike sharing system optimized is necessary to keep it running smoothly. A paetron would not want to see an empty station when he is in need of a bike and would not like to see a completely filled station when he wants to return a bike.
In our project, we aim to balance the City of Philadelphia's Indego Bike Share program, that has 105 stations, over 900 bikes and over 2000 docks throughout the city. The data for the project comes from Open Data Philly's Indego API that provides realtime information about the stations, including the number of bikes available, number of docks available, time of closing and its coordinates.
The goal of the project is to find the minimum possible distance to be covered by a balancing truck to balance all stations to a fixed ratio of bikes to docks such that a paetron will not face a shortage of bikes or docks. To optimize the total distance traveled, the distances are calculated from Google Maps API providing driving distances between stations.
For the purposes of this project, I have calculated the distances in advance and stored them in files which are later on imported. This is because of the free limits of calculating distances from Google's API, which can be increased if paid.
