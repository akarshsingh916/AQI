Let us see how to predict the air quality index using Python. AQI is calculated based on chemical pollutant quantity. By using machine learning, we can predict the AQI.

AQI: The air quality index is an index for reporting air quality on a daily basis.  In other words, it is a measure of how air pollution affects one’s health within a short time period. The AQI is calculated based on the average concentration of a particular pollutant measured over a standard time interval. Generally, the time interval is 24 hours for most pollutants, 8 hours for carbon monoxide and ozone.

We can see how air pollution is by looking at the AQI

AQI Level with AQI Range:

Good	0 – 50

Moderate	51 – 100

Unhealthy	101 – 150

Unhealthy for Strong People	151 – 200

Hazardous	201+




Let’s find the AQI based on Chemical pollutants using Machine Learning Concept. 




Data Set Description:



It contains 8 attributes, of which 7 are chemical pollution quantities and one is Air Quality Index.
PM2.5-AVG, PM10-AVG, NO2-AVG, NH3-AVG, SO2-AG, OZONE-AVG are independent attributes. air_quality_index is a dependent attribute. Since air_quality_index is calculated based on the 7 attributes.

As the data is numeric and there are no missing values in the data, so no preprocessing is required. Our goal is to predict the AQI, so this task is either Classification or regression. So as our class label is continuous, regression technique is required.

Regression is supervised learning technique that fits the data in a given range. Example Regression techniques in Python:

Random Forest Regressor

Ada Boost Regressor

Bagging Regressor

Linear Regression etc.

