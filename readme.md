#Chatbot

In this project, i created a chatbot using the nltk library. The data used for chatbot is saved in the file "data.txt". I take a topic of "Artificial Intelligence" from the wikipedia and pasted it on "data.txt". Also we use tfidfVectorizer and Cosine similiarity is used.

1. At first install all the dependencies and import the essential libraries
2. Then we import the data file
3. Then the text is converted into the a list of sentences called sentence tokenization
4. Then again text is converted into a list of words called word tokenization and convert it into lowercase and removing punctuations.
5. Then we use tfidfVectorizer from sklearn library to convert the text into the matrix of TF-IDF features. It measures the important of the each word in a document and assign a numerical value to form a matrix
6. Then we compare the user response with the TF-idf features and using cosine similiarity we select the response with the higher value of cosine similiarity.
7. Then we terminate the chatbot by using "Bye"

