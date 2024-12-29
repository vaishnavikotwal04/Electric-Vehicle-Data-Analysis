# Electric-Vehicle-Data-Analysis
(https://public.tableau.com/app/profile/vaishnavi.kotwal/viz/ElectricVehiclesEVDataAnalysis/Dashboard1)

## Problem Statement
The objective is to analyze the adoption and growth of electric vehicles (EVs) by assessing key metrics, trends, and market patterns. This analysis will focus on Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs), enabling stakeholders to make data-driven decisions regarding technology advancements, policy-making, and market strategies.

## Specific Goals:
#### 1. Market Size and Growth Analysis:

Assess the total number of EVs (BEVs and PHEVs) to understand the overall market landscape.
Evaluate the growth trends from 2010 onwards to gauge adoption over time.

#### 2. Technological Advancements:

Calculate the average electric range of EVs to understand progress in technology and efficiency.
#### 3. Segmentation of BEVs and PHEVs:

Identify the total number of BEVs and PHEVs and calculate their respective percentages within the EV market.
Analyze the dominance of fully electric models versus hybrid models.

#### 4. Geographical and Manufacturer Insights:

Analyze EV distribution by state to identify regions with higher adoption rates.
Identify the top 10 EV manufacturers and models to evaluate market dominance and consumer preferences.

#### 5. Impact of Incentives:

Determine the proportion of EVs eligible for Clean Alternative Fuel Vehicle (CAFV) incentives to understand the effectiveness of policy measures in driving adoption.

## Deliverables:
### Data Visualizations:

1. Line/Area Chart: Growth of EVs by model year (from 2010 onwards).
2. Map Chart: Geographical distribution of EVs by state.
3. Bar Chart: Top 10 EV manufacturers based on total vehicles.
4. Pie Chart: Proportion of EVs eligible for CAFV incentives.
5. Tree Map: Top 10 EV models based on total vehicles.

This analysis will provide actionable insights into EV market trends, helping manufacturers, policymakers, and industry stakeholders to align their strategies with market demands and technological advancements.

# Tableau (Using Technology)

Tableau is an excellent tool for visualizing and analyzing electric vehicle data due to its user-friendly interface, advanced analytical capabilities, and rich visualization features. Here's how Tableau can be used to address the KPIs and problem statement for this analysis:

### 1. Total Vehicles by Model Year (From 2010 Onwards)

Visualization: Line/Area Chart

Purpose: Illustrate the growth trend of EVs (BEVs and PHEVs) over time.

Implementation in Tableau: 
Import the dataset into Tableau.
Use the Model Year as the x-axis and Total Vehicles as the y-axis.
Apply filters to include only data from 2010 onwards.
Customize the chart with color coding for BEVs and PHEVs to differentiate trends.

### 2. Total Vehicles by State

Visualization: Map Chart

Purpose: Display the geographical distribution of EVs across states.

Implementation in Tableau:
Drag the State dimension to the Map view.
Use the Total Vehicles measure to determine the size or intensity of markers on the map.
Apply geographic filters or heatmap layers for better insights.
Include tooltips to show state-wise breakdown of BEVs and PHEVs.

### 3. Top 10 Total Vehicles by Make

Visualization: Bar Chart

Purpose: Highlight the most popular EV manufacturers based on the number of vehicles.

Implementation in Tableau:
Drag the Make field to the x-axis and Total Vehicles to the y-axis.
Sort the data in descending order and limit it to the top 10 manufacturers.
Use color differentiation for BEVs and PHEVs or other vehicle categories.

### 4. Total Vehicles by CAFV Eligibility

Visualization: Pie Chart or Donut Chart

Purpose: Understand the impact of CAFV incentives on vehicle adoption.

Implementation in Tableau:
Use the CAFV Eligibility dimension (Eligible/Not Eligible) as the category.
Use Total Vehicles as the measure to create a proportional chart.
Include percentage labels for a clearer representation of data.

### 5. Top 10 Total Vehicles by Model

Visualization: Tree Map

Purpose: Showcase consumer preferences and popular EV models.

Implementation in Tableau:
Drag the Model field to the Tree Map visualization.
Use Total Vehicles to determine the size of each block.
Apply filters to display only the top 10 models.
Use color coding to distinguish between BEVs and PHEVs.



