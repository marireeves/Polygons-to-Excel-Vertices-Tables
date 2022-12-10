# Polygons-to-Excel-Vertices-Tables

Create tables of spatial polygon vertices named by attributes in an ESRI .shp file attribute table.

This code reads in an ESRI .shp file and uses the sf and openxlsx packages in R to read in the data, change the geospatial projection of the data if needed, then summarize the data into different excel tables based on one of the fields in the shapefile. In this case I used a shapefile of Hawaiian Island coastlines (included with repo) and summarized the data by island. Other R packages used are shown in the code. The code may require slight modification to meet your needs. Hope you find it useful.
