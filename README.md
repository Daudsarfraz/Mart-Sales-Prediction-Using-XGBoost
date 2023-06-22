# Mart Sales Prediction using XGBoost Algorithm
![Untitled design](https://github.com/Daudsarfraz/Mart-Sales-Prediction-Using-XGBoost/assets/87930468/a4cf659b-2d4e-47a9-9373-0f8c18030416)

This project aims to predict sales in a mart using the XGBoost algorithm. XGBoost is a powerful and widely-used machine learning algorithm known for its high performance in regression and classification tasks.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
The goal of this project is to develop a predictive model that can estimate the sales of products in a mart. The XGBoost algorithm is employed due to its ability to handle complex relationships between features and produce accurate predictions.

The project includes the following key steps:
1. Data preprocessing: Cleaning, transforming, and encoding the dataset to prepare it for model training.
2. Feature engineering: Creating new features or extracting useful information from existing features to improve model performance.
3. Model training: Utilizing the XGBoost algorithm to train a regression model on the prepared dataset.
4. Model evaluation: Assessing the performance of the trained model using appropriate evaluation metrics.
5. Model deployment: Saving the trained model for future predictions on new data.

## Dataset
The dataset used in this project contains historical information about products and their corresponding sales in the mart. It includes features such as 'Item_Identifier', 'Item_Weight', 'Item_Fat_Content', 'Item_Visibility',
       'Item_Type', 'Item_MRP', 'Outlet_Identifier',
       'Outlet_Establishment_Year', 'Outlet_Size', 'Outlet_Location_Type',
       'Outlet_Type', 'Item_Outlet_Sales'. The dataset is expected to be in a structured format, preferably in a CSV file.

## Prerequisites
Before running this project, ensure that you have the following dependencies installed:
- Python (version 3.6 or above)
- Pandas
- NumPy
- XGBoost

## Installation
1. Clone this repository to your local machine or download the project files.
2. Install the required dependencies using the following command:
3. '!pip install pandas numpy xgboost'


## Usage
1. Place the dataset file (e.g., `Train.csv`) in the project directory.
2. Modify the configuration settings in the script according to your dataset and requirements.
3. Run the 'Jupyter Notebook downloaded' 

## Results
After running the script, the model will be trained on the provided dataset, and the evaluation results will be displayed. The results may include metrics such as mean squared error (MSE), mean absolute error (MAE), and R-squared value.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to create a pull request.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute this code as needed.

