# Improving-the-Forecasting-of-Low-Visibility-Events
This is a respository for my on-going dissertation project as a master student in MSc Data Science and Analytics at the University of Leeds in co-operation with the UK Met Office. 

Nowadays, our weather or atmospheric conditions are forecasted primarily using state-of-art physical models called Numerical Weather Prediction (NWP). However, some suggested that the forecasts for visibility are far worse than other atmospheric-oceanic variables. This project aims to perform post-processing on raw NWP visibility outputs using non-parametric methods to improve forecast reliability. 

The dataset used in this project is the Eumetnet Post-Processing Benchmark (EUPPBench) dataset, which contains time-aligned forecasts, reforecasts (hindcasts) and observations, to facilite NWP post-processing. Its spatial domain targets on stations scattered over central eastern Europe, covering the period 1997 to 2018. Please refer to the paper "The EUPPBench postprocessing benchmark dataset v1.0" by Demaeyer in 2023 for details on the dataset, and the GitHub respository (https://github.com/EUPP-benchmark/climetlab-eumetnet-postprocessing-benchmark/tree/main) about data extraction. 

Preliminary model shows improvements in forecast performance over all forecast periods (6 hours up to 12 hours), which are evaluated using root-mean-square error . 

This respository contains ipynb files used in this project from data pre-processing, exploratory data analysis, model building, and results evaluation. 

If you have any questions regarding my project, please feel free to contact me via email on mm23cyl@leeds.ac.uk.

Author: Cheuk Yin Lau (Cliff)
Organisation: MSc Data Science and Analytics, University of Leeds
