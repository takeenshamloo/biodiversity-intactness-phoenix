# Biodiversity Intactness Index Analysis: Phoenix, AZ

## Author
- **Takeen Shamloo**  
  GitHub: [@takeenshamloo](https://github.com/takeenshamloo)

## About
This repository contains an analysis of the Biodiversity Intactness Index (BII) for the Phoenix subdivision in Maricopa County, AZ. The purpose of this project is to investigate how urban growth impacts biodiversity by comparing BII values for 2017 and 2020. The analysis uses geospatial datasets to calculate biodiversity changes and identify areas of loss or maintenance over time.

### Key Objectives
- Mask and process raster data to isolate BII values for the Phoenix subdivision.
- Calculate and visualize changes in biodiversity between 2017 and 2020.
- Highlight areas experiencing biodiversity loss and suggest potential policy implications.

---

## Repository Structure
The repository is organized as follows:

```{plaintext}
biodiversity-intactness-pheonix
├── notebooks/
│   ├── biodiversity_of_pheonix_arizona.ipynb  # ipynb analysis document
├── output/
│   ├── biodiversity_of_pheonix_arizona.html  # Render of ipynb document
├── README.md                             
├── .gitignore                         # Files and folders excluded from Git tracking
```


---

## Data
### Biodiversity Intactness Index (BII)
- Source: Microsoft Planetary Computer STAC catalog
- Data: Rasters for 2017 and 2020 covering the Phoenix subdivision
- Bounding box coordinates:  
  `[-112.826843, 32.974108, -111.184387, 33.863574]`
- Access: Downloaded via the io-biodiversity collection

### Phoenix Subdivision Shapefile
- Source: U.S. Census Bureau
- Data: Census County Subdivision shapefiles for Arizona
- Access: Downloaded directly from the Census Bureau’s public dataset repository

---

## References
- Microsoft Planetary Computer. (n.d.). **Biodiversity intactness data**. Retrieved from [https://planetarycomputer.microsoft.com](https://planetarycomputer.microsoft.com)
- U.S. Census Bureau. (n.d.). **Census County Subdivision shapefiles for Arizona**. Retrieved from [https://www.census.gov/geographies/mapping-files.html](https://www.census.gov/geographies/mapping-files.html)
- GeoPandas contributors. (n.d.). **GeoPandas documentation**. Retrieved from [https://geopandas.org](https://geopandas.org)
- Rasterio contributors. (n.d.). **Rasterio documentation**. Retrieved from [https://rasterio.readthedocs.io](https://rasterio.readthedocs.io)

---

## Course Reference
This repository was developed as part of the coursework for **Environmental Data Science 220** at UCSB Bren School of Environmental Science and Management.





