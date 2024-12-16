# The Economic Influence of Billionaires

**Data Wrangling Project by Charlie Doubet & Matthew Riedl**

## Introduction

Money often equates to power, but does it also translate to economic influence? This project investigates whether the presence of billionaires in a country correlates with key economic indicators. We aim to explore how billionaire wealth may impact a country's GDP growth and unemployment rate using datasets from various sources. Specifically, we will analyze data on GDP percentage growth per country, unemployment rates, and billionaire demographics to assess any economic influence that the number of billionaires might have on a country’s economic health.

## Data Sources

Our analysis utilizes three primary datasets:

1. **The Complete World Billionaire List**  
   - **Source**: Kaggle
   - **Link**: https://www.kaggle.com/datasets/guillemservera/forbes-billionaires-1997-2023
   - **Description**: Every billionaire per year since 1997, including details like rank, net worth, industry, and country. This CSV file will be cleaned to build a year-by-year profile of billionaires globally from the past 5 years.

2. **Real GDP Growth Per Country**  
   - **Source**: MacroTrends  
   - **Link**: https://www.macrotrends.net/global-metrics/countries/ranking/gdp-growth-rate
   - **Description**: Annual GDP growth rate for each country over the past 5 years. This data will be scraped to create a dataframe with each countires GDP change from year-to-year.

3. **Unemployment Rates Per Country**  
   - **Source**: World Bank  
   - **Link**: https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS
   - **Description**: Yearly unemployment rates by country for the last 20 years, providing insights into workforce health across economies.

## Data Structure

| Field              | Type       | Source         | Description                                                         |
|--------------------|------------|----------------|---------------------------------------------------------------------|
| `year`             | Text       | All            | Year of the billionaire, GDP, and unemployment data                 |
| `name`             | Text       | Kaggle         | Name of the billionaire                                             |
| `net_worth`        | Numeric    | Kaggle         | Net worth of the billionaire                                        |
| `industry`         | Text       | Kaggle         | Industry where the billionaire obtained their wealth                |
| `country`          | Text       | All            | Country of residence for the billionaire                            |
| `gdp_growth`       | Numeric (%)| MacroTrends    | Annual GDP growth rate per country                                  |
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

## Folders in my Github
- **Assets**: This is used for any additonal information that doesn't include data (information regarding the project).
- **Code**: This folder includes folders for my jupyter notebooks and python scrypts
- **Data**: This folder includes my raw and finalyzed data.
- **Results**: This folder is used for my final PowerPoint and any visualizations/graphs from the final results.
