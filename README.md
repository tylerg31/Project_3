# Project 3: A Denver Housing Predictor
This is our Fintech Bootcamp final project that utilize primarily Jupyter Notebook as well as Google Colab to create applications in regards to the Denver housing market. We sourced our Denver Data csv file from Zillow, whicha ccurately gives us the prices of each respective neighborhood over a certain timeframe; the usa housing data csv file was also sourced from Zillow to convey neighborhoods, counties, and cities across the nation over a timeframe; and the neighborhood latitude and longitude csv file came from Google Maps. We utilized these data files to create applications that produced result forecasts and predictions.
---

## Technologies & Libraries

This project utilizes python 3.7 with the following:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [Numpy](https://github.com/numpy/numpy) - The fundamental package for scientific computing with Python.

* [Hvplot](https://github.com/holoviz/hvplot) - A high-level plotting API for pandas, dask, xarray, and networks built on HoloViews.

* [Metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

* [Datetime](https://github.com/datetime) - Fundamental understanding of library and uses.


---
## Result Images

### Mean Squared Error Value Epoch Training

![MSE Training](https://user-images.githubusercontent.com/117557983/234738973-d0fc3b29-17b5-4cf2-a6c9-999d5d17b200.png)

### Denver Housing Gradient Regressor

![Gradient Regressor](https://user-images.githubusercontent.com/117557983/234738993-936c9fc3-184a-4bac-8031-dfac2ac83154.png)

### Denver Annual Sales

<img width="1191" alt="Denver Sales Year" src="https://user-images.githubusercontent.com/117557983/234742597-ed1b2488-9c1c-4a5f-b6c8-470fc3027324.png">

### Neighborhood Annual Sales

<img width="1219" alt="Neighborhood Sales Year" src="https://user-images.githubusercontent.com/117557983/234742668-cf77c065-5a7e-4099-a64e-d280ad9a71f1.png">

--- 

## Pre Installation Guide

Prior to running this application, please first install the following dependencies:

```
import pandas as pd
import numpy as np
import datetime
import hvplot.pandas
import matplotlib.pyplot as plt
from pathlib import Path
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_squared_error
from sklearn.ensemble import GradientBoostingRegressor
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense
from tensorflow.keras.optimizers import Adam
from sklearn.metrics import mean_squared_error
```

---

## Contributors

Ben Lindauer
Terrence Mccoy
Tyler Goering
Jacob Macpherson
Evan Badding

---

## License

MIT
