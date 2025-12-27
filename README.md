# Atmospheric Variables and Solar Irradiance Dataset

## Overview
This repository contains merged atmospheric and solar irradiance datasets from three SURFRAD (Surface Radiation Budget Network) stations across the United States. The data combines ground measurements with satellite observations (GOES-16 and AURA) and reanalysis data (MERRA2), providing a comprehensive multi-source dataset for solar energy prediction or forecasting, atmospheric research, and climate studies.

**Time Period:** July 2023  
**Temporal Resolution:** 5-minute intervals  
**File Format:** CSV with timestamp index

## Station Locations

### Colorado (Table Mountain)
- **Latitude:** 40.12498°N
- **Longitude:** 105.23680°W
- **Elevation:** 1,689 meters
- **Timezone:** America/Denver (UTC-6, DST included)
- **File:** `colorado_merged_all_var.csv`

### Illinois (Bondville)
- **Latitude:** 40.05192°N
- **Longitude:** 88.37309°W
- **Elevation:** 213 meters
- **Timezone:** America/Chicago (UTC-5, DST included)
- **File:** `illinois_merged_all_var.csv`

### Pennsylvania (Penn State)
- **Latitude:** 40.72012°N
- **Longitude:** 77.93085°W
- **Elevation:** 376 meters
- **Timezone:** America/New_York (UTC-4, DST included)
- **File:** `pennsylvania_merged_all_var.csv`

## Data Columns

### SURFRAD Variables
Ground-based measurements from the NOAA Surface Radiation Budget Network:

- **SURFRAD_GHI**: Global Horizontal Irradiance (W/m²) - Total solar radiation received on a horizontal surface

### AURA Satellite Variables
Atmospheric composition measurements from NASA's Aura satellite (OMI instrument):

- **AURA_NO2**: Nitrogen Dioxide column density (Dobson Units)
- **AURA_O3**: Ozone column density (Dobson Units)

### MERRA-2 Reanalysis Variables
Atmospheric parameters from NASA's Modern-Era Retrospective analysis for Research and Applications, Version 2:

- **MERRA2_ALBEDO**: Surface albedo (dimensionless)
- **MERRA2_CLDTOT**: Total cloud fraction (dimensionless)
- **MERRA2_TAUTOT**: Total aerosol optical thickness at 550 nm (dimensionless)
- **MERRA2_TQV**: Total precipitable water vapor (kg/m²)
- **MERRA2_TO3**: Total column ozone (Dobson Units)
- **MERRA2_PS**: Surface pressure (Pa)
- **MERRA2_TOTSCATAU**: Total scattering aerosol optical thickness at 550 nm (dimensionless) 
- **MERRA2_TOTEXTTAU**: Total extinction aerosol optical thickness at 550 nm (dimensionless) 
- **MERRA2_TOTANGSTR**: Total aerosol Ångström parameter (440-870 nm) (dimensionless) 

### GOES-16 Satellite Variables
Derived products from NOAA's Geostationary Operational Environmental Satellite:

- **GOES_TPW**: Total Precipitable Water (mm) - Atmospheric water vapor content
- **GOES_LSA**: Land Surface Albedo (dimensionless) - Surface reflectivity
- **GOES_AOD**: Aerosol Optical Depth at 550 nm (dimensionless) - Atmospheric aerosol loading

## Data Sources

### SURFRAD Network
**Provider:** NOAA Global Monitoring Laboratory  
**Website:** https://gml.noaa.gov/grad/surfrad/  
**Description:** High-quality ground-based measurements of surface radiation budget components supporting satellite validation and climate research.

### NASA Aura Satellite
**Provider:** NASA Goddard Space Flight Center  
**Instrument:** Ozone Monitoring Instrument (OMI)  
**Website:** https://aura.gsfc.nasa.gov/  
**Description:** Polar-orbiting satellite measuring atmospheric composition including trace gases and aerosols.

### MERRA-2 Reanalysis
**Provider:** NASA Global Modeling and Assimilation Office  
**Website:** https://gmao.gsfc.nasa.gov/reanalysis/MERRA-2/  
**Description:** Atmospheric reanalysis combining observations with numerical weather prediction models.

### GOES-16 Satellite
**Provider:** NOAA National Environmental Satellite, Data, and Information Service  
**Website:** https://www.goes-r.gov/  
**Description:** Geostationary satellite providing continuous monitoring of atmospheric and surface conditions over the Americas.


---

*Dataset compiled for atmospheric research and solar irradiance prediction studies.*
