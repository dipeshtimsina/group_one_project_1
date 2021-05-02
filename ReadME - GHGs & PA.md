# Project One: Climate Change, Greenhouse Gas Emissions (GHGs) & Pennsylvania

**Contributors:** Megan Spriesterbach, Dipesh Timsina, Andrew Kromer, Anthony Hopkins
UPenn Data and Visualization Boot Camp (May 3, 2021)

#### <u>Project Guidelines:</u> 

* Determine scope and purpose of project - what questions will you be asking of the data?
* Sources for data
* Clean & visualize data in Jupyter Notebook
* Presentation of analysis

#### <u>Question:</u> 

How does Pennsylvania contribute to an issue we know must be resolved in relation to carbon dioxide emissions? 

#### <u>Sources:</u>

* EIA: https://www.eia.gov/environment/emissions/state/
* Kaggle - US Facility Data: https://www.kaggle.com/jaseibert/us-facilitylevel-air-pollution-20102014
* Kaggle - US Energy Census GDP: https://www.kaggle.com/lislejoem/us_energy_census_gdp_10-14
* WorldBank - https://climateknowledgeportal.worldbank.org/download-data

#### **<u>Analysis:</u>**

* CO2 emissions by country - the United States was the 6th greatest producer of CO2 from 1990-2016
* Top 5 U.S. states with highest CO2 emissions (1990-2018) - TX, CA, PA, IL, & OH
  * Based on a 5 year analysis (2010-2014), these 5 states consume between 1000-2500 million metric tons, accounting for 31.5% of national emissions, while the average state consumes 400 million metric tons of CO2 producers.
* U.S. CO2 emissions per capita from 1960s-2010s
* U.S. & PA CO2 emissions per capita from 1990-2016
* CO2 emissions: PA facilities vs. PA per capita (2010-2014) - trends are nearly the same over 5-year time period, though industrial facility emissions are in the hundred millions vs. per capita in the tens of millions
* Total carbon dioxide emissions from fossil fuel consumption in PA by sector - Electric Power (40.4%), Transportation (24.6%), Industrial (21.5%), Residential (9.0%) and Commercial (4.5%)
* Emission type by sector in PA - Coal driving total emissions (80 million metric tons) in Electric Power section & Petroleum Products (60 million metric tons) driving emissions in Transportation Sector
* Total CO2 vs. GDP by State (2014) - The r-value (0.85) suggests the more GDP output (USD millions), the higher the emission levels of CO2
* Top 10 counties in PA by total facility count and total CO2 emissions (2010-2014)
* Heatmap of Total CO2 emissions by facility (2010-2014) illustrates the high level of CO2 emissions by facility (only facilities emitting 25k+ metric tons of CO2 required to report)
* Number of facilities reporting emissions vs. facilities not reporting emissions - on average, from 2010-2014, only 21.2% of facilities reported their CO2 emissions

#### <u>Limitations:</u>

* Data focused mainly on CO2 emissions within the categorization of greenhouse gases (GHGs), but did not take into account other types of GHGs (e.g., methane, nitrous oxide, fluorinated gases, etc.)
* Datasets were incomplete due to lack of available information (i.e., CO2 emissions by certain countries in the 1960s) or because entities are not mandated to report (i.e., in PA, only larger facilities emitting 25k+ metric tons of CO2 are required to report their annual CO2 emissions)

#### <u>Conclusions:</u>

* Commercial and Industry sectors have the highest output of CO2 emissions; based on the correlation between CO2 and GDP $, both sectors are incentivized to not report their CO2 emissions
* The residential sector accounted for 9.0% of total CO2 emissions in PA, while electric power, transportation, and industrial sector account for 86.5% of total CO2 emissions. This suggests that while it's important for individual's continue to be mindful of their CO2 emissions, the responsibility will lie on industrialized sectors to curb total emissions
* The EPA stated: "The GHGRP generally requires facilities that emit above 25,000 metric tons CO2e [carbon dioxide equivalents] of GHGA’s to report their emissions. Therefore this data set does not reflect total U.S. emissions or total emissions from individual states. Roughly 50% of total U.S. emissions are reported by large emitting facilities subject to the GHGRP." Based on the data from 2010-2014 showing only 21.4% of PA facilities reported their CO2 emissions; therefore, we can conclude that total CO2 emissions in PA are actually higher than what reported numbers reflect.

