# Language-Classifier
A Language Classification Machine Learning Project

This project is an exploration of using Machine Learning to classify the language of a text. It explores the various models and tunings that can be used to achieve this. 

There are several files in this repository:
- Language Classifier MLB.ipynb uses the Multinomial Naive Bayes model, run once, with a report consisting of a Single score
- Language Classifier MLB LR - MLB LR.ipynb uses the Multinomial Naive Bayes model and applies Logistic Regression, run 99 times and averaged, with a report consisting of the Multinomial Naive Bayes score + LR prediction
- Language Classifier MLB LR - MLB.ipynb uses the Multinomial Naive Bayes model and applies Logistic Regression, run 99 times and averaged, with a report consisting of the Multinomial Naive Bayes score only
- Language Classifier MLB RFC SVC KNN.ipynb uses the Multinomial Naive Bayes model, adding Random Forest Classifier, Support Vector Classifier, and K-Nearest Neighbors, run 19 times and averaged, with a Classification report
- Language Classifier MLB RFC SVC KNN LR + Feature.ipynb uses the Multinomial Naive Bayes model, adding Random Forest Classifier, Support Vector Classifier, K-Nearest Neighbors, Logistic Regression Classifier, run 19 times and averaged, with the feature of SelectPercentile chi2, and a Classification report

The Multinomial Naive Bayes model with feature selection is the most optimal. You can run that file as a jupyter notebook file and input a sentence in one of the supported languages(Arabic, Chinese, Dutch, English, Estonian, French, Hindi, Indonesian, Japanese, Korean, Latin, Pashto, Persian, Portuguese, Romanian, Russian, Spanish, Swedish, Tamil, Thai, Turkish, Urdu) and it will classify the language.