# US-Landfill-Gas-to-energy-analysis documentation

### Project Overview
This work analyses the environmental and energy-generation potential of landfill-based renewable projects, highlighting their role in climate change mitigation and sustainable energy policy planning. By analyzing different aspects of the data, valueable insights were highlighted for stakeholders, including policymakers, environmental planners, and renewable energy developers, in advancing more efficient and impactful landfill gas utilisation strategies.

### Data Sources
US Landfills & LFG Energy Dataset: This data was sourced from Kaggle platform
  [Downoload here](https://www.kaggle.com/datasets/mehmetisik/working-file)

  ### Tools

  - Pandas- Data Cleaning and preparation
  - Matpotlib - Data Visualization
  - Seaborn - Data Visualization

### Data Cleaning/Preparation

In the initial data cleaning process, I performed the following tasks:
1. Missing entries in critical columns like the actual MW generation, were inspected and removed to provide for a more accurate result.
2. Duplicate landfill records were searched, but there were none to be removed.
3. Column names were standardized to lowercase and snake case for consistency.
4. Additional columns such as project age (based on current year) and the gas utilization rate were calculated to aid further analysis

### Exploratory Data Analysis
Analysis was Divied into two aspects: Descriptive statistics, and categorical analysis. They were carried out to answer the following questions:

- How are landfills and their gas recovery projects distributed across the U.S., and what patterns emerge across states or ownership types?

- What are the key physical and operational characteristics of U.S. landfills?

- What is the scale and nature of landfill gas-to-energy projects?

- How much methane is recovered, used, or flared, and what is the environmental benefit of these efforts?

- What factors influence project efficiency and landfill performance?

### Results/Findings
1. The landfills are distributed unevenly across states, with some states like California, Michigan, and New York having the highest concentrations. 
2. The energy generation potential varies significantly by state. States with a higher number of landfill projects generally produce more energy, though this trend isn't perfectly linear. California, Pennsylvania, and Michigan emerged as top contributors to energy generation.
3. States with high energy output also tended to have high emission reductions, though this relationship might vary based on gas capture and utilisation efficiencies.
4. Analysis revealed a 0.64 correlation between the LFG gas collected and the energy generated and also a 0.64 correlation between energy generated and direct emissions reduced.
   
   ![Energy generation vs emissions avoided](https://github.com/user-attachments/assets/4e632aa0-34f1-45cb-ab01-a0c22199648b)

6. A more positive relationship is discovered when an analysis of the energy flow to the project is carried out. There is a 0.96 correlation between the LFG gas flow to the project and energy generation.
   
   ![Lfg flow to project](https://github.com/user-attachments/assets/d20697ff-2dd9-4c91-beec-bf689f761292)

### Recommendations 

The following recommendations were made, based on the analysis:
1. States with a high number of landfill sites but low energy generation outputs should be evaluated for the underutilization of gas resources. Targeted investment and technical audits should be conducted to identify bottlenecks such as ageing infrastructure, inefficient collection systems, or regulatory delays.
2. Correlation results indicate a slightly strong relationship between landfill gas collected and energy generated. Improving gas collection efficiency directly translates to higher energy yields. This can be achieved by upgrading piping systems, sealing cover layers, and monitoring gas flow rates.
3. States that contribute significantly to emissions but generate less energy from LFG should be targeted for emission-reduction programs. 
4. States with a high amount of landfill waste but low energy generation outputs should be evaluated for the underutilization of resources. Targeted investment and technical audits should be conducted to identify bottlenecks such as ageing infrastructure, inefficient collection systems, or regulatory delays.
