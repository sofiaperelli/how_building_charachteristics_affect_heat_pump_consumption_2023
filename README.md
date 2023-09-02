# how_building_charachteristics_affect_heat_pump_consumption_2023
This is the code used in the methodology section of Sofia Perelli-Rocco's dissertation, reading for an MSc Energy Systems at Oxford University. The study is entitled 'How building characteristics affect heat pump consumption - a United Kingdom case study'. The data and analysis builds on the 2020-2023 Electrification of Heat UK heat pump trial.

This code retrives the clean 2-minute consumpion data for each house in the EoH trial. This data is publicly available at https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=9050#!/ .

By selecting the same properties that were deemed approperiate in the EoH trial analysis, the first part of the code creates files containing the average yearly and seasonal daily consumption pattern appended for each house. The output files are attached on GitHub for simplicity.

The second part of the code uploads the processed output file data and uses it to produce several plots that are part of the results of the dissertation. Results include the daily pattern of heat pump consumption averaged over different season and over the year, the regrouping of the data sample in houses based on EPC and MCS SHL and MCS HL values, and the differences in heat pump patterns in different house characteristics groups. The code also contains a focus on the coldest day heat pump consumption and efficiency.

Data sources:
Clean data – https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=9050#!/ . 
Raw data – https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=9049#!/   . Design and installation data – https://usmart.io/org/esc/discovery/discovery-view-detail/5325ef18-9cd1-493c-beae-e278d8998400  
Code for cleaning the EoH data: https://github.com/ES-Catapult/electrification_of_heat  
