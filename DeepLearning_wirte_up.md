# NLP and Unsupervised Learning Project
## What people say about things related to Dr. Malone?

### Abstract
This project is to find what people are talking about Dr. Robert Malone on twitter recently.
Who is Dr. [Robert Malone](https://en.wikipedia.org/wiki/Robert_W._Malone)? He is a virologist and immunologist. I never heard about him until his recent remarks about warning parents to be prudent if to give their children Covid_19 shots. And later one of his interviews went virus, which caused his ban from Twitter. I would like to know that when people mention Robert Malone, what  their main topics are? Are they holding a positive or a negative attitude?

### Design
The project will use natural language processing and Unsupervised learning techiniques to do analysis on people't tweets which are pulled by using Tweepy API. User's self description give us a hint what that person values most, their personality, hobby, thought etc. Topic modeling are performed on those two group of text dataset. Also we use Vader to do sentiment analysis for people's attitude when they talk about something.

### Data

The dataset is obtained from Twitter by using Tweepy API, including 20k+ tweets, self descriptions, followers, following, retweets and etc. Due to limited access to twitter for my developer account, I am not able to pull data morn than 7 days earlier. So the analysis is only focus on the recent week people's subjects and topics related to Dr. Malone. The latest tweets was create at 2022-01-14 17:47:15+00:00 and earliest was at 2022-01-07 17:53:24+00:00. For this project, we put out attention on Tweets and self description text.


### Algorithms
- **Preprocessing**  :spaCy and Regular Expression
- **Vectorization /Dimention_reduction** :spaCy,TfidfVectorizer,CounterVectorizer
- **Topic modeling** :LSA,NMF,LDA (only NMF is presented)
- **Clustering**  :KM Clustering

### tools
- Numpy and Pandas: data manipulation.
- Matplotlib /Seaborn : plotting.
- Regular Expression: Text Preprocessing
- spaCy: word tokenize and Parsing
- TSNE : high dimentional data visualization

- Scikit-learn: NMF, KM
- vaderSentiment: Sentiment analysis

### Result
By using aforementioned tools and algorithms, we found out that in general people hold a neutral attitude when they talked about things related to Dr. Malone. Also with top modeling, we divide users into 12 groups according to their self description ; split tweets into 15 topics related to Dr.Malone. 


### Communications
A PPT presentation will be presented.
