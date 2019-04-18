# Twitter-Sentiment-Analysis
Performing sentiment analysis on airline review data set using Maxent Classifier,SVM and KNN.

General Steps-
1. Load Dataset
2. Pre-processing
3. Feature set generation
4. Training
5. Testing
6. Result evaluation

# A). K-NN(K-Nearest Neighbour) Classifier
The K-nearest neighbors (KNN) algorithm is a type of supervised machine learning algorithms. KNN is extremely easy to implement in its
most basic form, and yet performs quite complex classification tasks. It is a lazy learning algorithm since it doesn't have a specialized
training phase. Rather, it uses all of the data for training while classifying a new data point or instance.

In my program, first dataset is cleaned by removing number, punctuation and stopwords. It is then converted into lower case.
Cleaned tweets is then split into train and tset dataset. Then, Converts a collection of text documents to a matrix of token counts.
After that training data is used for training the classifier then with testing data we can do prediction and calculate accuracy of the classifier.


# B). Maxent Classifier
Dataset is first cleaned by removing special characters, converted to lower case and then stop words are removed.
Cleaned Tweets are then converted into dictonary format with tweets as value and number of unique words in the tweet as key.
Class label is then added with the dictonary to get final data set which is then split into training and testing data.
training data is sent for training and testing data is used for predicting label and calculating accuracy of the classifier.
