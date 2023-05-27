## San Francisco Housing Data Analysis

This repository contains Python code for analyzing and visualizing housing data in San Francisco. The code utilizes the `pandas`, `hvplot.pandas`, and `pathlib` libraries to perform data manipulation, interactive plotting, and file path operations.

### Code Overview

1. **Data Loading**
   - The code imports the required libraries: `pandas`, `hvplot.pandas`, and `pathlib`.
   - It loads the San Francisco neighborhood census data from a CSV file.

2. **Housing Units by Year**
   - The code calculates the average number of housing units per year in San Francisco.
   - It creates a bar plot to visualize the housing units per year.

3. **Prices per Square Foot by Year**
   - The code calculates the average prices per square foot by year in San Francisco.
   - It creates a line plot to visualize the gross rent/sale price per square foot over the years.

4. **Prices per Year by Neighborhood**
   - The code calculates the average prices per year by neighborhood in San Francisco.
   - It creates a line plot for each neighborhood to visualize the gross rent/sale price per square foot over the years.

5. **Neighborhood Information and Plot**
   - The code loads a CSV file containing neighborhood locations.
   - It merges the neighborhood location data with the average values of each neighborhood.
   - Finally, it creates a scatter plot on a map to visualize the housing data by neighborhood.

