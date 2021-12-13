# MeToo-Troll-Detection

* Social media has become a very effective tool for information exchange. They allow users to not only consume information but also share and discuss a variety of topics of interest. Social media, on the other hand, has its drawbacks, such as trolling and online threats. Twitter is one such social networking site where people communicate in short messages called tweets. 
* An internet troll, or online bully, deliberately tries to offend, cause trouble or directly attack people by posting derogatory comments on social media platforms.
* Recently, a large portion of tweets was tagged as #MeToo was one of the most popular trending topics on Twitter.
* In this study, we utilized a dataset of 30000 me-too tweets and categorized them into hateful and non-hateful tweets. We gathered the information for sentiments classification using various models such as Naive Bayes, Logistic Regression, and LSTM.

## Dataset
### MeToo Dataset
https://www.kaggle.com/rahulgoel1106/hatred-on-twitter-during-metoo-movement

## Word Cloud Representation
<html>
<img src = "https://i.ibb.co/Bznh5md/word-cloud.png" width = 500 height = 500>
</html>

## Architectural Diagram of Classification Process
<html>
<img src = "https://i.ibb.co/2cKjG3j/flowchart-metoo.png" width = 500 height = 500>
</html>

## Results
Python is utilized in this research to determine how well the algorithm performs on reviews depending on the evaluation metric. The initial step is learning, and the subsequent phase is prediction. The learning step involves training the model on the dataset and then classifying the training dataset into hateful and non-hateful tweets. The outcomes are recorded, and performance varies according to the learning period. To avoid underfitting, we need to utilize a sufficiently large dataset, i.e., the learning phase should be sufficiently thorough. The model learns to classify using the training data and is then tested using the test set during the testing phase.
### Confusion Matrix achieved using LSTM
<html>
<img src = "https://i.ibb.co/d2vxxBt/Confusion-matrix.png" width = 650 height = 400>
</html>

## Comparative analysis using the Evaluation Metrics for different Classification techniques
<html>
<img src = "https://i.ibb.co/SJkbR1c/Evaluation-Metrics.png" width = 700 height = 250>
</html>
The accuracy, precision, recall, and F1 score are the evaluation metrics used to evaluate and compare the classification of hateful and non-hateful tweets. The accuracy for Naive Bayes is 93.27%, Logistic Regression is 95.35% and LSTM is 97.90%.

## Performance of Different classifiers in MeToo Twitter Sentiment Analysis using Bar Graph
<html>
<img src = "https://i.ibb.co/jy9x9fW/image.png" width = 700 height = 500>
</html>
