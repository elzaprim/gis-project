# Palm Oil Fire Risk Analysis

This project analyzes fire hotspot risks around palm oil supply chain locations using satellite-based fire detection data.

The analysis aims to evaluate potential fire exposure for palm oil supply chain entities, including:

* Estates
* Mills
* Vendors

By identifying fire hotspots near these locations, the project supports environmental risk assessment and sustainability monitoring.

## Data Source

Satellite fire detection data was downloaded from NASA FIRMS.

Dataset details:

* Data Source: VIIRS Active Fire
* Satellite Sensors:

  * VIIRS J1 (NOAA-20)
  * VIIRS SUOMI NPP
* Collection: C2
* Area of Interest: Indonesia
* Time Period: January 1, 2020 – January 31, 2026
* Output Format: CSV

These datasets provide near-real-time detection of thermal anomalies (active fires) observed by satellite sensors.

## Analysis Overview

The workflow includes:

1. Importing and preprocessing satellite fire detection data.
2. Filtering fire hotspots within Indonesia.
3. Spatial analysis to identify fire events near:
   * Palm oil estates
   * Mills
   * Vendor locations
4. Generating fire exposure indicators to support risk scoring.

