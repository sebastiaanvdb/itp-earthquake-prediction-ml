# Kaggle LANL Earthquake Challenge

The goal of this repository is to collaborate and find a good performing strategy for [this](https://www.kaggle.com/c/LANL-Earthquake-Prediction/overview) Kaggle challenge. Baseline notebook is based on pre-processing steps of [this kernel](https://www.kaggle.com/latimerb/lanl-getting-started-mlp-rf-ensembles).

## Usage
First follow instructions on [this](https://github.com/Kaggle/kaggle-api#api-credentials) repository to export your Kaggle credentials under the form of a json file.
- To enter virtual inveronment: ```pipenv shell```
- To download and unzip Kaggle data: ```make init```
- To run notebook: ```jupyter notebook``` and run "benchmark_submission.ipynb"
- To submit predictions: ```make submit FILE="PATH-TO-CSV" MESSAGE="SUBMISSION MESSAGE"```

 
