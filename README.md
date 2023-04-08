# NLP (Natural Language Processing)
This repository contains assignments of **natural language processing** university course [2022/2023]

### Team:
- [Renato Esposito](https://github.com/RenatoEsposito1999)
- [Vincenzo Mele](https://github.com/VincenzoMele)
- Luca Rubino (me)
<br></br>
## First Assignment: Statistics and Some Preprocessing Steps
The first step was to calculate some statistics of the input corpus.
in NLP it is essential to clean up the data (therefore the text) from useless information (which varies according to the application). For this reason, the preprocessing steps were carried out, such as: <i>Tokenization, Lemmatization and Stemming.</i>
<br></br>
## Second Assignment: Sentiment Analysis
A very important task of NLP is sentiment analysis: it is a task whose objective is to verify whether the given input text is  **positive** or  **negative**. To do this we used two models provided by the  `NLTK library`: **Naive Bayes** and **Logistic Regression**. These models received input data preprocessed differently depending on the model. after which tests and evaluations ( with <i>Confusion Matrix</i> ) were made to verify the accuracy of the predictions.
<br></br>
## Third Assignment: N-gram Language Model
In this assignment we want to create a word suggester (like google search does when you're typing words into the search bar). To do this, an <b>N-gram Language Model</b> is created, i.e. a <i>probability matrix</i> that is used to make predictions. Also in this case the model is tested and evaluated with the <i>perplexity measure</i>.
