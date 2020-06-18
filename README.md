# World Development Visualization by M. Raza Khalid Saleemi
## Scatter Plot "Life Expectancy" vs " GDP per capita" with Population
Analyzing World Development with year from 1900 to 2018. Here development of the world is analyzed by two main features "Life Expectancy" and "GDP per capita".

## Tools and Languages Used
- Python3 (3.7.4)
- Jupyter Notebook

## Code Description
### Importing Libraries
- pandas
- numpy
- matplotlib.pyplot
- matplotlib.lines
- pycountry_convert
- PIL
- imageio
- datetime

### Required Data Extraction
Source: https://www.gapminder.org/data/

Extracted data into four "comma seperated files" (.csv) files:
- population_total.csv
- income_per_person_gdppercapita_ppp_inflation_adjusted.csv
- life_expectancy_years.csv
- gapminder.csv ( for extracting countries data)

### Exploratory Data Analysis
- Matching year in all data files
- Matching countries
- Adjusting sequence of countires data
- Building new Dataframe of the adjusted/required data

### Visualization
- Adjusting parameters for displaying Scatter plot
- Creating images of the Plots
- Creating .gif file using the images created

### Author Info:
#### [Muhammad Raza Khalid Saleemi](https://www.linkedin.com/in/muhammad-raza-khalid-saleemi/)

### Acknowledgments:
- [Dice Analytics](https://diceanalytics.pk/)
