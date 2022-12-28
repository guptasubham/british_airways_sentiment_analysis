# british_airways_sentiment_analysis
Sentiment analysis on the reviews of the customers of the British Airways 

This project has the following processes that a typical machine learning project should have:

1.Data mining: the data for this project was scrapped from the skytrax.com a site where all airline reviews can be found.

2.Data cleaning: the data scrapped needed a lot of cleaning due to scrapping it consists of many unwanted strings attached to the review text.

3.Data preprocessing: for the data to be meaningful for exploratory data analysis and model training it has to be pre-processed. The following are the steps done in order to pre-process the data

    -Text generalization: removing puntuations and numbers from the text. 

    -Tokenization: making word tokens from the review texts.

    -Stemming and Lemmatization: finding the root word for any word that has been used in the review text(eg. see/saw/seen was stemmed to its root word "see").

    -TF/IDF: machine learning models needs data to be in vector format for training, tf/idf created the vector formant for the review texts.

    -Train/Test split: splitting data for training and testing.


4.Exploratory Data analysis: making a word cloud for getting the most frequent discussed topic or service of the airline.

5.Topic modelling: topic modelling includes classifying the reviews to a particular topic which it discusses. It could be useful in finding generalized topics from the whole corpus.

6.Sentiment analysis: model training and testing.
