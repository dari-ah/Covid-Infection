# Covid_Infection
  Since its first outbreak, COVID-19 has caused many devastating losses and changes to lives around the world. Considering its major global impacts, I want to investigate how the virus infects different parts of the world and find the potential contributing elements to the infection. I studied the infection rate and death rate in each country and found correlations between factors that can lead to higher cases.

Table of Contents:
	+ Objective:
	+ The Dataset:
	+ Results:
  
Objective:
	Due to the highly contagious nature and airborne transmission of the virus, I first looked at the potential relation between population density and the infection rate. My motivation was that if a country had more people living closely together, the infection rate would be higher. I then looked at the potential correlation between infection rate and GDP indexes. I reasoned that countries with lower GDP might have fewer resources available to prevent and treat the disease. Additionally, countries with lower indexes may have unsafe living conditions, which can contribute to the infection rate. 
  
Dataset:
	The dataset I used for this project is Coronavirus (COVID-19) Death, provided by ourworldindata.org. I selected data from January 1st, 2020, to August 10th, 2021. The original dataset included information about infected cases and death in each country. It also contained vaccination and hospitalization information, organized as one table. Before beginning my queries, I worked on my data modeling process. I first sorted the data following the data schema attached below. After that, I cleaned the data before importing it into Azure Data Studio. The original dataset, however, had one slight inconvenience. Whenever the continent column was null, the location column held the continent information. Additionally, the location column also included international information. Since this information was not relevant to my query, I decided to exclude them from my tables.

Results:
-infection rate and population density: The correlation between infection rate and population density is 0.0469. The number indicates some minor relationship between the two elements and is not very significant. The correlation might not be very accurate since the population density of some countries is not included or included incorrectly. Regardlessly, countries with high population density do have high infection rates. 

-infection rate and GDP indexes: The correlation between the two elements is 0.5121, showing a moderate positive relationship. Thus, a country’s GDP index has some contribution to its infection rate
	
Since all of the elements have a positive relationship with the infection rate, these elements affect how the virus spreads in a country. 
