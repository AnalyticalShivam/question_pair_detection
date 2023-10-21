# Duplicate Question Pair Detection using Random Forest Model

This project is aimed at building a simple duplicate question pair detection system using the Random Forest model. The goal is to identify whether two given questions are duplicates or not. This README file provides a brief overview of the project, including its purpose, functionalities, and basic instructions for getting started.

## Table Of The Content
- [Purpose](#purpose)
- [Image](#image)
- [Functionality](#functionality)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [LiveURL](#liveURL)

## Purpose

The purpose of this project is to implement a machine learning-based approach to detect whether two questions are duplicate or not. Duplicate question pair detection can be a valuable tool in various natural language processing applications, including question-answering systems, information retrieval, and online discussion forums.

## Image

![image](https://github.com/AnalyticalShivam/question_pair_detection/assets/93965065/b8a1270f-a437-4805-9b8b-5d558feaa3e1)

![image](https://github.com/AnalyticalShivam/question_pair_detection/assets/93965065/71e55154-5a99-408f-82eb-c197397f5e1b)

## Functionality

The project primarily consists of the following functionalities:

1. Data Preprocessing: Cleaning, transforming, and preparing the question pairs dataset for training the Random Forest model.
2. Feature Engineering: Extracting relevant features from the text data to facilitate the training process.
3. Model Training: Utilizing the Random Forest algorithm to train a model on the preprocessed data.
4. Prediction: Using the trained model to predict whether a given pair of questions are duplicates or not.
5. Evaluation: Assessing the performance of the model using appropriate evaluation metrics.
6. Accuracy: Accuracy score of the model is 78%
7. About Model: Model only able to classify english words or senteces and also not regional language in which it's words or sentences is translated in english.
 
## Installation

To run the project, follow these steps:

1. Clone the repository: `git clone https://github.com/AnalyticalShivam/question_pair_detection`
2. Install the required dependencies: `pip install -r requirements.txt`

## Usage

After installing the dependencies, you can perform the following steps:

1. Run the data preprocessing script to prepare the dataset.
2. Execute the feature engineering script to extract relevant features from the data.
3. Train the Random Forest model using the prepared data.
4. Use the trained model to predict whether a given pair of questions are duplicates.

## Dependencies

The project requires the following main dependencies:

- Python
- Pandas
- Scikit-learn
- NumPy
- bs4
- fuzzuwuzzy

Make sure to install these dependencies before running the project.

## LiveURL
https://questionpairdetection-ihrehncdakxxiqcig8psvd.streamlit.app/
