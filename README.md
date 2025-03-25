# Economic Indicator Analysis

**Analyzing Global Education Metrics and Human Development Indices (HDI)**  
 
This project collects, cleans, and analyzes global education data (literacy rates, government spending) and HDI rankings through web scraping, statistical analysis, and MongoDB integration. Designed for data enthusiasts and policymakers, it provides actionable insights into education development trends.
 
## Features  

- **Automated Web Scraping**: Extracts data from Wikipedia tables for literacy rates, education spending (% of GDP), and HDI rankings.  

- **Data Cleaning**: Handles missing values, duplicates, and type conversions for reliable datasets.  

- **Statistical Analysis**: Calculates summary statistics (mean, median, mode) and ranks countries by key metrics.  

- **MongoDB Integration**: Stores cleaned datasets in a NoSQL database for scalable querying and analysis.  
 
## Academic Assessment  

A detailed analysis of this project's methodology, results, and limitations is available in the following [paper](Docs/BBIM612_A1_Report_764706455_1.pdf).  
 
## Data Sources  

This project extracts data from the following Wikipedia pages:  
 
1. **Literacy Rates (PIRLS Study)**:  

   [Progress in International Reading Literacy Study](https://en.wikipedia.org/wiki/Progress_in_International_Reading_Literacy_Study)  

   - Scraped table: Country rankings, average scale scores, and 5-year changes.  
 
2. **Education Spending (% of GDP)**:  

   [List of Countries by Spending on Education](https://en.wikipedia.org/wiki/List_of_countries_by_spending_on_education)  

   - Scraped table: Government education spending as a percentage of GDP.  
 
3. **Human Development Index (HDI)**:  

   [List of Countries by Human Development Index](https://en.wikipedia.org/wiki/List_of_countries_by_Human_Development_Index)  

   - Scraped table: HDI rankings, values, and annual growth rates (2010–2021).  
 
---
 
### Notes  

- **Dynamic Scraping**: Data is fetched directly from Wikipedia at runtime. Results may vary if Wikipedia’s table structures change.  

- **Attribution**: All data is publicly available under Wikipedia’s [Creative Commons Attribution-ShareAlike License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License).   
 
## Setup  

### Prerequisites  

- Python 3.8+  

- MongoDB (local or cloud instance)  
 
### Installation  

1. Clone the repository:  

   ```bash  

   git clone https://github.com/your-username/Education-Development-Analytics.git  

Progress in International Reading Literacy Study)
 
