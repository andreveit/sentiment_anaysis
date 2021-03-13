   **Author:** Andre Veit

   **LinkedIn:** https://www.linkedin.com/in/andreveit/

   **E-mail:** andrev.veit@gmail.com
   
<br>

   # CONSUMER REVIEWS OF AMAZON PRODUCTS


# Sentiment Analysis


![figure](https://github.com/andreveit/sentiment_anaysis/blob/main/sentiment_analysis.jpg?raw=true)

## About this notebook:

&emsp; According to Badree Shshetty on his blog post published in Towards Data Science, "NLP is a field in machine learning with the ability of a computer to understand, analyze, manipulate, and potentially generate human language." It has been applied in several fields with many different objectives such as language translation, text summarization, spam filter, sentiment analysis and many others.

&emsp; The objective of this notebook is, unsing machine learning algorithms, build a text classifier to identify "Happy" documents, "Angry" documents or just "Neutral" ones. For training, it was chosen Amazon product reviews, that conveniently were already labeled.

&emsp; This study is divided in two parts, the first part (this notebook) consists in building a voting classifier through some classic machine learning algorithms. In the second part, a BERT model will be fine tunned using this same dataset.

<br>

### Overview:


**PART I:**

1) Data Cleaning

3) Data Exploration

4) Data Preprocessing and Preparation
> 4.1) Data Preprocessing<br>
> 4.2) Most Frequent Words<br>
> 4.3) Data Preparation<br>
> >4.3.1) Helper functions<br>
> >4.3.2) Balanced vs Imbalanced Data <br>
> >4.3.3) TfidfVectorizer   vs   CountVectorizer <br>
> >4.3.3) Data Preparation - Final State <br>

5) Classification Models
> 5.1) Base Models<br>
> 5.2) Grid Search and Cross Validation<br>
> >5.2.1) Support Vector Machines <br>
> >5.2.2) Logistic Regression <br>
> >5.2.3) Naive Bayes <br>
> >5.2.4) Random Forest <br>
> >5.2.5) Gradient Boosting <br>
> >5.2.6) Voting Classifier <br>

6) Wrapping up

<br>

**PART II:**

(Under construction)


<br>
<br>


## Data Set

&emsp;The dataset analyzed was provided by Datafiniti on Kaggle website.

&emsp;https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products?select=1429_1.csv

&emsp;Below, Datafiniti's data description:

### About This Data

&emsp;This is a list of over 34,000 consumer reviews for Amazon products like the Kindle, Fire TV Stick, and more provided by Datafiniti's Product Database. The dataset includes basic product information, rating, review text, and more for each product.

&emsp;Note that this is a sample of a large dataset. The full dataset is available through Datafiniti.
