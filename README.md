# Propulsion_Plants_Maintenance_Prediction
Gas Turbine and Compressor Decay State Coefficients Prediction

In the current project the Predictive Maintenance estimator models are built to predict the Gas Turbine and Compressor decay state coefficients;
the models are based on ML and DL concepts; the problem solved is a classical regression task. Among the tested algortihms are linear and ensemble models, as well as Neural Networks. The accuracy of the estimated target values are evaluated using mean aboslute error, mean squared error, as well as the absolute error for each individual measurement point.
The target functions (Gas Turbine and Compressor decay state coefficients) are predicted based on the propulsion system sensors measurements (16 features): shaft torque, rate of revolutions, compressor inlet air temperature and pressure, turbine injection control and fuel flow. 

The dataset used can be downloaded from the [UCI repository](https://archive.ics.uci.edu/ml/datasets/Condition+Based+Maintenance+of+Naval+Propulsion+Plants), or can be found in the [_data_](https://github.com/Mirlenko/Propulsion_Plants_Maintenance_Prediction/tree/main/data) folder. 

The project work is inspired by the original paper _Condition-Based Maintenance of Naval Propulsion Systems with Supervised Data Analysis_.
