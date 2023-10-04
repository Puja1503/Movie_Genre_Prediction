# Movie Genre Prediction Project

Overview

This project focuses on predicting whether a movie belongs to the drama genre or not based on its description. The goal is to develop a machine learning model that can classify movie descriptions accurately.

Files

movie_genre_prediction.ipynb: This Jupyter notebook contains all the steps for data preprocessing, training, testing, and prediction. It provides a detailed walkthrough of the project, including data exploration, feature engineering, model selection, and evaluation.

model.pkl: This is a serialized machine learning model that has been trained on the dataset. It can be used for making predictions on new data without retraining the model.

vectorizer.pkl: This file contains the text vectorizer or tokenizer used to convert movie descriptions into numerical features. It is necessary for preprocessing new data for prediction.

encoder.pkl: This file stores the label encoder used to encode the target variable (movie genre) into numerical values. It is needed for decoding predictions.

Usage

1. Clone the Repository: Clone this Git repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/movie-genre-prediction.git
   ```

2. Install Dependencies: Ensure you have the required libraries and packages installed. You can install them using the following command:

   ```
   pip install -r requirements.txt
   ```

3. Run the Notebook: Open the `movie_genre_prediction.ipynb` Jupyter notebook to explore the project, run the code cells, and understand the model development process.

4. Make Predictions: To make predictions on new movie descriptions, you can use the provided serialized model (`model.pkl`) and the vectorizer (`vectorizer.pkl`). Load the model and vectorizer in your own Python script or Jupyter notebook and use them to preprocess and predict genres for new descriptions.

## Data

The dataset used in this project is not included in this repository due to size limitations. 
You can obtain the dataset from [source link or location] and place it in the `data/` directory. Ensure that the dataset file is named `movie_data.csv`.




Thank you for exploring the Movie Genre Prediction Project!
