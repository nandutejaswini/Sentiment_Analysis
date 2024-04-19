# Sentiment Analysis Using LSTM

This project demonstrates the application of a Long Short-Term Memory (LSTM) neural network to perform sentiment analysis on movie reviews. It uses Keras and TensorFlow to create and train an LSTM model to classify reviews as positive, negative, or neutral based on their content.

## Features

- **Data Preprocessing**: Converts raw text into a format suitable for the LSTM model.
- **Model Training**: Trains an LSTM model on preprocessed text data.
- **Sentiment Prediction**: Uses the trained model to predict the sentiment of new movie reviews.
- **Model Evaluation**: Assesses the accuracy and effectiveness of the model on a test dataset.

## Installation

Clone this repository to your local machine using the following command:
git clone https://github.com/nandutejaswini/Sentiment-analysis.git

## Usage
Run the Jupyter notebook to see the step-by-step process of data preprocessing, model building, training, and evaluation:

jupyter notebook Sentiment_Analysis_using_LSTM_Model.ipynb

## Model Architecture
The LSTM model used in this project includes:

An embedding layer that converts text inputs into dense vectors.
An LSTM layer with dropout to prevent overfitting.
A dense output layer with a sigmoid activation function to classify the input as positive or negative.
## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes. For major changes or new features, please open an issue first to discuss what you would like to add or change.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
