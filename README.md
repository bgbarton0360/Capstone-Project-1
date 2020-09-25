Time Series Modeling and Forecasting  

Folder Descriptions  

Each folder contains output graphs for each franchise  
Avengers  
Batman  
Justice League  
Spiderman  
X-Men  

Inside each folder contains 8 files with similar naming conventions  
Franchise_Diag_ARIMA.png - ARIMA diagnostics  
Franchise_Diag_SARIMA.png - SARIMA diagnostics  
Franchise_Diag_SARIMAX.png - SARIMAX diagnostics    
Franchise_Line.png - Line plot of comic book sales over time   
Franchise_Predict_ARIMA.png - ARIMA comic books predicted vs observed  
Franchise_Predict_SARIMA.png - SARIMA comic books predicted vs observed  
Franchise_Predict_SARIMAX.png - SARIMAX comic books predicted vs observed  
Franchise_Stat.png - Bootstrap sampling of difference in mean between movie playing and no movie playing  

Main Folder  
Franchise_Code.ipynb - Code for each franchise  
Franchise_Final.csv - Dataset for each franchise  
Capstone Presentation.pptx - Slide show of project  
Final Report.pdf - Project walkthrough and analysis  
 
The capstone's project goal is the investigation of comic book sales and the effect movies have on its sales.  
Data obtained for this project was acquired from the website Comichron which has records of physical comic sales starting from April 1997.  
After importing and cleaning the data, we did a hypothesis test of the difference of means for when movie is playing or not for a certain franchise.  
Found that there was no significant difference for Batman and Spider-Man but there was a significant difference for Avengers, Justice League, and X-Men.  
Next, since we are dealing with data that is dependent on time as a variable we use ARIMA modeling as well as SARIMA and SARIMAX due to its seasonal trends and exogenous variables of movie playing or not.  
Using MAPE to measure prediction accuracy we found that forecasting was best for Avengers, Batman, and X-Men while Justice League and Spider-Man was not.  
Avengers = 43.9%  
Batman = 31.3%  
Justice League = 236.9%  
Spider-Man = 127.4%  
X-Men = 31.4%  
