# DS-4002-Project-2: Spotify Song Features Time Series Analysis

## Software & Platform
For data preprocessing, we used Jupyter Notebook with Python.  The “pandas” package needs to be installed for data preprocessing.  EDA visualizations were completed with python in a notebook file.  The “pandas” and “matplotlib” python packages were used for the visualizations.  “Matplotlib” and “pandas” need to be installed to regenerate these visualizations.  

For modeling, analysis, and evaluation with the SARIMA model, we used RStudio with R inside an R markdown file.  The packages used in these steps were “tidyverse”, “tseries”, “forecast”, “tsibble”, and “feasts”.  These packages need to be installed for modeling, analysis, and evaluation.  

All work was also completed on Mac OS.  

## Map of Documentation
```
DS-4002-Project-2 Folder Outline
│
├── DATA
│   ├── Data_Appendix_DS4002_Group1_Project2.pdf
│   ├── averages_year_month.csv
│   ├── cleaned_data.csv
│   └── data.csv
│
├── OUTPUT
│   └── 
│
├── SCRIPTS
│   ├── Data_Prepocessing.ipynb
│   ├── eda.ipynb
│   ├── evaluation.ipynb
│   └── sarima_modeling.Rmd
│
├── LICENSE
│
└── README.md
```

## Instructions for Reproduction of Results
To reproduce our results, first download the data from the DATA directory titled ‘SpotifyData.csv’.  Be sure to install the packages required for data preprocessing, these packages are listed in the Software & Platform section of this README file.  After this, run the ‘Data_Preprocessing.ipynb’ script found in the SCRIPTS directory.  This will produce the cleaned data file and a file with the average of song features by month by year in .csv format.  Once these files are produced, ensure these .csv files are in the DATA directory.

Complete the SARIMA modeling and evaluation process by first installing the five packages in R listed above in this README. Download the 'sarima_modeling.Rmd' script from the SCRIPTS folder and run the entire thing using R. Make sure to have the cleaned data files (specifically 'averages_year_month.csv') in the same location, or set working directory to the location of the data prior to running the script. All results should mimic the relevant output as found in the OUTPUT file exactly. 

## References
[1] calebelgut, “GitHub - calebelgut/spotify-lstm: Classification & Time Series Analysis of Spotify Data using Grid Searched Random Forest & LSTM.,” GitHub, 2025. https://github.com/calebelgut/spotify-lstm (accessed Feb. 25, 2026).

[2]	Mark Mulligan, “Music subscriber market shares Q2 2021,” MIDiA, Jan 18, 2022. https://www.midiaresearch.com/blog/music-subscriber-market-shares-q2-2021#:~:text=Spotify%20remains%20the%20DSP%20with,for%20the%20second%20successive%20year. (accessed Feb. 27, 2026).

[3]	Xiaolei Liu, Zi Lin, Ziming Feng, “Short-term offshore wind speed forecast by seasonal ARIMA - A comparison against GRU and LSTM,” Energy (Volume 227), Jul 15, 2021. https://www.sciencedirect.com/science/article/abs/pii/S0360544221007416#sec6 (accessed Feb. 27, 2026).

[4]	Paliari et al., “A comparison of the optimized LSTM, XGBOOST and ARIMA in Time Series forecasting,” 2021 12th International Conference on Information, Intelligence, Systems & Applications (IISA), 2021. https://ieeexplore.ieee.org/abstract/document/9555520 (accessed Feb. 27, 2026).

[5]	Jason Brownlee, “A Gentle Introduction to SARIMA for Time Series Forecasting in Python,” Machine Learning Mastery, Aug. 16, 2018. https://machinelearningmastery.com/sarima-for-time-series-forecasting-in-python/

[6]	Kontopoulou et al., “A Review of ARIMA vs. Machine Learning Approaches for Time Series Forecasting in Data Driven Networks,” Future Internet, 2023. https://www.mdpi.com/1999-5903/15/8/255 (accessed Feb. 27, 2026).
