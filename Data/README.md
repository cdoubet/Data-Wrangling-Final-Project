# Data Folder


## Folders

### Raw Data
This folder includes our three original, unmodified data after downloading and scraping.

### Final Data
This folder includes the five cleaned and merged datasets that we will use for our project.

---

## Data Dictionary
| Field              | Type       | Source         | Description                                                         |
|--------------------|------------|----------------|---------------------------------------------------------------------|
| `year`             | Text       | All            | Year of the billionaire, GDP, and unemployment data                 |
| `name`             | Text       | Kaggle         | Name of the billionaire                                             |
| `net_worth`        | Numeric    | Kaggle         | Net worth of the billionaire                                        |
| `industry`         | Text       | Kaggle         | Industry where the billionaire obtained their wealth                |
| `country`          | Text       | All            | Country of residence for the billionaire                            |
| `gdp_growth`       | Numeric (%)| MacroTrends    | Annual GDP growth rate per country                                  |
| `unemployment_rate`| Numeric (%)| World Bank     | Annual unemployment rate per country                                |
