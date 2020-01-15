# ECSM_Charlottesville
Emoji Analysis on Charlottesville Solidarity tweets

**Charlottesville dataset made available**
```
Due to Twitter's restrictions, we are only able to share the tweet ID's and User/Actor ID's. 

We have annotated the tweets into following Categories:
* -1 - Non Solidarity, 
* 0 - Cannot be determined, 
* 1 - Solidarity

These annotations are also made available along with tweet and User/Actor Id's.

The Datasets are available in the dataset folder

1. **Unite the Right rally - Charlottesville** - Id's(Tweet Id), Profile Id's(user_id) and Annotations from tweets of "Unite the Right rally", Charlottesville from Feb 2017 to October 2017.
```

This repository contains a mixture of codebase written in R (predominantly) and Python.

We have used Solidarity tweets (Annotation == 1) for our Analysis.

Please download the tweets with the help of the tweet IDs using this [repository](https://github.com/VidhushiniSrinivasan16/tweets_extraction) in Python or use the rtweet library for R.
**Scripts**

Charlottesville_FaceObjectGestureEmoji_Analysis.Rmd - Charlottesville Tweets Analysis Code containing Emoji analysis along with Information Theoretic Measures like lexical diversity, perplexity etc.

all_emoji_in_corpus.csv - Emoji's in our corpus and their corresponding annotated Categories.

Make_Dataset.ipynb - Code to extract tweet ID's, Actor ID's and Annotations from our dataset

Please contact vsriniv6@uncc.edu if you have any further questions with regards to this project. 
