# NLP_to_Categorize_News_Articles

This is my final AIT (Artificial Intelligence Techniques) Project which was NLP (Natural Language Processing) classification using the HuffPost dataset in Kaggle. Included are the following files:

1. [The final report](NLP%20Final%20Project%20Report.pdf)
2. [The final presentation](NLP%20Final%20Presentation.pdf)
3. [The code for the final report](NLP%20Final%20Project%20Code.ipynb)
4. [The code for the undersampling evaluation](NLP%20Undersampling%20Evaluation%20Code.ipynb)
5. [The code for the Midsemester baseline](NLP_Project_Midsemester.ipynb)

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

### Introduction

In the digital age of today, vast quantities of updated information and news are available to
us constantly. For someone interested in reading the latest developments or researching past
articles on a particular topic, the news article must first be categorized so that it can easily be
identified as content that might be of interest and recommended to the user. With millions of 
news articles available online, researching, categorizing, and filtering through such quantities
is impractical for a human to do. Natural language processing (NLP) is required to categorize
these articles.
NLP is a branch of Artificial Intelligence (AI) concerned with training machines to read,
understand, interpret, and generate spoken and written human languages in a similar way
that humans can [2]. In NLP, algorithms are developed to process large amounts of language
data such as articles or documents, from which practical meaning and information can be
retrieved.
One common and important application of NLP is article classification or categorization.
This project is concerned with article classification. A news category dataset with over
200,000 article headlines and descriptions will be used in this project. The aim is to read and
interpret the headlines and descriptions and categorize them into one of 42 topic categories.
To achieve this, the project will be divided into several steps.
1. Literature Review: A literature review will be conducted to research existing methods
and models used in NLP for article classification as well as possible challenges
and limitations. The idea is to deploy a baseline first and then use more advanced
techniques to find the optimal solution to this challenge.
2. Exploratory Data Analysis (EDA): The dataset will be investigated to determine
what insights can be gained from it and to determine its quality and current suitability
to be used for this NLP project. Data wrangling will be performed to make the dataset
more suitable for the project.
3. Data Preparation: The text data will be cleaned, pre-processed and vectorized (word
embedded) to prepare it for the machine learning stage.
4. Establish a Baseline: A baseline model will be established to demonstrate the suitability
of this dataset in the field of article classification.
5. Identification of Challenges, and Improvement in Data Preparation: Issues faced
will be addressed and further techniques will be investigated to improve the data preparation
to improve the modelling performance.
6. Deployment of More Advanced Models and Techniques: The literature review has
identified several advanced algorithms that can be used in topic modelling. This step
and the previous will be used and refined testing various of these more advanced model
architectures to improve the news article classification accuracy.
