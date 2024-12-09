# Warehouse and Retail Sales Prediction

## Project Overview
This project predicts monthly retail and warehouse sales for three categories (wine, beer, and liquor). The goal is to help optimize inventory and improve efficiency.

## Dataset
The dataset is sourced from [Data.gov Warehouse and Retail Sales](https://catalog.data.gov/dataset/warehouse-and-retail-sales).


## Setup Instructions

### 1. Creating the Virtual Environment

To isolate project dependencies, create a virtual environment:

```
python -m venv venv
```

### 2. Activating the Virtual Environment

Activate the virtual environment with the following command:

```
source ./venv/bin/activate
```

### 3. Installing Required Libraries

Install all necessary libraries by running:

```
pip install -r requirements.txt
```

### 4. Running the Prediction Notebook

Open and execute the `project.ipynb` Jupyter Notebook to train and evaluate the model.

### 5. Result

The results include two graphs for each product category (wine, liquor, and beer). Each category has a Retail Sales Graph and a Warehouse Sales Graph showing the predicted sales and the actual sales.

Three values:

R² (R-squared): Measures how well the model explains the variability in the data; higher values indicate better predictions.

RMSE (Root Mean Squared Error): Represents the average difference between predicted and actual values; lower values mean more accurate predictions.

MAPE (Mean Absolute Percentage Error): Shows the percentage error in predictions relative to actual values; lower percentages indicate better accuracy.


