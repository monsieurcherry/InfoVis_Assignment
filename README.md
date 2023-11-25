# `food_consumption.csv`
This is the main dataset for this assignment. It contains the food consumption and CO2 emission rates for each country, taken from the [Tidy Tuesday 2020 (week 8)](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-02-18/readme.md). 

### Dataset Variables

| Variable          | Class      | Description                       |
|-------------------|------------|-----------------------------------|
| country           | character  | Country Name                      |
| food_category     | character  | Food Category                     |
| consumption       | double     | Consumption (kg/person/year)      |
| co2_emission      | double     | Co2 Emission (Kg CO2/person/year)|

# `world_population.csv`
This dataset contains the world population by country, found on [Kaggle](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset). The original data comes from the [World Population Review](https://worldpopulationreview.com/), which is a private, for-profit organisation dedicated to providing current and accurate global population data and demographic information.

### Dataset Variables

| Variable                      | Description                                           |
|-------------------------------|-------------------------------------------------------|
| Rank                          | Rank by Population                                    |
| CCA3                          | 3 Digit Country/Territories Code                     |
| Country/Territories           | Name of the Country/Territories                       |
| Capital                       | Name of the Capital                                   |
| Continent                     | Name of the Continent                                 |
| 2022 Population               | Population of the Country/Territories in 2022         |
| 2020 Population               | Population of the Country/Territories in 2020         |
| 2015 Population               | Population of the Country/Territories in 2015         |
| 2010 Population               | Population of the Country/Territories in 2010         |
| 2000 Population               | Population of the Country/Territories in 2000         |
| 1990 Population               | Population of the Country/Territories in 1990         |
| 1980 Population               | Population of the Country/Territories in 1980         |
| 1970 Population               | Population of the Country/Territories in 1970         |
| Area (km²)                    | Area size of the Country/Territories in square km      |
| Density (per km²)             | Population Density per square km                      |
| Growth Rate                   | Population Growth Rate by Country/Territories         |
| World Population Percentage   | Population Percentage by each Country/Territories    |

For my assignment, I incorporated the `Continent` and `2020 Population` variables into my main dataset (`food_consumption.csv`) through the `transform` operation based on the common country column.
