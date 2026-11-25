# House Price Prediction using Apache Spark

## Project Overview

This project predicts house prices using Apache Spark, PySpark and Spark MLlib. It implements and compares two regression algorithms: Linear Regression and Decision Tree Regression.

## Technologies Used

- Python
- Apache Spark 3.5.9
- PySpark
- Spark MLlib
- Pandas
- Matplotlib

## Dataset

- 545 records
- 13 columns
- Includes house area, bedrooms, bathrooms, stories, parking and other features.

## Project Workflow

1. Load the housing dataset using Spark.
2. Check missing values and duplicate records.
3. Encode categorical features using StringIndexer.
4. Assemble features using VectorAssembler.
5. Split data into 70% training and 30% testing.
6. Train Linear Regression and Decision Tree Regression models.
7. Evaluate and compare both models using R², RMSE and MAE.

## Model Performance

| Metric | Linear Regression | Decision Tree |
| ------ | ----------------- | ------------- |
| R² | 0.6621 | 0.3422 |
| RMSE | 1028580.41 | 1435090.32 |
| MAE | 790887.26 | 1037644.64 |

Linear Regression performed better than Decision Tree Regression in this experiment.

## How to Run

1. Install Python and Jupyter Notebook.
2. Install PySpark:

   `pip install pyspark==3.5.9`

3. Keep the notebook and Housing.csv in the same working directory.
4. Open the notebook in Jupyter.
5. Run the cells sequentially.

## Author

Rishabh Kumar
