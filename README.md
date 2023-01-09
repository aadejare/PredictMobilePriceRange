# PredictMobilePriceRange

Predicts a price range for mobile phone creation that will eventually go into the market.
## Motivation

Two motivations went into the project:

1. Can we predict price range for mobile phone creation, even when under regresison.
2. Can deep learning produce a competitive result compared to regular machine learning for regression

## Run the project

This project runs on Python 3.7.12  once you confirm the settings you can start on this project.

Clone the project

```bash
  git clone https://github.com/aadejare/PredictMobilePriceRange
```

Go to the project directory

```bash
  cd PredictMobilePriceRange
```

Install dependencies

```bash
numpy = 1.21.6
pandas = 1.3.5
sklearn = 1.0.2
xgboost = 1.6.1
keras = 2.3.1
```

Grab data from the data source and run from Jupyter Notebook You can grab a method of running a Jupyter Notebook from Anaconda https://www.anaconda.com/


## Files


The files in the Repo are the following:
```
LISENSE: The MIT Lisense for the project
README.md: The Read me file for the project
new_esrb_rating.ipynb: The notebook to run the file
train.csv: Traninig dataset containing configuration of smartphones and their price range
test.csv: New dataset to evaluate model

## Data source

The Data source comes from Kaggle [Mobile Price Classification](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)

Download the files and replace the file paths with where the files are located on your machine.

The data sources are the following
```
train.csv
test.csv  
```
## Deployment

To deploy this project you need the following package

```bash
numpy = 1.21.6
pandas = 1.3.5
sklearn = 1.0.2
xgboost = 1.6.1
```


## Results

Here were the Results
KBQ1: XGBoost had the highest accuracy and F1 score for teen prediction
KBQ2: Using Kmeans clustering, Teens label had the least clarity on cluster location and subsequently had variables that were hard to decern for a perfect laebl.
KBQ3: Action titles seemed to be the candidates for a new label with violence, language, and use of alcohol being some of the most frequent categories that provided contenxt as to whether to produce a new label or not.

There's more but you should play around with it and discover more through the notebook.
## Acknowledgements

 - [Udacity](www.udacity.com)
 - [Kaggle](www.kaggle.com)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Authors

- [@aadejare](https://www.github.com/aadejare)

## Reference 

- [Let’s Invent a New ESRB Category](https://projectpioneer.wordpress.com/2022/09/14/lets-invent-a-new-esrb-category/) [Article]
