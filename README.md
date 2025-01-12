# Gun Violence in the United States (2013-2018)

This project analyzes gun violence incidents in the United States from 2013 to 2018, providing insights into geographic patterns, demographic influences, and other related factors. Using advanced data visualization techniques and statistical analysis, this project seeks to uncover trends and highlight actionable insights.

---

## Dataset
- **Source**: [Gun Violence Archive](https://github.com/VLimbhar22/Gun-Violence-in-United-States--2013-18-)
- **Time Period**: January 2013 - March 2018
- The dataset includes details on incidents, locations, participants, and outcomes.

---

## Objectives
- Analyze the geographic distribution of gun violence incidents across states, cities, and neighborhoods.
- Investigate demographic patterns, including age, gender, and participant roles.
- Identify trends and correlations related to gun violence.

---

## Technologies and Tools
This project is implemented using R and leverages the following libraries:
- **Data Manipulation**: `tidyverse`, `dplyr`
- **Mapping and GIS**: `maps`, `sf`, `leaflet`
- **Data Visualization**: `plotly`, `gridExtra`, `viridis`, `RColorBrewer`
- **Tabular Formatting**: `formattable`

---

## Key Steps
1. **Data Cleaning**:
   - Removed irrelevant columns (e.g., `incident_url`, `address`, etc.).
   - Filtered and transformed data for analysis.

2. **Geographic Analysis**:
   - Visualized the geographic distribution of incidents using shapefiles and mapping libraries like `sf` and `leaflet`.

3. **Visualization**:
   - Created interactive maps and visualizations with `plotly` and `viridis`.
   - Highlighted trends across states and cities using bar charts and choropleth maps.

4. **Statistical Analysis**:
   - Explored relationships between demographic variables and gun violence incidents.

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/VLimbhar22/Gun-Violence-in-United-States--2013-18-
   cd Gun-Violence-in-United-States--2013-18-
