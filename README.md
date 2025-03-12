# cloudnative_geospatial_workshop

---
## **1. Introduction to Cloud Native Geospatial**  
   - What does "Cloud Native" mean for geospatial data?  
   - Benefits of cloud-native formats (efficiency, scalability, accessibility)  
   - Overview of five formats: COG, FlatGeobuf, PMTiles, GeoParquet, COPC

## **2. COG (Cloud-Optimized GeoTIFF) – Raster Data in the Cloud**  
   - What is a COG, and how does it improve traditional GeoTIFF?  
   - Advantages: progressive loading, streaming, and cloud storage  
   - Tools for handling COGs (GDAL, QGIS, Rasterio)  
   - Hands-on: Converting and visualizing COGs in QGIS and Python  

## **3. FlatGeobuf (FGB) – Efficient Vector Data**  
   - What is FlatGeobuf, and how does it work?  
   - Comparison with traditional formats (GeoJSON, Shapefile)  
   - Streaming and random access capabilities  
   - Hands-on: Using FlatGeobuf in QGIS and Python  

## **4. PMTiles – Serverless Tile-Based Data**  
   - What is PMTiles, and how does it differ from MBTiles?  
   - Using PMTiles for web mapping and visualization  
   - Serverless tile distribution without a backend  
   - Hands-on: Generating and hosting PMTiles  

## **5. GeoParquet – Geospatial Data in a Columnar Format**  
   - What is Parquet, and why is GeoParquet important?  
   - Benefits for big data processing and analytics  
   - Integration with DuckDB  
   - Hands-on: Working with GeoParquet in Python and SQL  

## **6. COPC – Cloud-Optimized Point Clouds**  
   - What is COPC, and how does it differ from LAZ/LAS?  
   - Fast access and streaming for LiDAR data  
   - Integration with PDAL and Potree for visualization  
   - Hands-on: Processing COPC files  

## **7. Comparison & Use Cases**  
   - When to use each format?  
   - Combining formats in a cloud-native architecture  
   - Storage and accessibility options (S3, GCS, Azure Blob)  

## **8. Hands-on Final Project**  
   - Building a workflow using FlatGeobuf, PMTiles, GeoParquet, and COPC  
   - Storing and efficiently sharing data in the cloud  
   - Optimization and best practices  

## **9. Discussion & Future Perspectives**  
   - The evolution of cloud-native geospatial  
   - Emerging standards and tools  
   - Open discussion and Q&A  
