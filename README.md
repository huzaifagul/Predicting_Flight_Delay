# Predicting_Flight_Delay

Predicting Flight Delay Causation in United States using Logistic Regression
By: Huzaifa Gul

The data in this dataset is derived and cleaned from the full Bureau of Transportation Statistics dataset to illustrate the delay of air traffic during the COVID-19 pandemic. It spans all flights seen by the network's more than 2500 members between Jan-2020 to March 2021. 

The columns used include: 

Column Name		Data Type	Description
Month			Integer		Month of Journey
Origin			Object		Origin 	Airport
OriginCityName		Object		Origin Airport, City Name
Dest			Object		Destination Airport
DestCityName		Object		Destination Airport, City Name
DepDelayMinutes		Float		Difference in minutes. Early departure set to 0.
Cancelled		Float		Cancelled Flight Indicator (1=Yes)
Diverted		Float		Diverted Flight Indicator (1=Yes)
Carrier Delay		Float		Carrier Delay, in Minutes
Weather Delay		Float		Weather Delay, in Minutes
NAS Delay		Float		National Air System Delay, in Minutes
Security Delay		Float		Security Delay, in Minutes
Late Aircraft Delay	Float		Late Aircraft Delay, in Minutes

Data processing script
https://github.com/huzaifagul/Predicting_Flight_Delay.git with detailed comments

Credit
Bureau of Transportation Statistics (2021). On-Time : Reporting Carrier On-Time Performance from Jan-2020 to March 2021, https://www.transtats.bts.gov/DL_SelectFields.asp?gnoyr_VQ=FGJ 

Ding, Y. (2017). Predicting flight delay based on multiple linear regression. IOP Conference Series: Earth and Environmental Science, 81, 012198. doi:10.1088/1755-1315/81/1/012198 

Gui, G., Liu, F., Sun, J., Yang, J., Zhou, Z., & Zhao, D. (2019). Flight Delay Prediction Based on Aviation Big Data and Machine Learning. IEEE Transactions on Vehicular Technology, 1–1. doi:10.1109/tvt.2019.2954094 
Yu, B., Guo, Z., Asian, S., Wang, H., & Chen, G. (2019). Flight delay prediction for commercial air transport: A deep learning approach. Transportation Research Part E: Logistics and Transportation Review, 125, 203–221. doi:10.1016/j.tre.2019.03.013
