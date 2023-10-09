# masterthesis-anomalie
This repository contains the supported code and summaries for the master thesis: 'Reproduction of Selected State-of-the-Art Methods of Anomaly Detection in Time Series Using Generative Adversarial Networks.'

### Content
1. Data preparation and Simulation Beispiele ccontain the following:

- Examples from the theoretical part (in 'another_examples_theory.ipynb').

- Labelling and analysis of the NAB Dataset for stationarity (in 'NAB anomaly labelled.ipynb', 'NAB_Summary_anomalies.ipynb', and 'stationarity_NAB.ipynb').

- Data preparation for the Weather Dataset for analysis from raw signals ('temperature_data_prep.ipynb' for temperature data and 'pressure_data_prep.ipynb' for pressure data). The analysis of stationarity for signals from the Weather Dataset is provided in 'stationarity_weather.ipynb'.

- Boxplots for signals from both the NAB and Weather Datasets are available in 'boxplots.ipynb'.

The code was written by the author of this repository.

2. ARIMA
This folder contains anomaly detection using the ARIMA method for monthly average temperature ('Anomaly_detection_arima_temperature.ipynb') and pressure ('Anomaly_detection_arima_pressure.ipynb') signals from the Weather Dataset.

The code was written by the author of this repository.

3. This folder contains code for reproducing the TAnoGAN GAN-based anomaly detection.

Source of code: https://github.com/mdabashar/TAnoGAN/tree/master

4. TadGAN:
This code contains a notebook for reproducing the results ('TadGAN.ipynb') and for applying the TadGAN method to anomaly detection in daily average temperature ('TadGAN_weather.ipynb') and pressure ('TadGAN_pressure.ipynb') signals.

Source of code: https://github.com/sintel-dev/Orion/tree/master

In the notebook for detecting anomalies in Weather Data, a minor adjustment was made by the author of this repository (in Data preprocessing and plotting).

### Datasets
1. NAB Numenta Anomaly Benchmark.

Source: https://github.com/numenta/NAB/tree/master

2. Weather Dataset
The Weather Dataset comprises signals for temperature and pressure values measured in Bamberg (weather station 282) over the period from 1961 to 2020.

Source: https://opendata.dwd.de/climate_environment/

