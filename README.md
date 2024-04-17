testing branch
project title: analysis of Olympic Games
Main question: What are the key factors influencing Olympic medal outcomes?
Sub questions: 
- Hosting countries has impact to the country's performance? 
- Season has impact to the country's performance?
- Age, sex, heigh has impact to the performance?

A brief summary about the main dataset(s):
Kaggle: 120 years of Olympic history: athletes and results 

Data preparation: 
- check NAN value and replace them with mean
- create a column for hosting country based on the "city" information

Summary of major findings and conclusions
- Hosting countries tend to perform better/won more medals
- Some countries are better at winter games 
- Age, weight and height have some impact to the Olympic performance

our code:
The data preparation code: Data_cleanup.ipynb
The clean data is saved as Clean_data.csv

The analysis is dividended into 2 parts:
- country: country_performance.ipynb
- athlete: athlete.ipynb

Packages that need to be installed to run the code. The following modules are used for the code: 
matplotlib.pyplot, pandas, geopandas, plotly.express,numpy, request, time, scipy.stats (linregress), datatime, ipywidgets (interact)

Limitations and Assumptions
- Medal counts: The data from Kaggle is based on the participation of each athlete. For a group compeititon, the data will have entry for each athelete who participates the game. Then, the medal counts is overstated for each country if it wins medals for group compeitions.  


Project execution - Just add a snapshot of the project board - to show how you organized this project.
