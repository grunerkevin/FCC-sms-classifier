# Neural Network SMS Text Classifier

This project is part of the Machine Learning with Python curriculum of freeCodeCamp. It aims to create a neural network model that classifies SMS messages as either "ham" or "spam". A "ham" message is a normal message sent by a friend. A "spam" message is an advertisement or a message sent by a company.
## Dataset
The dataset used for this project is the UCI SMS Spam Collection Dataset, which contains 5572 SMS messages labeled as either "ham" or "spam".
## Requirements
This project requires the following Python libraries:
- pandas
- numpy
- tensorflow
	- keras
- matplotlib
This project also requires Google Colaboratory, a cloud-based platform that allows you to run Python code in a browser.
## Installation
To install this project, follow these steps:
- Clone this repository to your local machine or your Google Drive.
- Open the notebook file `neural_network_sms_text_classifier.ipynb` in Google Colaboratory.
- Run the code cells in the notebook to import and preprocess the data, create the model, and test the function.
## Usage
To use this project, you can call the function `predict_message` with a SMS message as an argument. The function will return the predicted label ("ham" or "spam") and the probability of the prediction. For example:

```python
predict_message("how are you doing today?")

Output:

[0.0, 'ham']