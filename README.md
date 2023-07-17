# Detect land and sea contrast in high-resolution Ocean surface wind data
Using Fourier series to decompose linear and cyclic trends of high-resolution wind data in kilometre-scale simulations.

## Data description
Data comprises near-surface u and v wind, simulated from Unified Model. Data is for 20200701-20200704 at hourly intervals. Data is on a dx=dy=1.5 km grid. Using a rotated coordinate system. 

## Methodologies
* A linear trend over 4 days
* Fourier series of 24h cycle and 12h cycle
* AR(1) of the residuals

## Analysis
Plot the parameters of all these component trends to see 
* Increasing/ decreasing trend inland and offshore and coastal line
* Amplitude of diurnal and semi-diurnal cycle
* Standard deviation of wind speed in the area
* Coefficients of the AR term in residuals after removing linear and diurnal trends
