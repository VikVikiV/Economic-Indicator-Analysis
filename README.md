# Economic Indicator Analysis

**Analysing Country's Population, GDP, and Exports**  
 
This project involves the collection, cleaning, and analysis of economic indictors; population, GDP, and exports. The processes performed include web scraping, statistical analysis, and integration to MongoDB and proivde insights in relation to the trends found in economic indicators and the relationships they have with eachother.
 
## Features  

- **Automated Web Scraping**: Extracts data from Wikipedia tables for list of countries population, GDP (nominal), and order by exports.  

- **Data Cleaning**: Handles missing values, duplicates, and type conversions for reliable datasets.  

- **Statistical Analysis**: Calculates summary statistics (mean, median, mode) and ranks countries by key metrics.

- **MongoDB Integration**: Stores cleaned datasets in a NoSQL database for querying and analysis.
 
## Academic Assessment  

A detailed analysis of the project's methodology, results, and limitations is accessible in the following [paper](Docs/BBIM612_A1_Report_764706455_1.pdf).  
 
## Data Sources  

This project extracts data from the following Wikipedia pages:  
 
1. **Country Exports**:  

   [List of Countries by Exports](https://en.wikipedia.org/wiki/List_of_countries_by_exports)  

   - Scraped table: Exports of goods and services (US$ million) by country.  
 
2. **Country Population**:  

   [List of Countries and Dependencies by Population](https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population)  

   - Scraped table: List of countries and territories by total population.
 
3. **Country GDP (Nominal)**:  

   [List of Countries by GDP (Nominal)](https://en.wikipedia.org/wiki/List_of_countries_by_GDP_(nominal))  

   - Scraped table: GDP forecast or estimate (million US$) by country  
 
---
 
### Notes  

- **Dynamic Scraping**: Data is captured directly from Wikipedia at runtime. Results may vary if Wikipedia’s table structures change.  

- **Attribution**: All data is publicly available under Wikipedia’s [Creative Commons Attribution-ShareAlike License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License).   
 
## Setup  

### Prerequisites  

- Python 3.8+  

- MongoDB (local or cloud instance) 
 
