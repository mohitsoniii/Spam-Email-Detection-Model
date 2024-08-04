# Spam-Email-Detection-Model

## Overview
This project aims to classify emails as either "spam" or "ham" (not spam) using machine learning techniques. The model uses a dataset of labeled emails and employs text preprocessing and classification algorithms to distinguish between spam and ham emails effectively.

## Dataset
The dataset used in this project consists of email messages labeled as spam or ham. It is a publicly available dataset and includes a mix of promotional and personal emails.

## Project Structure and Steps
1. Importing Necessary Libraries:
The project utilizes libraries like pandas for data manipulation, scikit-learn for model building and evaluation, and TfidfVectorizer for text feature extraction.

2. Loading the Dataset:
The dataset is loaded into a pandas DataFrame. The data consists of email messages labeled as spam or ham.

3. Data Cleaning:
The dataset is cleaned and preprocessed. The labels are encoded using LabelEncoder, and the data is split into training and testing sets using train_test_split.

4. Text Preprocessing:
Text data is transformed into numerical features using TfidfVectorizer to convert the text into a matrix of TF-IDF features, which helps in identifying the importance of words in the emails.

5. Model Training:
A Naive Bayes classifier is trained on the preprocessed text data. The model is fine-tuned using GridSearchCV to find the optimal hyperparameters.

6. Evaluation:
The model's performance is evaluated using metrics such as accuracy, precision, recall, F1 score, and a detailed classification report. The results show how well the model distinguishes between spam and ham emails.

## Results
The model achieved high accuracy and precision in distinguishing between spam and ham emails. The evaluation metrics include:
1.  Accuracy: ~98%
2.  Precision: ~96%
3.  Recall: ~89%
4.  F1 Score: ~93%
A detailed classification report is also provided in the notebook.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions for improvements or new features.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
