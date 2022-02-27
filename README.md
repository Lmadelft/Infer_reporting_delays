# Infer_reporting_delays 
This code is to infer the reporting delays of infections, recoveries, and deaths based on the time series of daily infections, recoveries, and deaths. 
The data considered in this file are the infections, recoveries, and deaths in the first wave of the COVID-19 pandemic for Spain.
The code is to smooth the time series first. 
In each step, we randomly choose candidate delay parameters. Then we do 10^7 random search to find the delay distributions which can make the revised time series turn proportional to each other. 
