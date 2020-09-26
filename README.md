# Fraud-Detection-using-BigQuery-and-AI-Notebooks
Implemented a Fraud Detection model on Google AI Platform and used data from Big Query


## Data :
A Preprocessed Big Query Dataset for Fraud Detection
- Time is the number of seconds between the first transaction in the dataset and the time of the selected transaction.
- V1-V28 are columns that have been transformed via a dimensionality reduction technique called PCA that has anonymized the data.
- Amount is the transaction amount.


## Big Query 
Made a Dataset in Big Query and split the data into 3 parts
- Training: used to build the model by iteratively adjusting parameters
- Validation: used to assess if the model is overfitting by verifying on independent data during the training process
- Test: used after the model has been created to assess accuracy


## Notebooks
- Used Tensorflow AI notebook instace to connect to the bigquery client and get the data 
- Build a 3 layer kearas deep learning model 

## Results

[1.8711000787477399, 0.998804, 0.3272799]
