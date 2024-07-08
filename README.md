# Cloud Forensics with XGBoost

This repository contains a Jupyter Notebook that demonstrates the application of the XGBoost algorithm for cloud forensics. The data is imbalanced since the majority of records are normal and very few of them are attacked. There are parameters to consider in XGB to handle the imbalanced data and consider the ratio. This notebook includes data preprocessing, feature engineering, model training, evaluation, and visualization of results.

## Requirements

To run the notebook, you will need the following Python libraries:

- pandas
- numpy
- seaborn
- matplotlib
- plotly
- scikit-learn
- xgboost
- joblib

## Clone the Repository:

git clone https://github.com/Yasamanne/cloud-forensics-xgb.git

cd cloud-forensics-xgb

## Install the required packages:

pip install -r requirements.txt

Run the notebook:
Follow the steps in the notebook to preprocess the data, train the XGBoost model, evaluate its performance, and visualize the results.

Contents:

Data Preprocessing: Steps to clean and prepare the data for modeling.
Feature Engineering: Techniques to create new features that enhance model performance.
Model Training: Training the XGBoost model on the prepared dataset.
Model Evaluation: Evaluating the performance of the trained model using various metrics.
Visualization: Visualizing the results to gain insights from the model.


## License

    Copyright [2024] [Yasaman Emami]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
