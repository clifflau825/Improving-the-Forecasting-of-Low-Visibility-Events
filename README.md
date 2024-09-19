# Improving-the-Forecasting-of-Low-Visibility-Events
This is a repository for my ongoing dissertation project as a master's student in the MSc Data Science and Analytics program at the University of Leeds, in cooperation with the UK Met Office.

Nowadays, our weather or atmospheric conditions are forecasted primarily using state-of-the-art physical models called Numerical Weather Prediction (NWP). However, some have suggested that the forecasts for visibility are far worse than for other atmospheric-oceanic variables. This project aims to perform post-processing on raw NWP visibility outputs using non-parametric methods to improve forecast reliability. Inputs of the post-processing model may include original NWP visibility forecasts and other potentially useful atmospheric-oceanic variables from NWP.

The dataset used in this project is the Eumetnet Post-Processing Benchmark (EUPPBench) dataset, which contains time-aligned forecasts, reforecasts (hindcasts), and observations to facilitate NWP post-processing. Its spatial domain targets stations scattered over central eastern Europe, covering the period from 1997 to 2018. Please refer to the paper "The EUPPBench Post-Processing Benchmark Dataset v1.0" by Demaeyer et al. (2023) for details on the dataset, and the GitHub repository (https://github.com/EUPP-benchmark/climetlab-eumetnet-postprocessing-benchmark/tree/main) for information about data extraction.

The preliminary model is built upon inputs of NWP visibility outputs, station altitudes and air temperature, to model observed visibility. Preliminary models show improvements in forecast performance over all forecast periods (from 6 hours up to 12 hours), which are evaluated using root-mean-square error.

This repository contains .ipynb files used in this project, including data pre-processing, exploratory data analysis, model building, and results evaluation.

If you have any questions regarding my project, please feel free to contact me via email at mm23cyl@leeds.ac.uk.

Reference:
Demaeyer, J., Bhend, J., Lerch, S., Primo, C., Van Schaeybroeck, B., Atencia, A., Ben Bouallègue, Z., Chen, J., Dabernig, M., Evans, G., Faganeli Pucer, J., Hooper, B., Horat, N., Jobst, D., Merše, J., Mlakar, P., Möller, A., Mestre, O., Taillardat, M., & Vannitsem, S. (2023). The EUPPBench post-processing benchmark dataset v1.0. Earth System Science Data, 15(6), 2635–2653. https://doi.org/10.5194/essd-15-2635-2023

Author: Cheuk Yin Lau (Cliff)


MSc Data Science and Analytics, University of Leeds

Add something.
