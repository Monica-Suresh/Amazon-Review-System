
# Amazon-Review-System

## Problem Statement
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The problem in sentiment analysis is classifying the polarity of a given text at the document, sentence, feature/aspect level  whether the expressed opinion in a document, a sentence or an entity feature/aspect is <br>
    <br></t>&nbsp;&nbsp;&nbsp;&nbsp;•	Positive,
    <br></t>&nbsp;&nbsp;&nbsp;&nbsp;•	Negative,
    <br></t>&nbsp;&nbsp;&nbsp;&nbsp;•	Neutral.
      <br><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Further the problem of sentiment analysis extends in looking onto text that gives the opposite meaning of the original polarity and some neural statement that does not gives any informative content about the product to be in the category of positive review or negative review.

## System Design
### Hardware and Software Required:
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Windows / Linux Operating System 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Python 3.x
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Anaconda Distribution (Jupyter Notebook / Spyder)  (Or) Google Collab
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Modern Web Browser
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	WebPy Framework (Flask)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	HTML, CSS, JavaScript 

## System Architecture
Initially the unprocessed and unstructured data is taken which undergoes a series of data processing that includes Tokenization, Feature Extraction, Text Cleaning and Processing, Stemming and Lemmatization followed by NLP techniques. Since the data is categorical converting the data to machine readable vectors is more important and plays a vital role. 
<br>Each sentences of the review text is taken and Word2vec representation of each word is done in order to get the vector format of the data.The vectorized data is further divided into train, test and validation set. The spitted train text undergoes pipelined machine learning and deep learning algorithm to obtain best accuracy.
Libraries Used:
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Numpy and Pandas 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Scikit-learn 
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Mathplotlib and Seaborn
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Tensorflow and Keras.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	 NLTK Package
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	Flask


