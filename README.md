<h1>What is Sentiment-Analysis </h1>
<p>the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.</p>

<hr>

<h2>1. Twitter Sentiment analysis</h2>
<ol>
  <li><a href = 'https://apps.twitter.com/app/new'>Twitter Developer Account</a></li>
  <li><a href = 'http://www.tweepy.org/'>Tweepy Library</a></li>
  <li><a href = 'http://www.nltk.org/'>NLTK Library</a></li>
</ol>
  
<h3>Step 1</h3>
<p>setting up the consumer and access keys and token, which we got from the developer twitter account</p>
<code>
#Initializing the API keys<br>
#Consumer Keys<br>
consumer_key = 'ZhP9aDb02I5o3Nz1dVMb7505D'<br>
consumer_secret = 'HahRh4LjYgyjaIIw3rEj9vFP4OKgUSDywuHNGITMt18dUJ56eD'<br>
#Generated API Tokens<br>
access_token = '3221955110-A61i8EDWbHIEqnNzZgoUw9P0tOEGmUBstHjZNVa'<br>
access_secret = 'CVDrSm34cwE3X1cp2bvPq87fZ0gAdv0iRmhYExnclCIjT'<br>
</code><br>

<step 2 >
<p>Setting up the connection bridge and in the args goes the keyword on which we want to search
<code>
#Client Authentication<br>
auth = OAuthHandler(consumer_key, consumer_secret)<br>
auth.set_access_token(access_token, access_secret)<br>
#Setting up our search token<br>
args = ['deeplearning']<br>

#If it doesnot get any tweets then after 10sec it will timeout<br>
api = tweepy.API(auth, timeout = 10)<br>
</code>
