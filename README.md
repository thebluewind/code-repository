# code-repository
data files and code materials for 《Quantifying the polar mesoscale cyclones spectrum: a data-driven exploration of physical regimes and environmental drivers》
1.features_track.xlsx: Track-level features for 44,141 850-hPa vortex tracks identified over the Nordic Seas during the extended winter seasons (November–April) from January 2000 to April 2024. Each row represents one vortex track, and the columns correspond to the variables listed in Table S1.
2.PMCs_climate.txt: A collection of track IDs for the PMCs identified from features_track.xlsx using the XGBoost binary classification model.
3.PMCs_predict.ipynb: Code used to train and evaluate the XGBoost binary classification model for PMC identification.
4.ML_track_PMCs_regression_xgb.ipynb: Code for the XGBoost–SHAP regression model, with the maximum cyclone-associated 10-m wind speed as the regression target.
5.time_cluster.ipynb: Code used for lifecycle time-series clustering.
6.integrated_plot.ipynb: Code used to generate the figures showing the spatial distributions and composite characteristics of the PMC regimes.
