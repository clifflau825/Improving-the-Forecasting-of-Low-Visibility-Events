# Improving-the-Forecasting-of-Low-Visibility-Events
This is a repository for my master dissertation project as a student of the MSc Data Science and Analytics programme (2023-24) at the University of Leeds, in collaboration with the UK Met Office.

Nowadays, our weather or atmospheric conditions are forecasted primarily using state-of-the-art physical models called Numerical Weather Prediction (NWP). However, some have suggested that the forecasts for visibility are far worse than for other atmospheric-oceanic variables.This study aims to explore various non-parametric (decision- tree-based) methods, specifically random forest regression and quantile regression forest, or model building approaches, to calibrate NWP visibility ensemble forecasts to create a determin- istic and a probabilistic forecast represented by an ensemble of predictions for calibrated visibil- ity with higher accuracy levels. The Integrated Forecasting System (IFS) ensemble forecasts for visibility from the European Centre for Medium-Range Weather Forecasts (ECMWF) with 6 to 120 hrs lead times are post-processed.

The dataset used in this project is the Eumetnet Post-Processing Benchmark (EUPPBench) dataset, which contains time-aligned forecasts, reforecasts (hindcasts), and observations to facilitate NWP post-processing. Its spatial domain targets stations scattered over central eastern Europe, covering the period from 1997 to 2018. Please refer to the paper "The EUPPBench Post-Processing Benchmark Dataset v1.0" by Demaeyer et al. (2023) for details on the dataset, and the GitHub repository (https://github.com/EUPP-benchmark/climetlab-eumetnet-postprocessing-benchmark/tree/main) for information about data extraction. 

Results show that the decision-tree-based post-processing models substantially improve the performance of visibility forecasts for all lead times, including low-visibility events, compared with the parametric models. The conclusion is based on root-mean-square error (RMSE) for deterministic forecasts and mean continuous ranked probability score (CRPS) for ensemble forecasts.

Please refer to my final report for detailed information on the methodology and analysis, which is available at xxx.

This repository contains the scripts (.ipynb files) used in this project, including data pre-processing, exploratory data analysis, model building, and results analysis. Raw data are preprocessed to produce dataframes for training (df_test.csv), validation (df_valid.csv) and testing (df_test.csv) using the scripts inside the "Data Preprocessings" directory. The analysis on the probability distribution of ensemble forecasts is conducted using the script inside the "Exploratory Data Analysis" directory. The post-processing models are built using the scripts inside the "Model Building" directory. The run times of different training different models are recorded in the text file "Run time records.txt". The performance of the models are analysed using the scripts inside the "Performance Analysis" directory. The trained models are saved as .pkl files inside the "trained_models" directory and the test results of different models are exported as dataframes inside the "test_results_df" directory. The saved models and test results are available for downloading via OneDrive share links. 

If you have any questions regarding my project, please feel free to contact me via email at clifflau825@gmail.coom.

Reference:
Demaeyer, J., Bhend, J., Lerch, S., Primo, C., Van Schaeybroeck, B., Atencia, A., Ben Bouallègue, Z., Chen, J., Dabernig, M., Evans, G., Faganeli Pucer, J., Hooper, B., Horat, N., Jobst, D., Merše, J., Mlakar, P., Möller, A., Mestre, O., Taillardat, M., & Vannitsem, S. (2023). The EUPPBench post-processing benchmark dataset v1.0. Earth System Science Data, 15(6), 2635–2653. https://doi.org/10.5194/essd-15-2635-2023

Author: Cheuk Yin Lau (Cliff)


MSc Data Science and Analytics (2023-24), University of Leeds
