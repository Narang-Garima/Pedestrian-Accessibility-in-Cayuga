# Pedestrian-Accessibility-in-Cayuga
This project focuses on evaluating pedestrian accessibility in Cayuga, aiming to identify and visualize areas that are safer and more walkable for pedestrians. Using a combination of Python and Power BI, the project introduces custom metrics and interactive visualizations to assist in walkability assessments and urban planning.

# Key Objectives
-Merge and clean road network datasets (edges and nodes)
-Handle missing data and ensure consistency
-Develop scores for Busy Roads and Pedestrian Friendliness
-Visualize findings using Python (Folium) and Power BI

# Data Preparation
1. Combined two datasets:
    -Edges (road segments)
    -Nodes (intersections and end points)
2. Cleaned and formatted columns for consistency
3. Addressed missing values by:
    -Imputing missing street names using nearby nodes
    -Estimating lane counts based on road type

# Feature Engineering

  ## Calculated Busy Score
  ## Calculated Pedestrian-Friendly Score

These scores were assigned to each road segment to evaluate overall pedestrian safety.

#  Visualizations
1. Python (Folium Map)
  Created an interactive map centered on Cayuga
  Roads were color-coded by Pedestrian-Friendly Score
  Helped identify high- and low-safety areas visually

2. Power BI Dashboards
    Maps: Showed geospatial safety score distribution
    Bar/Line Charts: Analyzed road types, busyness, one-way routes, etc.
    Filters: Enabled users to interactively explore areas by criteria

# Tools & Technologies
Python (Pandas, Folium)
Power BI
Jupyter Notebook
CSV/GeoJSON Files

# Results
  ## Developed a reliable system to score and visualize walkability
  Interactive tools make it easy for users or urban planners to identify safer walking routes
  The methodology is scalable to other cities or neighborhoods


