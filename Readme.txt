==========================================
Bike Sharing Demand prediction for the Big Data Analytics Project(CIND820)
==========================================

Jieun Oh (501075222)


=========================================
Files
=========================================

	- Readme.txt
	- hour.csv : bike sharing counts aggregated on hourly basis. Records: 17379 hours
	- InitialResults_JieunOh.ipynb : a set of technical report in JupyterNotebook format
	- InitialResults_JieunOh.html : a compilation of the uploaded technical report


=========================================
Abstract 
=========================================

The bike-sharing program is a scheme proposed in the 1960s in Europe that allows individuals to borrow bikes for a certain period of time. 
Users can ride bikes to their destinations and return them to a nearby docking station. 
In 2004, only 11 cities operated the programs but it got expanded to more than 50 countries in 2016 with a strong interest in sustainability. 
Now it is considered as a clean alternative to conventional transportation.

In this study, taking ‘Classification and Regression’ as a theme, the demand for public bike-sharing program will be predicted by a regression predictive model. 
In addition to prediction, relative variable importance is analyzed to verify which variables are influential and possess potential predictive power. 
Also, it is examined that registered and casual users respond differently to proposed independent variables such as weather conditions and holiday settings.


=========================================
Data Set
=========================================
Three datasets were amalgamated for this study: Capital Bikeshare Trip data (in Washington D.C. from Jan 2011 to Dec 2012), Holiday data and Weather data. 
For each hourly bike ridership data, corresponding weather conditions were associated and holidays information were added. 
There are 17,379 observations with 16 attributes. Neither missing values nor duplicates were found in any attribute.


=========================================
Associated tasks
=========================================

	- Regression analysis : Prediction of bike rental count hourly based on the weather and seasonal features.

	
=========================================
Dataset characteristics
=========================================	
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:autumn, 4:winter)
	- yr : year (0: 2011, 1:2012)
	- mnth : month (1 to 12)
	- hr : hour (0 to 23)
	- holiday : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : weather situation 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : Normalized temperature in Celsius. The values are divided to 41 (max)
	- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
	- hum: Normalized humidity. The values are divided to 100 (max)
	- windspeed: Normalized wind speed. The values are divided to 67 (max)
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered


=========================================
Tentative stages of the project
=========================================	
1. Choosing a theme and a dataset
2. Conducting a literature review
3. Processing the 1st round of prediction and analysis (initial result) * Current stage
4. Finalizing the analysis and reporting the result
5. Presenting the result


==========================================Dataset Source
==========================================

Hadi Fanaee-T

Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto
INESC Porto, Campus da FEUP
Rua Dr. Roberto Frias, 378
4200 - 465 Porto, Portugal

	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}
