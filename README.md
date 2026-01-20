# Urban Sanitation Impact on Restaurant Reviews

## Overview
This project analyzes the relationship between neighborhood cleanliness and Yelp restaurant ratings by linking Yelp review data with Philadelphia 311 sanitation complaint records. This analysis integrates over 600,000 Yelp reviews with multi year Philadelphia 311 sanitation records using geospatial entity linking.

## Data

This project uses three primary data sources.

- Yelp Open Dataset including business metadata and reviews
- Philadelphia 311 Service Request data
- Philadelphia neighborhood boundary geospatial data

All data sources are publicly available and are not included in this repository due to size and licensing considerations.

To reproduce the analysis:

1. Download the Yelp Open Dataset from https://www.yelp.com/dataset
2. Download Philadelphia 311 service request data from the City of Philadelphia Open Data Portal
3. Download Philadelphia neighborhood boundary shapefiles from the City of Philadelphia Open Data Portal
4. Place the extracted files into a local `data/` directory following the structure referenced in the notebooks

## Methodology
- Entity linking between restaurants and neighborhood polygons
- Feature engineering of sanitation metrics
- Predictive modeling using regression and tree-based models
- Model interpretation and validation

## Key Results
- Identified statistically meaningful relationships between sanitation complaints and review sentiment
- Demonstrated tradeoffs between interpretability and predictive performance

## Project Structure
- `yelpCleanliness_final.ipynb` Final analysis and modeling
- `yelpCleanliness_difficulty.ipynb` Technical deep dive
- `yelpCleanliness_presentation.pdf` Summary presentation

## Contributions
This project was completed as part of CIS 5450 Big Data Analytics course.  
