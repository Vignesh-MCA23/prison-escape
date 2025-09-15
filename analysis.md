# Analysis of Helicopter Prison Escapes

## Overview
This project analyzes data on helicopter prison escapes sourced from Wikipedia. The analysis includes data extraction, cleaning, exploration, and visualization to uncover trends and patterns in helicopter prison escapes over time.

## Data Collection
- Data was scraped from the Wikipedia page: [List of helicopter prison escapes](https://en.wikipedia.org/wiki/List_of_helicopter_prison_escapes)
- The data includes columns: `Date`, `Prison name`, `Country`, `Succeeded`, `Escapee(s)`, and `Details`
- The `Details` column was dropped for simplicity

## Data Cleaning
- Converted the `Date` column to datetime format
- Extracted the `Year` from the `Date` column for time-based analysis
- Created additional features: `Month` and `DayOfWeek` for more granular analysis

## Key Findings

### 1. Escapes by Year
- The number of helicopter prison escapes varies significantly by year
- The years with the most escapes are:
  - 1986, 2001, 2007, 2009: 3 escapes each
  - 1981, 1985, 1988, 1989, 1992, 2000, 2002, 2005, 2013: 2 escapes each
- Recent years show fewer escapes, with only 1 escape in 2016, 2018, and 2020

### 2. Escapes by Month
- The distribution of escapes across months is relatively even
- Some months show slightly higher activity, but no strong seasonal pattern emerges

### 3. Escapes by Day of Week
- The analysis shows escapes occurring on all days of the week
- Wednesday appears to be the most common day for helicopter prison escapes

## Visualizations
- Created bar charts showing:
  - Number of escapes per year
  - Number of escapes per month
  - Number of escapes per day of the week

## Limitations
- The dataset is relatively small (limited number of helicopter prison escapes)
- Some dates might be approximate or missing
- The success rate analysis wasn't included in this initial exploration

## Future Work
- Analyze success rates of escape attempts by country and year 
- Investigate the most common escape methods from the `Details` column
- Examine relationships between prison security levels and escape success
- Create interactive visualizations for more detailed exploration

## Conclusion
Helicopter prison escapes, while dramatic, are relatively rare events. The data shows sporadic occurrence with some concentration in certain years but no strong seasonal or weekly patterns. The analysis provides a foundation for further investigation into the factors contributing to these unusual escape attempts.