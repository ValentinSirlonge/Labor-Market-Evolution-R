# Labour Market Dashboard
This project presents an interactive dashboard to explore trends in the labour market using **OECD data**.  
Built with **R Shiny** and **Plotly**, the dashboard analyzes employment, unemployment, skill demands, and average wages across countries and age groups.

<p align="center">
  <img src="https://cdn.corporatefinanceinstitute.com/assets/labor-market.jpeg" 
       alt="Labour Market" 
       width="400"/>
</p>


## Project Overview
- **Objective**: Build an interactive R Shiny dashboard for the OECD to visualize key labour market indicators.
- **Context**: Created as part of an individual project for the course *Visualization & Dashboards* with LISER / BSB.
- **Data Source**: OECD datasets including:
  - Labour force population
  - Employment rates
  - Unemployed population
  - Skills demand
  - Average wages


## Dashboard Structure
### 1. **Labour Market**
- Visualizes:
  - Labour force size
  - Employment rate
  - Unemployment population
- Filters:
  - Year range (slider)
  - Age group (checkbox)
  - Country (dropdown)

### 2. **Skills Demand**
- Interactive column chart
- Filters by:
  - Country → shows skill demand by type
  - Skill → shows distribution across countries

### 3. **Average Wages**
- Trend plot of average wages over time
- Filters:
  - Year range
  - Country
