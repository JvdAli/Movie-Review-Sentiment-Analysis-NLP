# Movie-Review-Sentiment-Analysis-NLP
Sentiment Analysis of movie reviews -IMDb dataset- 50K reviews(Positive &amp; Negative)

<!-- HEADER -->
<p align="center">
  <img src="Images/header_image.png"/>
</p>

<!-- PROJECT DESCRIPTION -->
## <br>**Project description**
Movie reviews sentiment analysis is a project which is based on natural language processing, where we use NLP techniques to extract useful words of each review and based on these words we can use binary classification to predict the movie sentiment if it is positive or negative.

<!-- PREREQUISTIES -->
## <br>**Pre-requisites**
This is list of required packages and modules for the project to be installed :
* <a href="https://www.python.org/downloads/" target="_blank">Python 3.x</a>
* Pandas 
* Numpy
* re
* Scikit-learn
* NLTK

Install all required packages :
 ```sh
  pip install -r requirements.txt
  ```
<!-- THE DATASET -->
## <br>**The Dataset**
The IMDb dataset refers to a collection of data with 50,000 records compiled and provided by IMDb (Internet Movie Database).
Review columns shows reviews of the viewers and a target column represent their "sentiment" about the movie, either it is positive or negative<br>

<br>**Dataset head :**<br>
![](Images/dataset_head.png)

<!-- CODING SECTIONS -->
## <br>**Coding Sections**
In this part we will see the project code divided to sections as follows:
<br>
- Section 1 | Data Preprocessing :<br>
In this section we aim to do some operations on the dataset before training the model on it,
<br>processes like :
  - Loading the dataset
  - Encoding Target columns(sentiment) to binary (Positive : 1 , Negative : 0) 
  - Data cleaning : Remove HTML tags
  - Data cleaning : Remove punctuation
  - Data cleaning : Remove special characters
  - Data cleaning : Convert everything to lowercase
  - Data cleaning : Remove stopwords
  - Data cleaning : Stemming<br><br>

- Section 2 | Model Creation :<br>
The dataset is ready for training, so we create a Naive Bayes model using scikit-learn and then fit it to the data.<br>

- Section 3 | Model Accuracy Check :<br>
Finally we evaluate the model by getting accuracy score .

<!-- INSTALLATION -->
## <br>**Installation**
1. Clone the repo
   ```sh
   git clone https:https://github.com/JvdAli/Movie-Review-Sentiment-Analysis-NLP.git
   ```
2. Run the code from cmd
   ```sh
   python movie_reviews_sentiment_analysis.py
   ```

<!-- REFERENCES -->
## <br>**References**
These links may help you to better understanding of the project idea and techniques used :
1. Natural Language Processing (NLP) : https://ibm.co/38bN03T
2. Sentiment analysis : https://bit.ly/3yi9BGq
3. Naive Bayes classifier : https://bit.ly/3zhoWIO
4. Model evaluation : https://bit.ly/3B12VOO

<!-- CONTACT -->
## <br>**Contact**
- E-mail   : [jvdali.e@gmail.com](mailto:jvdali.e@gmail.com)



