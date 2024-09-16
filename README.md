# SPAM-MAIL-PREDICTION

Table of Contents:
Project Overview
Model Training
How It Works
Results
Contributors
License

Project Overview for Spam Mail Detection:
This project focuses on detecting whether a given email is spam or non-spam using a machine learning model. The model was trained on a dataset containing emails labeled as spam or non-spam (ham) and leverages natural language processing (NLP) techniques to classify emails based on their content.

Model Training:
Algorithm: Logistic Regression
Logistic Regression is a simple yet effective linear classifier commonly used for binary classification tasks such as spam detection.
Dataset: The model is trained using a dataset that contains spam and non-spam (ham) emails, each labeled appropriately.
Text Preprocessing: The following techniques were applied:
Tokenization: Breaking the email text into words.
Stopword Removal: Removing common words (e.g., "the", "and") that do not contribute to classification.
TF-IDF: Term frequency-inverse document frequency for transforming the text into numerical features.

How It Works:
Input: The email text is inputted into the system.
Preprocessing: The text is tokenized, and stopwords are removed. TF-IDF is applied to transform the text into numerical features.
Prediction: The processed text is passed into the Logistic Regression model, which predicts whether the email is spam or non-spam.
Output: The result is displayed as either Spam or Non-spam.

Results: 
Accuracy on Training Data: 96.70%
Accuracy on Test Data: 96.59%
The model performs exceptionally well, achieving over 96% accuracy on both the training and test datasets. This high accuracy indicates that the Logistic Regression model generalizes well and is highly effective in distinguishing between spam and non-spam emails.

Contributors:
Contributions are welcome! Feel free to fork this repository, submit pull requests, or report issues if you encounter any problems or have suggestions for improvements.

Licence:
This project is licensed under the MIT License - see the LICENSE file for details.

