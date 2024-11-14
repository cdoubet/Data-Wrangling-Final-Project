# Data Folder


## Folders

### Raw Data
Original, unmodified data after downloading, scraping, etc

### Final Data
Data after all cleaning, processing, and analyzing

---

## Data Dictionary
| Field             | Type         | Source         | Description                                                                                     |
|-------------------|--------------|----------------|-------------------------------------------------------------------------------------------------|
| year              | Text         | All            | Year of the billionaire, GDP, and unemployment data.                                            |
| name              | Text         | Areppim        | Name of the billionaire.                                                                        |
| net_worth         | Numeric      | Areppim        | Net worth of the billionaire.                                                                   |
| industry          | Text         | Areppim        | Industry in which the billionaire obtained their wealth.                                        |
| country           | Text         | All            | Country where the billionaire resides, with applicable GDP growth rate and unemployment rate.   |
| gdp_growth        | Numeric (%)  | IMF excel      | Year-by-year GDP growth rate per country.                                                       |
| unemployment_rate | Numeric (%)  | World Bank excel | Year-by-year unemployment rate per country.                                                   |
