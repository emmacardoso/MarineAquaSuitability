# Potential Marine Aquaculture Suitability for Oysters in West Coast United States' Economic Exclusive Zones
## Overview
This repository contains an rmarkdown document and associated r scripts for analyzing the suitability of Economic Exclusive Zones (EEZ) off the West Coast of the United States for marine aquaculture. The analysis focuses on identifying areas suitable for oyster aquaculture based on sea surface temperatures and depths below sea level. The goal is to provide insights into potential locations for expanding marine aquaculture operations. Additionally, the end of the rmarkdown includes a function, 'analyze_species_suitability', allowing users to analyze the suitability of EEZs for different species. Users provide the species name and the preferred temperature and depth ranges as inputs to generate maps of total suitable area and percent suitability.

Aditionally, this repository contains a blog style .rmd and .html post to display the contents of the study in a different format!

## Background
Marine aquaculture, as defined by the [National Oceanic and Atmospheric Administration](https://www.fisheries.noaa.gov/insight/marine-aquaculture#:~:text=Marine%20aquaculture%20provides%20a%20domestic,supports%20our%20wild%20fisheries%20production.), encompasses the comprehensive processes of breeding, rearing, and harvesting aquatic plants and animals. The critical role of seafood as a global protein source for over 3 billion people is evident, yet the United States faces a significant seafood deficit, importing more than 60% of its consumption, resulting in a shortfall exceeding $16 billion. Thus, as marine aquaculture has the ability to boost food production, create economic opportunities and boost local economies, and can help keep waterways clean, the implementation of additional marine aquacultures in the United States should be seriously considered. This analysis centers on pinpointing the most suitable Economic Exclusive Zones,  regions where coastal nations posess authority over living and non-living resources, off the West Coast of the United States for developing marine aquacultures, with a specific emphasis on oysters — a proven success in U.S. aquaculture ventures. 

## Data
The analysis uses data from various sources :
- Sea Surface Temperatures: NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1.
- Bathymetry: General Bathymetric Chart of the Oceans (GEBCO).
- Economic Exclusive Zones: Data collected from Marineregions.org.

While the data files are too large to be included in this repository, and thus were omitted using gitignore, the zipped data can be downloaded from [here](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view?usp=sharing).

## Credit
This analysis is based on materials developed by Ruth Oliver at UC Santa Barbara and was conducted as apart of the course EDS 223: Geospatial Analysis and Remote Sensing.

## Repository and Zipped Data Contents

<pre>
  MarineAquaSuitability
    │   README.md
    │   Rmd/Proj files   
    │   knitted .html 
    │   blog post .rmd and .html
    │   gitignore
    │
    └───data
        │   wc_regions_clean.shp
        │   depth.tif
        │   average_annual_sst_2008.tif
        │   average_annual_sst_2009.tif        
        │   average_annual_sst_2010.tif        
        │   average_annual_sst_2011.tif
        │   average_annual_sst_2012.tif      
</pre>

