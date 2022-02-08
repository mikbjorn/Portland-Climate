# Climate Analysis of Portland, OR
Authors: Mikkel Bjornson, Dang Dinh, Jiefeng Chen
## Background
This timeseries analysis focuses on the modeling and forecasting of monthly precipitation, and monthly average minimum and maximum temperatures. With climates changing globally, it is important to identify how these effects are presenting locally. Weather data for Portland, OR is obtained from NOAA [1]. Multiple timeseries methods are attempted for each measurement. The models with the lowest root mean square error are used to forecast ten years into the future. 
## Goals
-	Identify both local seasonal changes and long-term trends in temperature and precipitation.
-	Forecast likely temperatures and precipitation for the next ten years. 
## Analysis and Findings
### Precipitation
The SARIMA model resulted in the lowest error rate of 1.88 (RMSE). This model found a regular seasonal pattern in precipitation. All three models indicate no longer term change. Precipitation appears to be following a regular unchanging pattern. 
### Average Monthly Minimum Temperatures
The ARMA model resulted in the lowest error (RMSE = 2.45), with the SARIMA model (RMSE = 2.47) coming in as a close second. There is a regular seasonal pattern with lower temperatures expected in the winter. There does appear to be a slight upward trend of about 0.0439 degrees Fahrenheit per year. 
### Average Monthly Maximum Temperatures
The SARIMA model resulted in the lowest error (RMSE = 3.01), but both other models performed almost as well (ARMA RMSE = 3.08, Holt-Winters RMSE = 3.09). Both seasonal change, and a long term increase are identified. The ARMA model estimated an annual increase of 0.039 degrees Fahrenheit per year. 
## Recommendations 
Increasing trends in both minimum and maximum average monthly temperatures appears to surpass the global estimates [2]. Portland appears to be getting warmer but is not getting any wetter. The increased temperatures may result in a water shortage, crop die out, or hydrologic drought. Decisions makers should start planning now for these outcomes. 
## Benefits
By identifying local climate change now, necessary changes can be identified and implemented. The preplanning for these changes can likely reduce the cost in terms of both life and finance. 
## Citation 
[1] weather.gov, NOAA, https://www.weather.gov/media/pqr/climate/pastdata/Portland_daily.csv

[2] NOAA National Centers for Environmental Information, State of the Climate: Global Climate Report
for Annual 2020, online January 2021, retrieved on March 15, 2021 from https://www.ncdc.noaa.gov/sotc/
global/202013.

