# NLP_to_Categorize_News_Articles

This is my final AIT (Artificial Intelligence Techniques) Project which was NLP (Natural Language Processing) classification using the HuffPost dataset in Kaggle. Included are the following files:

1. The final report.
2. The final presentation.
3. The code for the final report.
4. The code for the undersampling evaluation.
5. The code for the Midsemester baseline.

### Abstract

We live in a digital age, in which vast quantities of news and other content can be accessed and consumed online. Accurately categorizing all this content and recommending
it to online users is a difficult challenge. In the past decade, Natural Language Processing (NLP) techniques have become necessary to classify online articles, based on their
content.

This project utilizes the News Category Dataset from HuffPost [1]. It contains new
headlines from approximately 210,000 articles that span a decade from 2012 to 2022.

The project uses NLP algorithms to categorize the headlines into 42 distinct article categories. This midsemester report summarizes the work done up to that point on the project.
Extensive exploratory data analysis reveals insights into the data’s structure. There is
a notable class imbalance in this dataset that will be further investigated. The dataset
has been processed and prepared for simpler machine learning models which serve as a
baseline. This includes the implementation of TF-IDF vectorization. The two baseline
models are Naïve Bayes and Logistic Regression, which have achieved classification
accuracies of 52.5% and 60.5% respectively for the 42-class dataset.

The next stage of the project focused on further enhancing the data preparation and
utilizing advanced deep learning models including Gated Recurrent Unit (GRU) and
Long Short-Term Memory (LSTM) models. By merging some similar categories, the
number of classes was reduced to 31, which resulted in a significant improvement in
accuracy. The GRU and LSTM models were developed and tuned, and both resulted in
improving the prediction accuracy over the baseline Logistic Regression model. The best
accuracy was achieved by the GRU. The best overall classification accuracy was 69.3%
which is a significant improvement over the baseline of 60.5%. This project has demonstrated that neural networks are better suited to NLP tasks than traditional models, but
feature engineering and data preparation play an even more important role in improving
classification accuracy.
