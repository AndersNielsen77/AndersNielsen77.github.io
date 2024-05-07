---
layout: default
#layout: single
title:  "02806 Final Assignment"
date:   2024-05-06 09:00:30 +0100
categories: Update
#classes: wide
---


# Final assignment for 02806 Social Data Analysis and Visualization
This assignment is made by students s204606, s194299 and s185382.  

### Introduction to the assignemnt 
In recent years, world leaders have emphasized the critical importance of constraining global warming to 1.5°C by the close of this century. This urgency stems from the findings of the UN’s Intergovernmental Panel on Climate Change, which warns that surpassing the 1.5°C threshold could trigger significantly harsher climate change repercussions. These consequences may include more frequent and intense rainfalls, droughts and heatwaves. To achieve this goal, greenhouse gas emissions must decrease by 43% before 2030. ([1], The Paris Agreement) Many of these goals include an increase in energy production from renewable sources, since about 34% of all grenhouse gasses emitted in 2019 was from global energy production. ([2], EPA) Since then, EU has set the goal of being carbon neutral in 2050, and EU countries have followed with local goals and directives. For instance Sweden has set a goal of not producing energy from fossil fuels at all in 2040, and Denmark has set the same goal, but for 2050 ([3], Energimyndigheten),([4], Norlys). This comparative analysis will therefore deep dive into the energy production of Denmark and Sweden, to explore whether or not they are on track to reach these goals. This analysis uses the dataset ‘Global Electricity Production’ ([5], Kaggle) , which includes daily data about energy production for 48 different countries, including the mode of production (solar, nuclear, wind etc), as well as imported and exported energy in GWh.  


### Global energy production over time 
To gain an initial insight into the production of energy worldwide, a map is constructed which shows the development in energy production from year 2010 to year 2021. This visual tool helps in assessing the global trend towards greener energy sources.

<iframe src="/renewable_production_over_time2.html" height="500" width="720"></iframe>

Generally, the global trend is that each country produces a higher percentage of renewable energy. Worth noting is that some countries do not have data prior to 2014, which is why China for example is only visible after this. Overall, European countries show a positive trend towards higher percentages of renewable energy production, supporting the goal of reducing greenhouse gas emissions. Iceland and Norway already have a substantial portion of renewable energy in their production, thus their progress may not be as noticeable. Conversely, Denmark and Sweden show similar increases in the percentage of renewable energy, suggesting parallel developments in these two countries. A closer examination of the renewable energy production methods in Sweden and Denmark will be conducted to better understand their respective strategies.

### Production of different energy types over time
The graph below shows the total production of renewable energy for the respective countries. The graph is interactive, so the visualisation can be filtered based on the type of energy production. 

<iframe src="/combined_figure.html" height="500" width="720"></iframe>

When looking into the different modes of energy production, Sweden and Denmark does display a significant difference. Sweden has a lot of hydropower and wind energy, while Denmark almost solely relies on wind energy and a bit of solar energy. Sweden also produces large amounts of nuclear power, which Denmark does not, due to a danish law forbidding it in 1985 ([7], Danmarkshistorien). Currently, nuclear power is not classified as a renewable energy source, but rather a 'low-carbon' energy source by the EU. Nuclear power is however not a fossil fuel, and still counts towards the goal of limiting CO2-emissions, even though it is a controversial type of energy production ([6], National Grid). Therefore, exploring the significance of nuclear power in Sweden and Denmark is also relevant when looking at energy production and its contribution to climate change. The upside of using nuclear power, is that many renewable energy sources are dependent on weather, such as solar energy and wind energy, which is the only two renewable energy sources produced in Denmark. We will now look closer at how the renewable energy production varies throughout the year. 

### Wind energy production in Denmark over time 
The below graph shows the production of wind energy in 2021, which was a year of very little wind, compared to the average wind energy produced between 2010 and 2020. The data has been normalised so it is proporrtionate to the number of windmills and their capacity. 

<iframe src="/wind.html" height="530" width="720"></iframe>

From the graph above, it is clear that wind production is not always consistent. In months with an excess of wind, energy is exported to nearby countries, and in times of low wind energy production, other types of energy are used (which are non renewable), or energy is imported from nearby countries (primarily from Norway and Sweden) ([4], Norlys). This raises the question if the wind and solar production is robust enough for Denmark to become free of fossil fuels, or if they will need to keep importing energy to sustain themselves. To gain an understading of the energy import and export for the two countries, this is plotted in the graph below.  

### Import and export of energy in Sweden and Denmark
The graph below shows the average monthly import, export and energy production for Sweden and Denmark respectively. 

<iframe src="/Electricity_breakdown.html" height="530" width="700"></iframe>

