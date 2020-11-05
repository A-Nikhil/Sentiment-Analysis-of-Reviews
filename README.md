# Sentiment Analysis

## Packages required

Run the following commands in your virtual environment
```
pip install tensorflow nltk sklearn matplotlib spacy keras
```

## How to run the code

Open the notebook `sentiment_main.ipynb` and Run All the cells
To provide your own custom review

* With Naive Bayes
    ```python
    test_sentiments(nb_classifier, [["Your review here""]]
    ```

* With SVM
    ```python
    test_sentiments(svm_classifier, [["Your review here""]]
    ```

* With LSTM
    ```python
    decide_review("Your review here")
    ```