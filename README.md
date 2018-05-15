# Sentiment Analysis on IMDb Movie Reviews

In this respository, we will explore one way of applying machine learning technique to real-life data.
In this example, given 25,000 **labelled** IMDb reviews, we will **classify** each review to be either **positive or negative**.
<br/>
<br/>Code's available [here](https://github.com/ng-kode/Imdb-reviews-sentiment-analysis/blob/master/(Acc%2088%25)Densely-connected-layers.ipynb).

## Overview

- All 25,000 reviews are pre-labelled with either positive or negative
- 25,000 reviews to train our model (i.e. provide the model with **both text and label** for it to learn)
- 25,000 reviews to test our model (i.e. provide the model with **text only**, the model predict if each review is positive or negative)

Our model can attain:
  - Accuracy of 88.6% (total number of correct predictions / 25,000 reviews)
  - Precision of 89.4% (total number of correct predictions / total number of predictions)
  - Recall of 88.0% and 90% (total number of reviews predicted as positive /  total number of positive reviews, and vice versa)

![alt text](https://github.com/ng-kode/Imdb-reviews-sentiment-analysis/blob/master/result_cm "Result Confusion Matrix")

## Installation

Requires 
- python 3
- pip for package installation (normally pre-packed with python) 
- [virtualenv](https://virtualenv.pypa.io/en/stable/installation) (optional tho recommanded, for re-usable environment)

Download the project, cd to project dir, then install packages

```sh
$ git clone https://github.com/ng-kode/Imdb-reviews-sentiment-analysis.git
$ cd Imdb-reviews-sentiment-analysis

# if using virtualenv
$ virtualenv -p python3 ENV
$ source ./ENV/bin/activate

# install packages
$ pip install -r requirements.txt

# after completion, open the notebook by
$ jupyter notebook
```
Default web browser should be automatically launched with address http://localhost:8888/
If not, go to the hosting terminal and find http://localhost:8888/?token=AS-SEEN-FROM-TERMINAL
> Note: The notebook is pre-compiled so that you can see the result without running. Once run, the printed content in notebook **will be removed** and updated. A clone of the notebook is therefore suggested if preservation of a printed content is preferred.
