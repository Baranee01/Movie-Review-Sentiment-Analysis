# Movie Review Sentiment Analysis

### INSTALLATION

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](http://seaborn.pydata.org/)
- [nltk](http://www.nltk.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/index.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.

##
### EXECUTION

In a terminal or command window, navigate to the top-level project directory `Movie-Review-Sentiment-Analysis/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook MOVIES.ipynb
```
or
```bash
ipython notebook MOVIES.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser. You can also use [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) for easy access as it already has all the packages installed.

##
### ABOUT THE DATASET
The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis, originally collected by Pang and Lee. The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

 - "**train.tsv**" contains the phrases and their associated sentiment labels. We have additionally provided a SentenceId so that you can track which phrases belong to a single sentence.
 - "**test.tsv**" contains just phrases. You must assign a sentiment label to each phrase.

###
The sentiment labels are:

Sentiment | Label
----------|-----------------
0         | negative
1         | somewhat negative
2         | neutral
3         | somewhat positive
4         | positive

###
Link : https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data

##
### SAMPLE DATASET

#### 1) TRAINING DATASET:
![image](https://user-images.githubusercontent.com/80042740/118836539-901e7680-b8e1-11eb-8335-cf1c20707ae2.png)

###
#### 2) TEST DATASET:
![image](https://user-images.githubusercontent.com/80042740/118836721-c1974200-b8e1-11eb-9d4a-76851735e13e.png)

##
### FLOW OF THE PROJECT
- Data Preprocessing.
- Exploratory Data Analysis.
- Splitting training and test data.
- Model Building.
- Results and Analysis.
