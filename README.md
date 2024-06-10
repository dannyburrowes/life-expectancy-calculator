# WHO Life Expectancy Predictor
This project is a machine learning tool designed to predict the life expectancy of an individual based on various input parameters. The source data for this project is provided by the World Health Organization (WHO).

## Table of Contents
Introduction\
Features\
Installation\
Usage\
Demonstration

## Introduction
The WHO Life Expectancy Predictor uses a linear regression model to estimate the life expectancy of a person. Users can input various health and socio-economic factors to get a prediction. This project includes a Python script that prompts users for input and processes it to make predictions. The function utilises two different models: the best performing model and the minimal model. The best performing model has been trained on all of the available data to predict life expenctancy as accurately as possible, whereas the minimal model has not been trained on data that may include sensitive information. Data that we deemed to be "sensitive" included all financial and medical-related data.

## Features
Predict life expectancy based on user inputs.\
Two models for prediction: Minimal Model and Best Performing Model.
* Minimal Model: Excludes sensitive information.
* Best Performing Model: Uses all available features.
  
Use advanced population data for more accurate predictions.\
Case-insensitive input handling.

## Installation
To use the WHO Life Expectancy Predictor, you need to have Python installed. You also need the following Python libraries:\

pandas\
numpy\
matplotlib\
seaborn\
You can install these libraries using pip:\

pip install pandas numpy matplotlib seaborn\

## Usage
Clone the repository:\
git clone https://github.com/yourusername/who-life-expectancy-predictor.git\
cd who-life-expectancy-predictor\
Ensure you have the necessary CSV files (bp_model.csv and minimal_model.csv) in the same directory as the script.\
Run the Python script:\
python life_expectancy_predictor.py\
Follow the prompts to enter the necessary data.

## Demonstration
![1](https://github.com/dannyburrowes/life-expectancy-calculator/assets/130167847/54d949f3-cb19-447b-8434-e0a4049c2048)
![2](https://github.com/dannyburrowes/life-expectancy-calculator/assets/130167847/4b437350-68f3-4c3d-9eaa-198e78ef2fe8)
![3](https://github.com/dannyburrowes/life-expectancy-calculator/assets/130167847/a8aa8ddf-fec2-48e2-816c-cf9fe0ded45b)
![4](https://github.com/dannyburrowes/life-expectancy-calculator/assets/130167847/bdc89ae3-661a-41c8-b1c2-2690688dbd57)
![5](https://github.com/dannyburrowes/life-expectancy-calculator/assets/130167847/b75897e8-bba3-4b8d-895f-24a75a83c2a1)
