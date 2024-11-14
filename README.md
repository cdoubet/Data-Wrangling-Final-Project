# data-analytics-template
BAIS3250_HW5

# The Economic Influence of Billionaires

**Data Wrangling Project by Charlie Doubet & Matthew Riedl**

## Introduction

Money often equates to power, but does it also translate to economic influence? This project investigates whether the presence of billionaires in a country correlates with key economic indicators. We aim to explore how billionaire wealth may impact a country's GDP growth and unemployment rate using datasets from various sources. Specifically, we will analyze data on GDP percentage growth per country, unemployment rates, and billionaire demographics to assess any economic influence that the number of billionaires might have on a country’s economic health.

## Data Sources

Our analysis utilizes three primary datasets:

1. **The Complete World Billionaire List**  
   - **Source**: Areppim Stats  
   - **Description**: Top 500 billionaires per year since 1996, including details like rank, net worth, industry, and country. This data will be scraped and compiled to build a year-by-year profile of billionaires globally.

2. **Real GDP Growth Per Country**  
   - **Source**: International Monetary Fund (IMF)  
   - **Description**: Annual GDP growth rate for each country over the past 20 years. This data will be converted to CSV format for easy integration.

3. **Unemployment Rates Per Country**  
   - **Source**: World Bank  
   - **Description**: Yearly unemployment rates by country for the last 20 years, providing insights into workforce health across economies.

## Data Structure

| Field              | Type       | Source         | Description                                                         |
|--------------------|------------|----------------|---------------------------------------------------------------------|
| `year`             | Text       | All            | Year of the billionaire, GDP, and unemployment data                 |
| `name`             | Text       | Areppim        | Name of the billionaire                                             |
| `net_worth`        | Numeric    | Areppim        | Net worth of the billionaire                                        |
| `industry`         | Text       | Areppim        | Industry where the billionaire obtained their wealth                |
| `country`          | Text       | All            | Country of residence for the billionaire, applicable GDP, and unemployment rate |
| `gdp_growth`       | Numeric (%)| IMF            | Annual GDP growth rate per country                                  |
| `unemployment_rate`| Numeric (%)| World Bank     | Annual unemployment rate per country                                |

## Proposed Analysis

This project aims to answer several research questions:

- Does a high number of billionaires correlate with stable GDP growth for a country? Do fewer billionaires indicate greater economic volatility?
- Is there a relationship between the billionaire population and unemployment rates? Do wealthy individuals in a country signify a healthier job market or potentially high unemployment due to wealth concentration?
- Which countries exhibit the healthiest economies based on GDP growth and low unemployment? Do these countries also have a large number of billionaires?
- Who are the top ten billionaires worldwide, and where do they reside? Are their home countries economically healthy?

## Technologies

- **Jupyter Notebook**: For data scraping and initial data exploration.
- **Visual Studio Code**: For data conversion and preprocessing.
- **Python Libraries**: Pandas, BeautifulSoup, and Matplotlib for data analysis and visualization.


### To do list
---
[ ] task 1  
[ ] task 1  
[ ] task 1  
[ ] task 1  
[ ] task 1  


### Change log
---
- 2024-11-14    CLD     Created a Github Document
- 2024-11-14    CLD     Worked on Scraping Data through 2019