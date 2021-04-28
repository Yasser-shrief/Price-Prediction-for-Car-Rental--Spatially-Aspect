# Price-Prediction-for-Car-Rental--Spatially-Aspect

![](car aps.jpg)

The global car rental industry is expected to reach an estimated $120 billion by 2025 with a CAGR of 6.1% from 2020 to 2025.
However, after a long search, i was unable to access an open-source project related to it, and the data is also scarce.<br>

Finally, I found a database file consisted of a 330MB JSON file with a heavily nested format., that was extracted from the **(TURO) website.** consisted of 36000 car rental events.<br>
therefore I decided to make this project open source. I tried to explain step by step starting from reading the database file and converting it to flatten data through the EDA included the spatial analysis as well.<br>
and comparing between -`Random Forest and XGBoost`- to predict daily rent rates.
It's also includes how to deal with different data sources as I have added a population dataset.<br>

I did my best to explain the steps of hyperparameter tuning in details for beginners as well .
Packages used :<br>
**data visualization** : <br>
Plotly.<br>
Seaborn.<br>
Matplotlib.<br>
ggplot.

**Spatial analysis:**<br>
Geoviews .<br>
Folium .<br>
go.figure plotly.<br>
geopandas.

**hyperparameter tuning:** <br>
GridSearch.<br>
Randomsearch.<br>
manually.

To download data [here](https://www.kaggle.com/theriley106/turo-rental-car-pricing-info)
