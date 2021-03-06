# Wind-Speed-Prediction
## Datasets:

### Description:

The datasets contain the weather of **Berlin, Germany** `(lat = 52.5246, lon = 13.3946)` from `1995` to `2004`

- `dataset-monthly.csv` contains the Month wise dataset (1)
- `dataset-daily.csv` contains day by day dataset (2)

Despriction of Both the datasets `dataset-daily.csv` and `dataset-monthly.csv` has given below:

|             | time                      | air_temperature_mean | pressure | wind_direction | wind_speed |
|-------------|---------------------------|----------------------|----------|----------------|------------|
| Unit        | YYYY/MM (1) / YYYY/MM/DD (2) | degC                 | hPa      | deg            | m/s        |
| description | Time as per Gregorian calendar | Mean temperature at 2 m height | Mean air pressure at sea level | Wind direction in 10 m height | Mean wind speed at 10 m height |
| Minimum | **1995/01** (1) / **1995/01/01** (2) | **-3.6** (1) / **-13.7** (2)  | **1005.6639** (1) / **984.4167** (2)  | **7** (1) / **0** (2)     | **2.3** (1) / **0.7** (2) |
| Maximum | **2004/12** (1) / **2004/12/31** (2) | **23** (1) / **30.6** (2)     | **1025.2272** (1) / **1045** (2)      | **359** (1) / **359** (2) | **5.2** (1) / **10.3** (2) |
| Mean | --                               | **10.689** (1) / **10.6** (2) | **1015.56** (1) / **1015.565916** (2) | **225.425** (1) / **200.6731** (2) | **3.4691**(1) / **3.46367** (2) |
| Standard Deviation | --                 | **7.2192** (1) /  **7.9858** (2) | **3.7031** (1) / **9.2113** (2) | **68.5984** (1) / **90.7423** (2) | **0.5982** (1) / **1.458** (2) |

- (1) - is the monthly dataset 
- (2) - is the daily dataset

### Other Content:

- #### Create-Dataset notebooks
    1. create-dataset-monthly.ipynb
    2. create-dataset-daily.ipynb

- #### Testing notebooks
    1.  netCDF-test-monthly.ipynb

- #### Notebooks on CNN_LSTM
    1.  LSTM_weather_daily.ipynb
    2.  LSTM_requisite_model.txt(Textfile for further utility)
    3.  LSTM_model.py(Python file to build model)

- #### LICENSE:-
     Apache License 2.0 
