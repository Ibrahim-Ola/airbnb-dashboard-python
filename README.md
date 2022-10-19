# Data Visualization

This repository is basically about data visualization in Python. If you find this content helpful, please consider leaving **star** on this repository.

## Structure

Our visualization is grouped into two sections: 

1. Data visualization using Python packages.
2. Interactive dashboard creation using the [Panel](https://panel.holoviz.org/index.html) library.

## Dataset

The dataset used in this projectis publicly available on [kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data). The dataset contains properties of Airbnb apartments in New York City.

## Using this code

The easiest way to use this code by clonning this repository. To clone this repositort type:

```{none}
 https://github.com/Ibrahim-Ola/airbnb-dashboard-python.git
```

## Required Libraries

All packages needed comes pre-installed in Anaconda except; `geopandas`, `panel`, and `holoviews`. Install the packages using the following:

```{none}
 conda install --channel conda-forge geopandas
```
```{none}
 conda install -c conda-forge panel
```
```{none}
 conda install -c conda-forge holoviews
```

## Deploying the Dashboard

```
 panel serve Dashboard.ipynb
```

## Dashboard Preview

![alt text](https://github.com/Ibrahim-Ola/airbnb-dashboard-python/blob/main/images/dashboar_preview.png)

