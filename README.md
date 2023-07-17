# Detect land and sea contrast in high-resolution Ocean surface wind data
Using Fourier series to decompose linear and cyclic trends of high-resolution wind data in kilometre-scale simulations.

## Data description
Data comprises near-surface u and v wind, simulated from Unified Model. Data is for 01-04 July 2020 at hourly intervals. Data is on a dx=dy=1.5 km grid. Using a rotated coordinate system. 

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

Map of land and sea in Sahel (Africa)
![image](https://github.com/melliemainguyen71/wind_speed_land_sea_contrast/assets/98959461/899423e4-49a3-4d69-9457-3c6e89f1bc91)

Amplitude of 24h cycle
![image](https://github.com/melliemainguyen71/wind_speed_land_sea_contrast/assets/98959461/10ce0d7b-86c3-43ae-87df-ec4f8b0f17eb)

Amplitude of 12h cycle
![image](https://github.com/melliemainguyen71/wind_speed_land_sea_contrast/assets/98959461/e75e7c7f-6abc-48d0-9724-563c4add1bd1)

Standard error of residuals
![image](https://github.com/melliemainguyen71/wind_speed_land_sea_contrast/assets/98959461/8856a113-9008-4daf-9e90-01ea0326b901)
