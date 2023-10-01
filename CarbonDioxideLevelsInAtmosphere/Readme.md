# Carbon Dioxide Levels in Atmosphere 1958-2017, 2018-2022

Time Series Analysis of real time Carbon Dioxide Levels in Atmosphere 1958-2017. and predict values for each month of 2018-2022.

The carbon dioxide record from Mauna Loa Observatory, known as the “Keeling Curve,” is the world’s longest unbroken record of atmospheric carbon dioxide concentrations. Scientists make atmospheric measurements in remote locations to sample air that is representative of a large volume of Earth’s atmosphere and relatively free from local influences.

This dataset includes a monthly observation of atmospheric carbon dioxide (or CO2) concentrations from the Mauna Loa Observatory (Hawaii) at a latitude of 19.5, longitude of -155.6, and elevation of 3397 meters.

The data is sourced from [Kaggle, Carbon Dioxide Levels in Atmosphere]([https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1310041501&pickMembers%5B0%5D=3.1&cubeTimeFrame.startYear=2012&cubeTimeFrame.endYear=2022&referencePeriods=20120101%2C20220101](https://www.kaggle.com/datasets/ucsandiego/carbon-dioxide))

## Method
Employ Jupyter Notebook to execute Meta Prophet using Python to estimate the predicted live 2018-2022 CO2 levels.

## Analysis

### Forecast
CO2 levels between 1958-2017 follow a consistent seasonal pattern each year. The pattern repeats 2018-2022.
![image](https://github.com/gitgizmo/TimeSeriesAnalysis/assets/16417298/c5f37a32-7256-4a38-8f48-6071b439fa88)

### Trend
CO2 levels between between 1958 and 2017 present a trend where CO2 levels trend upwards in a non-linear fashion. 2018-2022 continues the trend with a narrow level of uncertainty.
![image](https://github.com/gitgizmo/TimeSeriesAnalysis/assets/16417298/ff228887-04ed-465d-abee-53ffabd2f75f)


### Seasonality
CO2 levels between between 1958 and 2017 seasonal patterns present a wave like pattern that begin in January and peaks late April. At that point there is a sharp decline to early September where it begins a steady climb throughout the fall.
![image](https://github.com/gitgizmo/TimeSeriesAnalysis/assets/16417298/a7c691d0-8e54-45ed-8315-458f51a8db85)






