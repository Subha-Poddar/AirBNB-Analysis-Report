
---

# Airbnb NYC Analysis Report(Tableau)

## Project Overview

This project provides an analysis of Airbnb listings in New York City using the **2019 Airbnb NYC dataset**. The analysis was performed using **Tableau**, with visualizations created to explore trends, pricing patterns, and neighborhood dynamics.

Link of the dataset: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data?resource=download

### Dataset

The dataset consists of 48,895 Airbnb listings in New York City, and contains various fields, including:

- `id`: Unique identifier for each listing
- `host_id`: Host's unique identifier
- `neighbourhood_group`: The main borough or group the listing belongs to (e.g., Manhattan, Brooklyn)
- `neighbourhood`: The specific neighborhood of the listing
- `latitude`, `longitude`: Coordinates of the listing
- `room_type`: Type of room offered (e.g., Entire home/apt, Private room)
- `price`: Price per night in USD
- `minimum_nights`: Minimum stay requirement
- `number_of_reviews`: Total reviews received
- `last_review`: Date of the last review
- `availability_365`: Number of available booking days per year

## Objective

The objective of this analysis is to uncover patterns in:

- Price distribution across different neighborhoods and room types
- Availability trends throughout the year
- Review frequency and host activity

## Key Insights:

**Room Types**: Entire homes/apartments make up the largest portion of listings, followed by private rooms, with smaller contributions from shared rooms.

**Top Boroughs**: Manhattan and Brooklyn dominate the Airbnb market, with Manhattan commanding the highest prices and demand.

**Pricing Trends**: The average price per night varies significantly across boroughs, with Manhattan being the most expensive and the Bronx offering more affordable stays.

**Availability**: Listings in Manhattan are often booked throughout the year, while certain neighborhoods in Brooklyn show seasonal trends.

**Host Analysis**: Many hosts manage multiple listings, with some operating as mini-property managers, particularly in high-demand areas.

## KPIs
- Total Hosts
- Total Neighborhoods in NYC
- Average Reviews per Month
- Total Reviews

## Visualizations

The Tableau workbook (`AirBNB analysis Report.twbx`) includes interactive dashboards and charts that cover:

- Average price Based on the Room types
- Total Bookings per Month
- Percentage of neighborhood group
- Top 10 Host in terms of reviews 
- Total Bookings by neighborhood group and room type
- Year-wise Reviews
- Avg Price based on neighborhood groups
- Average price(bar plot)
- Avg Reviews Per Month

## How to Run the Project

1. Download the dataset: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data?resource=download
2. Open the Tableau workbook using Tableau Desktop.
3. Explore the interactive dashboards to gain deeper insights into the Airbnb market in NYC.

## Conclusion

This project helps researchers understand the dynamics of the NYC Airbnb market. From room types to neighborhood pricing trends, the analysis sheds light on various factors influencing Airbnb activity in New York City.

---
