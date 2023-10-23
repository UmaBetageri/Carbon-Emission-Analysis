## Analyzing the Energy-Related Carbon Emissions in the U.S.

The United States on average produced 6.6 billion metric tons of carbon dioxide equivalent greenhouse gas emissions in 2019. Our goal with this project is to research and evaluate the energy-related carbon emissions (total GHG) across US sectors over the past few years. The emissions from fossil fuels, such as coal, natural gas, and petroleum, are referred to as "energy-related." The "Unites States Energy Information Administration" provided the project with the dataset, which covered the years 1980 through 2019. The information includes more details on sub-sectors within each of the five main sectors (Commercial, Industrial Process, Residential, Transportation, and Electricity) as well as the energy-related carbon emissions in each.

To view all visualizations and further details about the project, kindly visit [Project Website](https://sites.google.com/sdsu.edu/energy-carbon-emissions/){:target="_blank" rel="noopener"}

### Problem Statement
Carbon emissions, sometimes known as greenhouse gases, are the main cause of global warming. This line brought to mind the rising global temperature, the world's population, and the US's partially destroyed ozone layer. As students studying cutting-edge technologies, we feel obligated to be aware of our surroundings. We can surely utilize technology to transform the real world if we can use our analysis to grasp its problems, which is now the case. This is due to the fact that identifying the root of an issue solves half of it. Every living thing on the planet is impacted by a poor environment and contaminated air, water, and soil, regardless of where in the globe one lives. This makes addressing global warming and carbon emissions crucial.

### Tools Used
1) Web Development : Google Sites
2) Visualization : Tableau, ArcGIS
3) Data Preparation : Microsoft Excel

### Dataset
Data for the project was obtained from the Energy Information Administration (EIA) website in the United States. This dataset includes information on energy-related carbon emissions for the five main sectors of transportation, industry, electricity, and residential and commercial buildings from 1980 to 2018. Three main sources account for the majority of energy-related emissions: natural gas, coal, and petroleum. You can download the dataset from following links.

[Emission Data](https://www.eia.gov/environment/emissions/state/){:target="_blank" rel="noopener"}

[Geographical Data](https://developers.google.com/public-data/docs/canonical/states_csv){:target="_blank" rel="noopener"}

### Data Preparaion
Data preparation and cleaning are carried out in sequential steps, with distinct files being made for each set of graphs.
1) Combine information from 50 excel files—one for each state—into one file.
2) Update each state's latitude and longitude.
3) Create separate CSV files containing temporal data for every sector and source.

This repository contains the cleaned and processed data.

### Data Visualizations
Some of the most common visualizations are shown below. 

<img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/2d9871ef-e26f-4afc-92b1-f1bc2bb59a1d' width='400'> <img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/4423bb84-1722-4e85-bff1-0e452b75ab0c' width='350'>


This graph on the left depicts the overall trend in carbon emissions by sector. Our dataset includes five sectors: commercial, transportation, electric power, residential, and industrial. We can see that over decades, the electric power sector has produced the most emissions. The total amount of electricity generated in the United States by the electric power industry from all energy sources was 4.01 trillion kilowatt-hours (kWh), resulting in the emission of 1.55 billion metric tons—1.71 billion short tons—of carbon dioxide (CO2).

The carbon emission "Source-wise" trend is shown in the graph on the right. We analyzed three primary sources: natural gas, coal, and petroleum. The majority of the thousands of metric tons of polluting emissions released annually come from these three sources. As we can see, the petroleum products are the most polluting of these. They have a major role in the current state of climate change.

<img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/ec0ef109-f449-4aa1-a65b-9f6b7cea67fd' width='800'>

This trend graph shows the overall carbon emissions by per state. We can see here in the 50 states and their individual contributions to the emissions across United States. As per observation, Texas has the highest carbon footprint. This can be contributed to the growing production, automobile and refinery industries in the state of Texas. Texas has a large presence of the country's energy industry, which causes most of this carbon emissions.

<img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/e86627cb-feb6-4be4-a1af-ec6e8f7d2b05' width='800'>

This is the analysis of sector-specific trends for the years 1983–2018. The industries with the highest emissions in recent years have been transportation and electric power, nearly equally. We can see a peak around year 2005 in transportation and electric power sectors. The combustion of fossil fuels for the production of electricity is responsible for more than 40% of energy-related CO2 emissions. However, there has been a slight decrease in carbon emissions from the electric power sector in recent years. This could be a result of the rise in wind and solar power installations.

 For additional details, as well as more in-depth analyses and visualizations of each sector and source, please visit the website.

 ### Conclusions

 This project analyzes the root causes of the 6.6 billion metric tons of greenhouse gas emissions the US produced in 2019 from 1980 to 2018. Along with the electric power sector, the transportation sector also makes a significant contribution, given its heavy reliance on petroleum fuels. Because of things like industrialization and economic expansion, fossil fuels continue to be the most widely used energy source. Texas's industrial activity, and energy-intensive goods production make it stand out as a high emitter. Depletion of resources, diminished ice cover, and global warming are caused by greenhouse gas emissions. In order to lower carbon emissions and save the planet for future generations, eco-friendly alternatives must be adopted in light of the growing population and usage of technology.
