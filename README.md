# CO2 Emissions Prediction using Sentinel-5P Data

![CO2 Emissions](https://www.bing.com/images/create/panoramic-image-of-africa-with-smoke-covering-rwan/64da3960f1cc4147b3cf15abf51c6e7f?id=IQP600KX5tNpWcPSgqKLeQ%3D%3D&view=detailv2&idpp=genimg&idpclose=1&form=SYDBIC)

## Introduction

This repository contains a Jupyter Notebook that demonstrates how to predict CO2 emissions in Rwanda using open-source data from Sentinel-5P satellite observations. The notebook aims to create machine learning models that utilize emissions data to forecast carbon emissions, contributing to the understanding of carbon emissions patterns and enabling governments and organizations to estimate carbon emission levels across Africa.

## Dataset

The dataset includes data collected from approximately 497 unique locations in Rwanda. Weekly features were extracted from Sentinel-5P satellite observations. These features encompass Sulphur Dioxide, Carbon Monoxide, Nitrogen Dioxide, Formaldehyde, UV Aerosol Index, Ozone, and Cloud information.

## Notebook Contents

### 1. Data Preprocessing

In this section, the dataset is cleaned, missing values are handled, and the features are normalized using Min-Max scaling.

### 2. Feature Engineering

This section focuses on extracting meaningful information from the raw data. New features are created, and existing ones are transformed to prepare the dataset for model training.

### 3. Model Building

The notebook demonstrates the implementation of a deep learning model for CO2 emissions prediction. The model architecture includes LSTM layers and dense layers with appropriate activation functions.

### 4. Training and Evaluation

The model is trained on the preprocessed data and evaluated using metrics such as mean squared error (MSE) to assess its prediction accuracy.

## Getting Started

1. Clone this repository to your local machine:
git clone https://github.com/Dev-ASingh/Rwanda_CO2_emission_prediction.git

2. Open the Jupyter Notebook using your preferred environment.

3. Install any required packages using the following command:
pip install -r requirements.txt

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
