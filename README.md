
SMS spam classification is a technique used to automatically identify and classify spam messages in text messages (SMS). The main goal of SMS spam classification is to distinguish between legitimate messages and spam messages so that the latter can be filtered out before reaching the intended recipient.

Here's a brief overview of the SMS spam classification process:

1. Data: Took a large dataset of SMS messages that are labeled as either spam or ham (legitimate messages) from Kaggle.

2. Data Preprocessing: Perform various preprocessing tasks such as text cleaning, labelling, tokenization, stop-word removal, and stemming.

3. Feature Extraction: Extract relevant features from the preprocessed text messages such as bag-of-words, and TF-IDF.

4. Model Training: Train a machine learning model on the extracted features to classify the messages as spam or ham.

5. Model Evaluation: Evaluate the performance of the trained model using various metrics such as accuracy, precision, recall, and F1-score.

6. Model Deployment: Deploy the trained model using flask to classify incoming SMS messages as spam or ham in real-time.

The SMS spam classification process can be implemented using various machine learning algorithms such as Naive Bayes, Support Vector Machines (SVM), and Random Forests. The choice of algorithm depends on the size of the dataset, the complexity of the classification problem, and the available computing resources.

Interface : 

![image](https://user-images.githubusercontent.com/86832339/227755323-35e8240f-6851-49fc-bcfb-84aa1d374d42.png)


![image](https://user-images.githubusercontent.com/86832339/227755304-09b0bce4-1642-4e61-8779-f301b322afcf.png)



