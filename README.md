# PRODIGY-DS-01

# Exploratory Data Analysis on Titanic Dataset

## Overview

This project is part of the internship program at Prodigy Infotech, focused on data science. It analyzes the Titanic dataset obtained from Kaggle. The dataset contains individual information regarding the travellers on the ship focusing their gender, age, ticket ID etc along with the target variable being whether individuals survived or not.

## Table of Contents

- [Data Loading](#data-loading)
- [Data Exploration](#data-exploration)

## Data Loading

The project starts with loading necessary libraries and importing the dataset using pandas. 

```python
import pandas as pd

# Loading the dataset
data = pd.read_csv('/kaggle/input/titanic/train.csv')
````
## Data Exploration

The relation between various variables are studied along with visualizations to support it. At the end XGB is applied for prediction.
