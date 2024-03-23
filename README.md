# Global-Emissions-Analysis-using-Tableau


![Global Emissions Tablaeu dashboard](https://github.com/Mona-Bhagat/Global-Emissions-Analysis-using-Tableau/assets/148805047/badb428d-4f3b-4eda-8e90-ed41560c0137)


# About
This project aims to analyze Global Emissions Trends using a dataset containing data from 1750 to 2021. Many analyses using this information have been done before this however they mostly analyze using production-based CO2 emissions data. This particular project has taken a different approach by analyzing trends based on consumption-based CO2 emissions. Additionally, this project has narrowed down focus on the most vital indicators such as emissions per capita, per-dollar GDP, and countries' contribution to the rise in Global Mean Surface Temperature. 


# Notes:
<p align="justify">
* The data has been filtered down from 1750 - 2021 to 2000 - 2021 to capture recent trends and increase accuracy with high-resolution trade data. 
<p align="justify">
* The Fossil fuel chart however displays a trend from 1900 to 2021 to encapsulate the historical trend. 
<p align="justify">
* For this analysis, consumption-based CO2 emissions data have been used in place of traditional production-based measures of total emissions. From my readings, I felt consumption-based emission offers a more comprehensive understanding of a country's carbon footprint by capturing emissions from traded goods – the CO2 emitted in the production of goods elsewhere, which are later imported (or the opposite: emissions from goods that are exported) (Our World in Data, 2020). Consumption-based accounting is based on the ground that those who benefit from a process should bear (at least some) responsibility for the associated emissions (Chen et al. 2018).
</p>

# Limitations:
This analysis would have been more enriched with data on emissions from different sectors (Electricity, Transport, Agriculture, and Aviation) as well. Due to the lack of sector breakdown in the dataset, this analysis couldn't be included and can be considered a limitation.


# Tools:
* Excel CSV - Single Table Data Structure
* Tableau
  

# Preprocessing
<p align="justify">
* Rows with non-ISO codes were filtered out, which resulted in narrowing down the data to include only individual countries and not groupings under headings such as World, Africa, Asia, etc. This was done because our analysis is focused only on the country-level data and not the regional data.
<p align="justify">
* Data types of fields with CO2 figures were changed from strings to numbers and moved from the Dimensions section to Measures.  


# Insights from charts (in Z layout format)
<p align="justify">
Chart 1 - As per me measuring how a nation is developing sustainably and inclusively is more vital than just growth. Hence, the first chart tracks the CO2 emissions generated per dollar of GDP by the Top 5 economies of the world.
China produced almost 0.55 kg CO2 per dollar of GDP driven by its high dependency on coal and oil to fuel its energy consumption. It is followed by the USA and India at 0.40 and 0.29 consecutively. Japan has one of the lowest figures at 0.32 kg indicating a more environmentally conscious approach to economic development. I can’t help but wonder if Japan could have achieved an even lower figure had it not been forced to discontinue its nuclear power plants and subsequent shift to thermal power generation following a powerful earthquake in 2011. However, its recent change in stance on returning to nuclear power around 2022 (Reuters, 2022) can rapidly change its ranking
  
<p align="justify">
Chart 2 - The next chart shows CO2 Emissions per capita. Singapore leads with an average consumption CO2 per capita of 30.71, followed closely by the United Arab Emirates (27.52), Qatar (27.28), Kuwait (23.78), and Luxembourg (21.85). Usually, when CO2 per capita is used as a measure we see names like Qatar, UAE, Bahrain, etc. on top (Statista, 2023) but when the consumption-based measure is used, we see countries like Singapore and Luxembourg on top as well. This trend is prevalent in nations that are wealthy but have economies with limited natural resources. An average Singaporean generates an alarming 9000kg of carbon emissions per year, more than twice the world's average, and more than 4 times the target to maintain a sustainable footprint (Tham, 2020).

<p align="justify">
Chart 3 - The third chart shows countries' contribution to the rise in Global Mean Surface Temperature from its cumulative emissions of carbon dioxide, methane, and nitrous oxide. The United States comes as no surprise as the highest contributor (18.76%), followed by China (10%), Russia (6.59%), Brazil (4.87%), and India (4.48%). Interestingly, the USA alone contributes almost twice as much as China, and even more than China and Russia combined. Its hunger for energy (energy-intensive appliances), transportation (preference for large fuel-guzzling vehicles), and lack of political will (Donald Trump pulling out of the Paris Agreement, thankfully Biden is more sociable) all explain the top ranking.

<p align="justify"> 
Chart 4 - The fourth chart shows trends of the top three fossil fuels Coal, Gas, and Oil contribution to carbon emissions. Coal has been the most preferred fuel source for the world as a whole due to its abundance, easier accessibility, and reliability. It was first taken over by oil around 1969 due to a rise in automobile usage and technological advancements in oil extraction.  Its contribution to carbon emission overtook Oil in 2002 driven majorly by China to fuel its rapidly growing economy. Overall, in the last 20 years, there have been only a couple of occasions where we see a slump in carbon emissions. And it's easily guessable, the 2008 financial crisis and the 2000 covid pandemic. Guess only forces beyond human control can incentivize us to lower our consumption patterns.

</p>

# Summary 

2023 officially was the warmest year on record (Lindsey and Dahlman, 2024). The top 10 emitters account for more than 60 percent of the global total emissions (Jia et al. 2023). Whilst the UK was the world's largest emitter till 1888 due to industrialization, at present it accounts for less than 1% of global emissions. However since a large fraction of CO2 remains in the year for hundreds of years once emitted, it poses challenges in terms of agreement as to which countries should shoulder more responsibility in tackling global warming.  Historically, CO2 emissions have been a by-product of an improved standard of living but to secure the conditions for future generations it’s imperative for the world to transition to sustainable lifestyles (Ritchie and Roser, 2020). How about donating your clothes instead of just throwing them away? Maybe switch to a more plant-based diet or allow more WFH ;-)



# Citations:

* Chen, Z.-M., Ohshita, S., Lenzen, M., Wiedmann, T., Jiborn, M., Chen, B., Lester, L., Guan, D., Meng, J., Xu, S., Chen, G., Zheng, X., Xue, J., Alsaedi, A., Hayat, T. and Liu, Z. (2018). Consumption-based greenhouse gas emissions accounting with capital stock change highlights the dynamics of fast-developing countries. Nature Communications, [online] 9(1), p.3581. doi:https://doi.org/10.1038/s41467-018-05905-y.
* Lindsey, R. and Dahlman, L. (2024). Climate Change: Global Temperature. [online] Climate.gov. Available at: https://www.climate.gov/news-features/understanding-climate/climate-change-global-temperature.
* Ritchie, H., Roser, M. and Rosado, P. (2020). CO2 and Greenhouse Gas Emissions. Our World in Data. [online] Available at: https://ourworldindata.org/co2/country/singapore#consumption-based-accounting-how-do-emissions-compare-when-we-adjust-for-trade [Accessed 18 Mar. 2024].
* Jia, Kamwoo Lee, Divyanshi Wadhwa, and Maarten Lambrechts. 2023. “From climate science to global action” In Atlas of Sustainable Development Goals 2023, edited by A. F. Pirlea, U. Serajuddin, A. Thudt, D. Wadhwa, and M. Welch. Washington, DC: World Bank. License: Creative Commons Attribution CC BY 3.0 IGO. https://www.doi.org/10.60616/vg01-7787 
*Tham, N. (2020). Where do Singaporeans stand in terms of carbon dioxide emissions per capita as compared to the rest of the world? | EDPR APAC. [online] www.edpr.com. Available at: https://www.edpr.com/apac/en/where-do-singaporeans-stand-terms-carbon-dioxide-emissions-capita-compared-rest-world#:~:text=By%20Natalie%20Tham [Accessed 18 Mar. 2024].
* Ritchie, H. and Roser, M. (2020). CO2 emissions. [online] Our World in Data. Available at: https://ourworldindata.org/co2-emissions.


