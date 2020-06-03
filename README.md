# Natural-Language-Classification
Natural Language Processing for IMDB reviews and 20Newsgroup news with multiple ML models


### Natural Language Processing

#### Preprocessing (nltk)
* Remove all non-words
* Transform the review in lower case
* Remove all stop words
* Perform stemming/lemmating
* Check and correct spelling

**Use Sklearn package with hyper-parameters tuning (Pipeline, GridSearch)**
* RandomForest
* Adaboost
* SVM
* Decision Tree
* Logistic
* KNN
* Naive Bayes

**Data used:**
* [IMDB review](http://ai.stanford.edu/˜amaas/data/sentiment/)
* [20 news group](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html) with removal of *'headers'*, *'footers'*, *'quotes'*