It is clear that Denmark is more dependent on imported energy than Sweden is, and that the danish renewable energy types are more volatile than the swedish. This is probably because Sweden's renewable energy production includes large amounts of hydro energy, which is not seasonal in the same way that wind and solar energy is, which constitutes the only renewable energy production in Denmark. Adding nuclear energy on top of the more stable renewable energy production for Sweden, means that Sweden exports more energy than it imports. As previously stated, most of the imported energy in Denmark is from Sweden and Norway, both of which have mostly renewable energy sources, which makes the energy consumption in Denmark mostly renewable, despite its large amount of imported energy. It does however seem like the renewable energy sources in Denmark is not enough on their own to support the countries consumption. Having gained an insight into the development of renewable energy in Sweden and Denmark, a trend line is employed to estimate whether or not the local goals of not using fossil fuels can be reached, for both Sweden and Denmark. The trendline is created using a linear regression model. 

### Will Sweden and Denmark reach their goals of zero fossil fuel energy production in 2040 and 2050? 
The graph below shows a forecast of renewable energy sources made with a linear regression model. For Sweden, the forecast includes just renewable energy, and renewable energies together with nuclear energy, to assess if nuclear energy is still crucial for reaching the goal of zero fossil fuels. The graph is interactive. 

<iframe src="/Trendlines2.html" height="530" width="700"></iframe>

Based on this linear regression, Denmark will reach its goal of having 100% of its energy be from renewable sources as early as 2031, if the growth in renewable energy sources (particularly wind energy) is stable. For Sweden, the goal will not be reached if the current development is kept up, as in 2040, only 81% of its energy production will be from renewble sources. If nuclear power is included in this, it will reach only 96% of the total energy production. This looks promising, but Sweden will need to invest in renewable energy sources or more nuclear power to reach its climate goals. There are actually already plans for this, as the swedish government plans to increase Sweden's nuclear power equivalent to two large reactors by 2035, which would mean that they would reach their goal ([8], WNN). For Denmark, the renewable energy sources wind and solar power is not always stable and reliable, and so the country may still need to rely on Sweden and Norway, even if the growth of renewable energy production is kept up. 


### Summary 
The assignment examines Denmark and Sweden's progress in transitioning to renewable energy and eliminating fossil fuel dependence. It stresses the global imperative to limit global warming to 1.5°C and highlights the role of renewable energy in achieving this. Using data from the 'Global Electricity Production' dataset, it analyses renewable energy trends in both countries, noting Sweden's reliance on hydro and nuclear power and Denmark's focus on wind and solar energy.

Challenges arise from Denmark's intermittent wind energy production, leading to fluctuations in energy import and export. A comparison of energy import/export patterns between Sweden and Denmark reveals Denmark's higher dependence on imported energy. Forecasting with a linear regression model suggests Denmark could achieve 100% renewable energy by 2031, while Sweden may fall short of its target by 2040, even with nuclear power. This underscores the need for Sweden to invest more in renewables.

In conclusion, Denmark shows promising progress, but Sweden faces challenges in meeting its renewable energy targets, necessitating further investment. Collaboration between the two countries could aid in a sustainable transition to renewables and mitigate climate change impacts.


### Sources 
1. 'The Paris Agreement', _United Nations (UN)_, 4 May 2024, https://unfccc.int/process-and-meetings/the-paris-agreement
2. 'Global Greenhouse Gas Overview', _United States Environmental Protection Agency (EPA)_, 2 May 2024, https://www.epa.gov/ghgemissions/global-greenhouse-gas-overview
3. 'Sveriges energi- och klimatmål', _Energimyndigheten_, 5 May 2024, https://www.energimyndigheten.se/klimat--miljo/sveriges-energi--och-klimatmal/
4. 'Hvor meget af Danmarks energi er vedvarende?', _Norlys_, 6 Maj 2024, https://norlys.dk/inspiration/energi/hvor-meget-af-danmarks-energi-er-vedvarende/
5. 'Global Electricity Production dataset', _kaggle_, 20 Mar 2024, https://www.kaggle.com/datasets/sazidthe1/global-electricity-production
6. ‘What is nuclear energy (and why is it considered a clean energy)?’, _National Grid_, 27 Mar 2024, https://www.nationalgrid.com/stories/energy-explained/what-nuclear-energy-and-why-it-considered-clean-energy
7. 'Atomkraft-politik i Danmark, 1973-1985', _Danmarkshistorien_, 6 May 2024, https://danmarkshistorien.dk/vis/materiale/atomkraft-politik-i-danmark-1973-1985
8. 'Sweden plans 'massive' expansion of nuclear energy', _World Nuclear News (WNN)_, 7 May 2024, https://www.world-nuclear-news.org/Articles/Roadmap-launched-for-expansion-of-nuclear-energy-i?fbclid=IwAR3dGFlaRYXGhrivv3TtKvte6AIOhVXfiexflESr61AdhfsJKTfiiy_9CdU


### Contributions 
**The group has worked together on all parts of the assignment. The following list shows the main contributor of each part of the assignment:** 

**s204606 - Liv**  
Bar chart Introduction and Summary 

**s194299 - Anders**  
Heat map

**s185382 - Magnus**  
Bokeh plot
