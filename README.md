 ![alt text](1.jpg)

<h1>What is Sentiment-Analysis </h1>
<p>the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.</p>

<hr>

<h2>1. Twitter Sentiment analysis</h2>
<ol>
  <li><a href = 'https://apps.twitter.com/app/new'>Twitter Developer Account</a></li>
  <li><a href = 'http://www.tweepy.org/'>Tweepy Library</a></li>
  <li><a href = 'http://www.nltk.org/'>NLTK Library</a></li>
</ol>
  
<h2>Steps for Twitter Sentiment Analysis</h2>
<br>
<ol>
  <li>Importing Necessary libraries</li>
  <li>setting up the consumer and access api tokens and keys</li>
  <li>Setting up the connection bridge and the search token</li>
  <li>loading the pretrained model</li>
  <li>Data Preprocessing</li>
  <li>Fitting the model</li>
  <li>Plotting The results</li>
</ol>

<h2>2. Using VADER</h2>
<ul>
  <li>Valence Aware Dictionary for Sentiment Reasoning is a model used for text sentiments analysis
    that is sensitive to both polarity (positive/negative) and intensity (strength) of emotion.</li>
 
 <li>It is available in the NLTK package and can be applied directly to unlabeled text data</li>
  
 <li>Primarily VADER sentiment analysis relies on a dictionary which lexical features to emotion
    intensities called sentiment scores</li>
  
 <li>The sentiment score of a text can be obtained by summing up the intensity of each word in the text.</li>
 
 <li>For example, words like "love", "like", "enjoy", "happy" all convey a positive sentiment</li>
 
 <li>VADER is intelligent enough to understand basic context of these words, such as "did not love" as a negative sentiment</li>
 
 <li>It also understands capitalization and punctuation, such as "love!!!"
  
 <li>Sentiment Analysis on raw text is always challenging however, due to a variety of possible factors:</li>
  <ol>
   <li>Positive and Negative sentiment is the same text data.</li>
    <li>Sarcasm using positive words in a negative way.</li>
  </ol>
</ul>
  
  
