---
name: DATA VISUALIZATION FINAL PROJECT
tools: [Python, HTML, vega-lite]
image: assets/pngs/assignment8.png
description: This is a visualization for Assignment 8.2 
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# DATA VISUALIZATION FINAL PROJECT


### Description of Dashboard 1: Flood Risk Analysis

This interactive dashboard is designed to explore and present flood risk data across the U.S. states. It integrates various types of visualizations to provide comprehensive insights into the distribution of flood risks.

#### Features

- **State Selection Dropdown**: Allows the user to select either a specific state or 'All' states for aggregate data visualization. This feature facilitates targeted analysis of flood risk data.

- **Visualizations Included**:
  - **Pie Chart**: Displays the proportionate distribution of Minor, Moderate, and Major flood risks, offering an immediate visual assessment of the severity of risks in the selected area.
  - **Histograms**: There are three histograms showing the frequency distributions of Minor, Moderate, and Major flood risks. These plots help understand how commonly different levels of risks occur and their variability within the selected data scope.
  - **Bar Plot**: Compares the top 10 locations within the chosen area by their flood risk levels, displayed in a stacked format. This visualization highlights areas with heightened risks, which can be crucial for prioritizing flood management and mitigation efforts.

#### Interactivity

- The dashboard updates dynamically based on the state selected from the dropdown menu, making it a powerful tool for real-time data exploration. All visualizations reflect the current selection, ensuring that users have the latest information at their fingertips.

#### Usage

This tool is invaluable for policymakers, urban planners, and disaster management professionals looking to develop informed strategies to mitigate flood risks. It is also a useful educational resource for the public and researchers interested in environmental management.



### Description of Dashboard 2: Interactive Flood Risk Mapping

This dashboard utilizes interactive maps to visualize specific flood risks across various locations in U.S. states. It allows users to select flood risk levels and states to see real-time geographic distributions of risks.

#### Features

- **Interactive Map Visualization**: Utilizes Folium for dynamic mapping, providing a geographical representation of flood risk data.
  
- **Customizable Viewing Options**:
  - **Flood Risk Level Dropdown**: Users can choose to view Minor, Moderate, or Major flood risks. This dropdown allows for specific risk level analysis.
  - **State Dropdown**: Users can select a specific state to focus the map's view, enabling more localized analysis of flood risks.

- **Marker Visualization**:
  - **Markers on Map**: Depending on the selected risk level and state, markers are placed on the map in colors representing the severity of flood risks:
    - Dark Blue for Major Flood Risks (threshold >= 0.06)
    - Blue for Moderate Flood Risks (threshold >= 0.075)
    - Light Blue for Minor Flood Risks

#### Interactivity

- The map updates dynamically based on user selections from the dropdown menus. This interactivity allows for tailored visualization and aids in pinpointing high-risk areas more effectively.

#### Usage

This tool is particularly useful for environmental analysts, emergency planners, and governmental agencies engaged in flood management. It helps in planning interventions and understanding spatial distributions of flood risks.


#### Accessing the dataset and analysis

To view the dataset used in the analysis, click the bottom-left button. To review the analysis results, click the bottom-right button to access the Jupyter notebook.

<div class="left">
{% include elements/button.html link="https://water.weather.gov/resources/tmp/long_range_river_flood_risk_data.csv" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/Rushabhnm/rushabh_dataviz/blob/main/python_notebooks/DATA_VIZ_FINAL.ipynb" text="The Analysis" %}
</div>
