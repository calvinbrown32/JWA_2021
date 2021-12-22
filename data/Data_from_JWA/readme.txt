Analyst Hire Test Data Sources

#TriMet_Network - shapefile containing line features of TriMet Bus Routes and MAX Lines

#MAX_Yellow_stops - shapefile containing stop location points for MAX Yellow Line

#Route2_Stops - shapefile containing stop location points for Route 2

#Multnomah_Population_Blockgroups.csv - contains blockgroup GEOID and ACS 2015 5-year population estimate

#Oregon_blockgroups - TIGER boundary shapefile of Oregon Census block groups

#OpenStreetMap - folder containing various OSM base layers for the Portland region (Mapzen area extract)


GEOID - 410510072023


4.5x = 0.804



Hello Michelle, 

My work has been very busy this last week, and my GIS analysis demo is still a work in progress. I anticipate completing the project within the next few days. My project is an ambitious improvement of my previous Trimet residential coverage analysis for JWA.  

I am making two major improvements to my previous methodology:

	1) I am using the osmnx Python library to generate isochrones that encompass everywhere that can be reached by traveling 1/2 mile along the street network from each transit stop. Isochrones provide a more realistic model of travel behavior and access to transit than the Euclidean buffers that I used in my previous analysis.  

	2) Every step of my project is Python driven and uses open source tools, including the retrieval of Census data (via the Census API) and OSM network data (using osmnx). With minor tweaks, my code can be used to efficiently perform a similar analysis of any transit system in the U.S. The code is well documented, which fosters collaboration and development, and allows for quality assurance, peer review, and reuse on future projects. 

I'm excited to share these improvements soon, and look forward to connecting with more members of the JWA team. In the meantime, please feel free to reach out with any questions. 

Thank you, 
Calvin



retrieve, model, analyze, and visualize street networks from OpenStreetMap





