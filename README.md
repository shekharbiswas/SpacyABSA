
# Aspect-Based Sentiment Analysis

Aspect-Based Sentiment Analysis (ABSA) is a natural language processing (NLP) task that involves identifying and analyzing sentiments expressed toward specific aspects or features within a piece of text. 
**SpaCy** is a popular Python library for natural language processing, but it does not have built-in functionality specifically designed for ABSA. 

However, you can use SpaCy in combination with other libraries and techniques to perform aspect-based sentiment analysis.


## Considerations

- Tricky situation of removing stopwords to reduce unwanted extractions of non-aspects but this can also affect spaCy's dependency parsing. 
Same goes with noun chunk merging as well. If someone can think of a better way to remove stopwords and still retain spaCy's dependency goodness it can greatly improve the accuracy

- If it is a ML task per se since we do more of parsing than ML. 
Although Bi-Directional LSTM have been very good at ABSA tasks in the past, unlike semeval tasks we do not have a fixed topic for our aspects to fall into. 
If someone can use the parsing aspect of the code to implement BLSTM in this case, that would be great

- Better alternatives to vaderSentiment if available (unsupervised/ semi-supervised methods might be better here I think)
