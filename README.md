• Trained Built a stacked LSTM network (Tensorflow/Keras) to predict the remaining useful life (RUL) of aircraft turbofan from multivariate sensor time-series using the FD001 subset of NASA’s C-MAPSS run-to-failure benchmark.


• Achieved a test RMSE of 14.4 cycles (MAE 10.5) and a C-MAPSS asymmetric score of 370 on the 100 engine FD001 test set.


• Applied SHAP (GradientExplainer) to the trained LSTM to attribute each RUL prediction to individual sensors and time steps. The Top-ranked channels (HPC static pressure Ps30, fuel-flow ration) matched FD001’s seeded high-pressurecompressor degradation fault mode.


• Tools used: Tensorflow/Keras, SHAP, NumPy, Python, Matplotlib
