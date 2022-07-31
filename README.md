# Temporal-Processing-Recurrent-Neural-Network---Appliances-Energy-Prediction
Background and Methods:
Appliances Energy Prediction Data: This data set records the energy consumption at 10 min resolution for about 4.5 months. In addition, a ZigBee wireless sensor network monitored the house temperature and humidity conditions. The temperature and humidity conditions were averaged and logged for 10 minutes with m-bus energy meters. This study proposes time series forecast to predict energy consumption using the time-lagged and recurrent neural networks time-series modeling in the presence of covariates.
Pre-processing:
Correlation and partial-correlation plot to understand the dataset dynamics:
**Appliances Energy Prediction**
1. Creates the log of Appliances (i.e., the target variable) for the symmetric distribution of frequencies and improves model performance.
2. Scaled and normalized the dataset.
3. Inspect and clean the data.
4. Leverage sin and cos to convert the time to "Time of the day" and "Time of the year" signals. This gives the model access to the most critical frequency features.
