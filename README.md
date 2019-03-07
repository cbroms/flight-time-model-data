# Fly Genius Data Visualization and Processing

This branch stores the original data files used in the FlyGenius API as well as any visualization, data processing, and model building scripts that require the original data. 

The data can be found in the `data/flight-data/` directory, organized into subdirectories based on the month and year each file contains data for. 

### Data Processing

The most up to date data processing scripts can be found in `processing/v2/`. The file `process_data.py` aggregates the data and creates the entries for airlines, airports, and routes, descibed in more detail [here](https://github.com/CBR0MS/flight-time-model-api/blob/master/README.md#resources-in-the-api). The file `send_data_to_api.py` creates the individual json objects and keys and patches the data in the API for each resource. The file `create_model.py` creates and trains the model used to make predictions. 

The `processing/v1/` directory contains scripts used to make the models in the original version of the site. 

### Data Visualization

This branch is for visualization of flight data as well. The jupyter notebooks are organized by the website's versions: 

 - [FlyGenius v.1 Dataviz](https://github.com/CBR0MS/flightTimeModel/blob/docs/Flight%20Time%20Modeling.ipynb)

