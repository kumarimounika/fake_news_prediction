# fake_news_prediction
dataset is obtain from kaggle.com.

various NLP technique were performed to obtain the maximim accuracy.

in this model the steps involved are:
step1:Imported the Dataset./n
step2:Data Exploration./n
step3:Stemmimg is done using PorterStemmer.
step4:Bag of Words are obtained using CounterVetorizer.
step5:split the data into test and train.
step6: modelling:
note:modelling is done using two model i.e 
     1.CounterVectorizer.
     2.TF-IDF.
     3.Hagging Vectorizer.
     by applying multinominalNB and PassiveAggresiveClassifier logrithms.
step7:Training and hyperparametertuning with CounterVectorizer.
     1.by using multinominalNB - 90% accuracy.
     2.by using PassiveAggresiveClassifier - 92% accuracy.
step8:Training and hyperparametertuning with TF-IDF.
     1.by using multinominalNB - 90% accuracy.
     2.by using PassiveAggresiveClassifier - 91% accuracy.
step9:Training with Hagging vectorizer and got 89% accuracy.
step10:since the CounterVectoriser(PassiveAggresiveClassifier) gives high accuracy i.e 92%. we creating a model using this.
#this model has the ability to predict the fake news with 92% of accuracy.










highest accuracy is obtained using contervectorizer and by applying passiveaggresiveclassifier  i.e 92%
