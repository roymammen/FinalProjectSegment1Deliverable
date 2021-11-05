# FinalProjectSegment1Deliverable
1	Name	:Establish temperature trends in specific Metro cities of Europe, US, China, India and Middle East									
		Bonus, if possible add green initiatives are helping with reducing global warming									
2	Why this topic										
		Quantify if add green initiatives may be helping reduce global warming									
3	Description of source of data										
		1	Kaggle Historic temperature of major cities								
		2	generate data with openweathermap.org API
    3 Other sources yet to be determined
4	Question to find answer with the data										
		Are we headed to polar cap melt down?									
		1	If there had been no actions taken, when can the global temperature rise creating permenant climate change								
		2	Given the current trends, what is the projected temperature 10 years from now								
		3	Compare how close your ML model is to a popular weather site for cities in US								
											
5	Visuals 	
    1	Maping of Cities 								
		2	Graph plottomg average yearly temperature trends of cities								
		3	Graph ploting Average yearly polulation growth of cities								
		4	Graph plotting Average yearly rainfall/snowfall recorded in cities								
											
6	Database	Postgress SQL									
		Table#1	Clean upload historic temperature data								
			Automate to update data to historic data using APIs for temperature on a daily basis								
		Table#2 	Average Rain fall recorded in City								
			Automate update data to Average Rain fall in city								
		Table#3	Mean distance of Earth from Sun = MDES (Historic)								
				Update for each city a temperature coefficient by adding distance to equator + MDEF 							
			Update historic data with yearly update								
		Table#4	Average yearly population of the city Historic								
			Update historic population data yearly and update Table								
											
7	ML	Train Forecast Average yearly temperature trends in these cities from following resources									
		Data used for Training use from Postgress Database. Supplied as DataFrames									
		1	Historic data from average yearly temperatures : Kaggle city temperature data. 								
			Establish if we can get temperature data for these specific cities from site								https://home.openweathermap.org/
		2	How far the mean distance of earth from Sun. Farthest, closest, mean in a year								
		3	City proximity from equator as a parameter + Mean distance of Earth to Sun (MDES)								
		4	Average Rain fall recorded in the city								
		5	What is the average population of the City								
											
			Pottential candidates to add integrate								
				How Effective is Public transit in the city							
				Number of Evs used by the city per capita							
![image](https://user-images.githubusercontent.com/6334337/140454687-06ac84c5-aad7-47a8-bcc9-72edf8e6ad86.png)
