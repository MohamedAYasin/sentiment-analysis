# sentiment-analysis

<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Enraged%20Face.png" alt="Enraged Face" width="10%" height="10%" /><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Angry%20Face.png" alt="Angry Face" width="10%" height="10%" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Neutral%20Face.png" alt="Neutral Face" width="10%" height="10%" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Grinning%20Face%20with%20Smiling%20Eyes.png" alt="Grinning Face with Smiling Eyes" width="10%" height="10%" />
<img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Beaming%20Face%20with%20Smiling%20Eyes.png" alt="Beaming Face with Smiling Eyes" width="10%" height="10%" />
</div>

---

## 1- Introduction

Sentiment analysis is the process of collecting and analyzing information, thoughts, and opinions regarding different topics whether it is politics, entertainment, subjects and services. Collecting these opinions can be beneficial to governments, organizations and individuals who want to make decisions based on others’ opinions. Sentiment analysis has gained popularity in the past recent years, not just among researchers and tech people but also among organizations, businesses and governments [1].

In this assignment, we developed a text classification system to do sentiment analysis on Twitter’s or X’s tweets. We sourced the dataset from the famous site Kaggle, and it contains collected tweets labeled as sentiments - Positive, Negative and Neutral. The goal of using sentiment analysis on this dataset was to build two models that can predict the sentiment of the tweets.

We were instructed to build and compare two models, a traditional machine learning model (Logistic Regression, Support Vector Machine (SVM) and Naive Bayes) and deep learning model (RNN, LSTM, GRU).For the traditional model, we trained Logistic Regression and SVM, On the other hand, we implemented a Long Short-Term Memory (LSTM) with Word2Vec Embeddings. We also evaluated the performance of both models and compared the differences.

--- 

## 2- Preprocessing Steps

The process started with loading the dataset from Kaggle, and then we performed numerous preprocessing steps to standardize and clean the data like removing special characters and numbers. After that, we tokenized the data by splitting the tweets into words. Then, we did the lemmatization and stemming process to convert the tweet words to their base form. We also visualized the data key findings in different visualizations.

--- 

## 3- Visualizations:

- ![Image](https://github.com/user-attachments/assets/9e978cb7-5933-462b-ad5f-5c2d5e4c322a)

- ![Image](https://github.com/user-attachments/assets/459d67fb-13a8-4a6f-978c-bbde2dc0ed1a)

- ![Image](https://github.com/user-attachments/assets/42ed0a44-4b01-40c0-a718-cd484f0d624e)

---

## 4- The Traditional Machine Learning Model

In this Traditional machine learning model, we explored and trained two simple models, Logistic Regression and SVM. Logistic Regression is one of the most used techniques in data mining, particularly binary data classification. One of the benefits and the reasons we used Logistic Regression is that it can assist with problems related to multi-class classification. Logistic Regression methods also follow the same principles used in Linear Regression [2].  Support Vector Machine known as SVM is also the other powerful model that we used to separate sentiment classes and improve the performance of the model.

As mentioned in the notebook, both of the models were trained on TF-IDF embedding, and their performance were evaluated using several metrics such as the accuracy, f1-score, precision and recall.

Compared to the two models, the SVM has better performance due to its high accuracy, F1-Score and Precision. The SVM is effectively balancing precision-recall trade-offs while also making more accurate predictions.

---

## 5- The Deep Learning Model

In this Deep Learning Model, we implemented an LSTM network with Word2Vec embeddings. The LSTM is best known for sorting sequential data, as it allowed the model to capture the relationships between tweets. We used LSTM layers, Dropout regularizations and Softmax layer to prevent overfitting and improve the model performance.

---

## 6. Findings and Evaluation
After we trained the models, we compared  their performances and realized that:

Both Logistic Regression and SVM performed well on the TF-IDF.
LSTM with Word2Vec embeddings also provided better contextual understanding for enhancing sentiment classification for ambiguous tweets.

---

## 7. Conclusion

In this assignment project, we explored sentiment analysis on tweets using both traditional Machine Learning and Deep Learning models. In the traditional one, we trained two models, Logistic Regression and SVM, while we explored LSTM with Word2Vec on the Deep Learning model. The insights of both models showed that the models' performances improved over time. For the future, we aim to experiment with more advanced techniques like pre-trained transformers like BERT to improve the quality and performance.

---

8- References:

[1] J. F. Sánchez-Rada and C. A. Iglesias, “Social context in sentiment analysis: Formal definition, overview of current trends and framework for comparison,” Information Fusion, vol. 52, pp. 344–356, Dec. 2019, doi: https://doi.org/10.1016/j.inffus.2019.05.003.
‌[2] M. Maalouf, “Logistic regression in data analysis: An overview,” ResearchGate, Jul. 2011. https://www.researchgate.net/publication/227441142_Logistic_regression_in_data_analysis_An_overview‌

---

## Links:
Github Repository: https://github.com/MohamedAYasin/sentiment-analysis.git

---

# Team Contribution:
1- Data Load and Preprocessing: Mohamed Yasin and Esther Mbanzabigwi
2- Traditional Model: Esther Mbanzabigwi
3- Deep Learning Model: Mohamed Yasin and Guled Hassan




