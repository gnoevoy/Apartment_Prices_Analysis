![cover](https://github.com/gnoevoy/Apartment_Prices_Analysis/assets/43414592/026cc005-ada7-47a5-a5f0-f069bb2b9255)

This project shows insights of the apartment markets in the Polish cities of Gdansk and Gdynia.
The focus is on analyzing prices, both for sale and rent, with the aim of providing insights that support informed decision-making for potential tenants and buyers.

### Objective
The main goal of this analysis is to show to different user groups – students and families – by offering them clear insights to guide their decisions in the housing market.

### As a Data Analyst, I took the following steps:
1. Collecting and processing apartment sales and rental data for Gdansk and Gdynia.
2. Performing exploratory data analysis, including distribution, correlations, and monthly trend analysis.
3. Developing visualizations and interactive reports using BI tool.

<br>

## [Power BI Presentation](https://github.com/gnoevoy/Apartment_Prices_Analysis/blob/main/Presentation.md)
## [Jupyter Notebook](https://github.com/gnoevoy/Apartment_Prices_Analysis/blob/main/apartment_prices.ipynb)

<br>

## Dataset Overview

The dataset includes information on apartments for sale and rent in Poland's 15 biggest cities. The information is taken from local apartment sale websites and gathered every month. It covers the period from August 2023 to December 2023.

### Files

| Table | Description |
| --- | --- |
| `apartments_pl_YYYY_MM` | Monthly snapshot of sell offers |
| `apartments_rent_pl_YYYY_MM` | Monthly snapshot of rent offers |

### Data Fields

| Column | Description |
| --- | --- |
| `city` | The name of the city where the property is located |
| `type` | Type of the building |
| `squareMeters` | The size of the apartment in square meters |
| `rooms` | Number of rooms in the apartment |
| `floor` / `floorCount` | The floor where the apartment is located and the total number of floors in the building |
| `buildYear` | The year when the building was built |
| `latitude`, `longitude` | Geo coordinates of the property |
| `centreDistance` | Distance from the city centre in km |
| `poiCount` | Number of points of interest in a 500m range from the apartment |
| `[poiName]Distance` | Distance to the nearest point of interest (e.g., schools, clinics) |
| `ownership` | The type of property ownership |
| `condition` | The condition of the apartment |
| `has[features]` | Whether the property has key features (e.g., parking space, balcony, elevator, security, storage) |
| `price` | Offer price in Polish Zloty (sale offers: sale price, rent offers: monthly rent) |

<br>

## Additional Links
- [Dataset](https://github.com/gnoevoy/Apartment_Prices_Analysis/blob/main/Dataset.zip)
- [Power BI file](https://github.com/gnoevoy/Apartment_Prices_Analysis/blob/main/apartment_prices.pbix)
- [Project Repository](https://github.com/gnoevoy/Apartment_Prices_Analysis/tree/main)
