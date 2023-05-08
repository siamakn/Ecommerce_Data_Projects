# E-Commerce Category Classifier

This project aims to build a Machine Learning model that can predict the category of an item using only its title. The dataset (not provided) contains item titles from six different categories: Books, Grocery, Music, Toys, Office, and Watches.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Results](#results)
- [Usage](#usage)

## Introduction

The purpose of this project is to create a model that can accurately classify e-commerce items into their respective categories using just the item's title. This is particularly useful when category information is missing or incomplete.

## Dataset

The dataset consists of a CSV file containing item titles from six different categories: Books, Grocery, Music, Toys, Office, and Watches. The majority of entries are in English, but some titles may be in other languages.

## Methodology

1. **Data Preparation**: Loaded the dataset and preprocessed the data, including the optional removal of non-English entries using third-party libraries.
2. **Model Selection**: Tested three different classification models and represented their performance visually through confusion matrices and classification reports. Chose the best model based on performance and used grid search to find the optimal hyperparameters.
3. **Pipeline Construction**: Built a pipeline that includes at least a text vectorizer (e.g., TfidfVectorizer) and the chosen classification model, allowing for predictions to be made by directly inputting a text label.
4. **Prediction and Analysis**: Added a prediction label to the original dataframe and plotted the results, divided by category and number of correct predictions. Updated the "predictions" dictionary with the corresponding prediction from the final model using the pipeline.
5. **Model Export**: Included a .joblib file named "category_classifier" with the model ready for use.


## Usage

This project demonstrates a general approach to solving e-commerce category classification problems using data preprocessing, model selection, and evaluation techniques. To understand and adapt the methodology for similar problems, follow these steps:

1. Review the Jupyter Notebook: Examine the data preprocessing steps, model selection process, and performance evaluation.
2. Apply the methodology: Use the techniques and concepts demonstrated in this project to tackle similar classification problems in e-commerce or other domains, modifying the code as needed.
3. Learn from the implementation: Study the pipeline construction, hyperparameter tuning, and visualization of model performance using confusion matrices and classification reports.

Please note that this project is primarily intended as a reference and may not be directly applicable to other datasets without modification.


