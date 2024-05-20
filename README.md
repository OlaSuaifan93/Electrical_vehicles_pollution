# Electrical_vehicles_pollution
The research here is about finding the CO2 Emissions that are caused 
by electric vehicles that are not moving using fuel and so they dont cause
CO2 emissions however, is this actually true?  

To do the research, some data were gathered for the EV use in the US:
1- state electricity generative energy sources 
a data set that consists of the states and electricty percentage that is 
generated via each source. the sources are (nuclear, coal, natural gas, petroleum, renewable and Hydro)
reference: https://www.nei.org/resources/fact-sheets/u-s-nuclear-plants 
2- CO2 Emission per power/energy source
a dataset that shows the CO2 emission in grams per energy source 
reference: https://www.iea.org/data-and-statistics 
3- Driver Milage per state: 
a dataset that shows the  average annual mileage driven by EV drivers per state. 
reference: https://www.policygenius.com/auto-insurance/average-miles-driven-by-state/

Preprocessing: 
Collecting Data:
Gather data from various sources on electricity generation, CO2 emissions, and EV usage across different states.
Converting Data:
Transform all collected data into CSV format for easier analysis.
Calculating Key Metrics:
CO2 Emissions per kWh: Calculate how much CO2 is emitted per kWh by different power plants.
Average Emissions per Driver: Determine the potential CO2 emissions based on average mileage per driver in each state.

Insights:
- Rhode Island scored the highest percentage of electricity energy source which is Natural Gas.
- Petroleum is the energy source with the highest CO2 Emission per kWh
- Wyoming is the state with the highest number of vehicles annual millage.


Maps had been used to demonstrate the CO2 emission per Energy source also per state through Driving

Conclusion:
Petroleum Power Plants: Although petroleum power plants are less common
across the United States, they are significant contributors to CO2
emissions in specific regions, particularly in Hawaii and Alaska.
These areas rely more heavily on petroleum due to geographic and
infrastructural constraints, leading to higher localized emissions.
Coal as a Primary Emitter: Coal remains the predominant source of CO2 
emissions nationwide, due to its extensive use in electricity generation.
The high carbon content of coal results in greater CO2 emissions per unit 
of energy produced compared to other fossil fuels.
Impact of Clean Energy Sources: States with higher percentages of hydro,
nuclear, and renewable energy generation typically exhibit lower CO2
emissions. These energy sources are cleaner alternatives that produce 
little to no direct CO2 emissions, thereby contributing to a more 
sustainable energy profile and aiding in the reduction of overall 
greenhouse gas emissions.
