# Data-Visualization-and-Exploration-Assignment-2
## Data Visualization and Exploration Assignment 2: Time Series and Geospatial Data Analysis
Assignment 2 requires basic data cleaning and exploration techniques on prescribed datasets (NYC Taxi data available on Kaggle).
The aim is to explore the dataset and make observations. The dataset is one released by the NYC Taxi and Limousine Commission (TLC), which includes
pickup time, geo-coordinates, number of passengers, and several other variables for 1.5 million trips between 2016-01-01 and 2016-06-30. For this analysis we only explore the train dataset

## Assignment 2 Resources
**Project Notebook:** https://colab.research.google.com/drive/1YaL8bF2OtsO35PggcYbS1KKqOO5fmhIc <br>
**NYC Taxi Dataset:** https://www.kaggle.com/c/nyc-taxi-trip-duration
**Assignment 2 Package installation Process on CMD/Anaconda Prompt:** <br>
- 
```
> conda create -n dve_assignment2_env
> condata activate dve_assignment2_env
> conda config --env --add channels conda-forge
> conda config --env --set channel_priority strict
> conda install geopandas
> cond install -c conda-forge geoplot
> cond install -c conda-forge geocoder
> cond install -c conda-forge hdbscan
> cond install -c conda-forge utm
> cond install -c conda-forge colour
> cond install -c conda-forge imageio
> conda install jupyter notebook
> python -m ipykernel install --name dve_assignment2_env
> jupyter notebook
```

