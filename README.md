# Fake-News-Detection
Technologies used : Python
Libraries used : pandas  , numpy , nltk , sklearn , matplotlib

We train and test the model for classifying the news as real or fake .

We take the text from the news and perform cleaning operations onit like applying stop words , performing stemming operation and store it in corpus

We take the  5k most frequent words in the entire list of documents and convert into bagof words .

We split the input text into training and test data 

Then we apply the bag of words on the Text to classify it as real or fake using a MultinomialNB class .
