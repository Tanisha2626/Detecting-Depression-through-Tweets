<h1> Instructions </h1>
<ul>
<li>All resources related to project will be shared here. <br>
<li>Every weekly resource will also contain a weekly task which is expected to be completed before the next week resources are updated.<br>
<li>I would highly appreciate if you keep following these weekly tasks on time since it would avoid a lot of last minute work for you guys<br>
<li>But at the same time if any of you is not able to cover it up in given time due to whatever reason then let me know about it and try covering it up later<br>
<li>I dont want to make any of it compulsory because i want it to be a learning experience for you all and not some madatory assignment with a hard deadline 
So learn at your pace and make the best out of this opportunity<br>
</ul>

<h1><b>Week 1</b></h1>
<h2>Study Resources</h2>
<h3> For this week you will be brushing up your <b>Exploratory Data Analysis</b> basics,and also some basic introduction to <b>Text Pre-Processing</b></h3>
<ol>
  <h2><li>Exploratory Data Analysis - </h2>
   Video number 6 - 12 of <a href='https://www.youtube.com/watch?v=GA0u6WM7_Eo&list=PLZoTAELRMXVNUL99R4bDlVYsncUNvwUBB&index=4'>playlist</a> is suffiecient for the EDA part however if any of you does not feel confident enough in python then feel free to watch video number 4 and 5 as well. 
  <h2><li> Text Pre Processing -</h2>
  Articles <a href='https://builtin.com/data-science/introduction-nlp'>1</a> and <a href='https://builtin.com/data-science/introduction-nlp'>2</a> should suffice for the introduction however you can also refer to the <a href='https://www.marktechpost.com/2022/11/30/top-natural-language-processing-nlp-tools-platforms/'>bonus article</a> <br>
  For the implementation purpose refer to top 10 videos of <a href='https://www.youtube.com/playlist?list=PLZoTAELRMXVMdJ5sqbCK2LiM0HhQVWNzm'>this playlist</a>
  </ol>
 <h2>Assignment for Week 1</h2>
  <h3>Its time to implement what you have studied through the above mentioned resources. For this week we will not focus on extracting data and will use a <a href='https://www.kaggle.com/datasets/ywang311/twitter-sentiment'>predefined dataset.</a><br>
  This dataset has file Sentiment Analysis Dataset 2.csv having following columns:<br>
  <ul>
    <li>ItemID : Unique ID for tweets
    <li>Sentiment : 1 if tweet is of depression sentiment, 0 if not
    <li>SentimentSource : Source of tweet extraction
    <li>SentimentText : Raw text of tweet
  </ul></h3>
  <ol>
  <h2><li>Task 1 -</h2>
  Go through an introduction on google colab <a href='https://www.youtube.com/playlist?list=PLA83b1JHN4ly56Y7o6vDAT8Szxc3_EdRH'>video or </a><a href ='https://medium.com/swlh/what-is-google-colab-169d5252e51d'>article</a> and implement the following:
  <ul>
    <li>Make an account on Google Colab and Mount your drive.
    <li>Upload csv file in a Google Drive folder.
    <li>Import csv in colab as DataFrame (df) (Check pd.read_csv())
    <li>Preview top 5 rows of df  (Check df.head())
    <li>Check number of Null values in each row (Check df.isnull().sum())
  </ul>
  <h2><li>Task 2 - </h2>
  Go through this <a href='https://www.analyticsvidhya.com/blog/2021/06/text-preprocessing-in-nlp-with-python-codes/'>article </a>about pre processing techniques NLP data and their easy python implementations and then perform the following tasks:
  <ul>
    <li>Drop unnecessary columns (ID, Source)
    <li>Remove punctuations like . , ! $( ) * % @, URLs, Stop words
    <li>Perform lower casing, tokenization, stemming, lemmatization
  </ul>
  <h2><li>Task 3 - </h2>
  Go through this <a href='https://github.com/sharmaroshan/Twitter-Sentiment-Analysis/blob/master/Twitter_Sentiment.ipynb'>article </a>about EDA techniques NLP data and their easy python implementations and then perform the following tasks:
  <ul>
   <li>Make word cloud from the overall dataset
   <li>Make word cloud for individual classes (Positive / Negative)
   <li>Get sentence lengths (word count) for both classes’ data and make plots to check if there is a difference in tweet length of depressing and non-depressing nature
   <li>Get counts of tweets for both classes and make a count plot.
   <li>Check 5 examples of depressing and 5 of non-depressing tweets
   <li>Check the longest tweet in the dataset for both classes. 
     
  </ul>
  <h2>Task 4 - </h2>
  Create a github repository by the name <i><b>Detecting Depression through Tweets</b></i> just like the one I made and store all the three tasks in it in the form of ipython notebooks before the deadline.<br>
  Feel free to refer to <a href='https://www.edureka.co/blog/how-to-use-github/'>this article</a> for an introduction to github and <a href='https://bebi103a.github.io/lessons/02/git_with_colab.html#:~:text=Pushing%20your%20notebook%20to%20the%20repository,-After%20you%20have&text=To%20do%20so%20from%20within,be%20pushed%20to%20your%20repository.'>this article</a> for uploading your colab notebooks to your github repository. 
  <h1> End of Week 1 </h1>
  <h2> Deadline: 23rd of December </h2>


  
    



  
  
   
