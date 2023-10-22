## Analyzing the Energy-Related Carbon Emissions in the U.S.

The United States on average produced 6.6 billion metric tons of carbon dioxide equivalent greenhouse gas emissions in 2019. Our goal with this project is to research and evaluate the energy-related carbon emissions (total GHG) across US sectors over the past few years. The emissions from fossil fuels, such as coal, natural gas, and petroleum, are referred to as "energy-related." The "Unites States Energy Information Administration" provided the project with the dataset, which covered the years 1980 through 2019. The information includes more details on sub-sectors within each of the five main sectors (Commercial, Industrial Process, Residential, Transportation, and Electricity) as well as the energy-related carbon emissions in each.

To view all visualizations and further details about the project, kindly visit [Project Website](https://sites.google.com/sdsu.edu/energy-carbon-emissions/)

### Problem Statement
Carbon emissions, sometimes known as greenhouse gases, are the main cause of global warming. This line brought to mind the rising global temperature, the world's population, and the US's partially destroyed ozone layer. As students studying cutting-edge technologies, we feel obligated to be aware of our surroundings. We can surely utilize technology to transform the real world if we can use our analysis to grasp its problems, which is now the case. This is due to the fact that identifying the root of an issue solves half of it. Every living thing on the planet is impacted by a poor environment and contaminated air, water, and soil, regardless of where in the globe one lives. This makes addressing global warming and carbon emissions crucial.

### Tools Used
1) Web Development : Google Sites
2) Visualization : Tableau, ArcGIS
3) Data Preparation : Microsoft Excel

### Dataset
Data for the project was obtained from the Energy Information Administration (EIA) website in the United States. This dataset includes information on energy-related carbon emissions for the five main sectors of transportation, industry, electricity, and residential and commercial buildings from 1980 to 2018. Three main sources account for the majority of energy-related emissions: natural gas, coal, and petroleum. You can download the dataset from following links.

[Emission Data](https://www.eia.gov/environment/emissions/state/)

[Geographical Data](https://developers.google.com/public-data/docs/canonical/states_csv)

### Data Preparaion
Data preparation and cleaning are carried out in sequential steps, with distinct files being made for each set of graphs.
1) Combine information from 50 excel files—one for each state—into one file.
2) Update each state's latitude and longitude.
3) Create separate CSV files containing temporal data for every sector and source.

This repository contains the cleaned and processed data.

### Data Visualizations
Some of the most important visualizations are shown below. Please visit the website for more information and plots.

<img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/2d9871ef-e26f-4afc-92b1-f1bc2bb59a1d' width='500'> <img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/4423bb84-1722-4e85-bff1-0e452b75ab0c' width='500'>


This graph depicts the overall trend in carbon emissions by sector. Our dataset includes five sectors: commercial, transportation, electric power, residential, and industrial. We can see that over decades, the electric power sector has produced the most emissions. The total amount of electricity generated in the United States by the electric power industry from all energy sources was 4.01 trillion kilowatt-hours (kWh), resulting in the emission of 1.55 billion metric tons—1.71 billion short tons—of carbon dioxide (CO2).

<img src='https://github.com/UmaBetageri/Carbon-Emission-Analysis/assets/134670470/2d9871ef-e26f-4afc-92b1-f1bc2bb59a1d' width='600'>


