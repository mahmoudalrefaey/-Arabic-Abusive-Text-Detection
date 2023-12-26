'Arabic Abusive Text Detection'

Overview:
This GitHub repository contains a Python implementation for detecting abusive text in Arabic language content.
The project utilizes natural language processing (NLP) techniques and machine learning models to classify text into different sentiment categories, focusing on identifying offensive language.

Dependencies:
Make sure to install the required Python packages by running the following commands:
bash
Copy code
pip install arabert tashaphyne numpy nltk scikit-learn pandas

Usage:
Download the dataset: Ensure you have the 'ar_dataset.csv' file containing the Arabic text dataset.
Run the provided Jupyter Notebook: Open the 'ar_abusive_text_detection.ipynb' notebook and execute the cells to load the dataset, preprocess the text, and train the machine learning model.
Evaluate the Model: The notebook includes steps to train the model, perform predictions on a test set, and evaluate the accuracy and classification report.
Data Preprocessing
The preprocessing steps involve cleaning and normalizing the Arabic text, removing stop words, stemming, handling hashtags, and dealing with emojis.
The processed data is then split into training and testing sets.

Machine Learning Model:
The project uses a Multinomial Naive Bayes classifier trained on a Bag of Words representation of the text.
The model achieves an accuracy of 77% on the provided dataset.

Feel free to contribute, improve the model, or adapt it for your specific use case. Let's work together to create a safer online environment for Arabic language content.

#NLP #ArabicTextAnalysis #AbuseDetection #MachineLearning
