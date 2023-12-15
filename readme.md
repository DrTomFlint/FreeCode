# A Jupyter Notebook dedicated to the Calorimeter Project
Power losses in a motor drive are estimated by measuring the heat given off during operation.
Most of the controller and data acquisition system are hosted on a Raspberry Pi 4.
A Python Flask application collects data, stores it in an SQLite database, and makes it available on a webpage with jChart.
Training data will be created using a calibration heater.
Machine learning algorithms will be used to estimate the power loss based on temperature readings.
