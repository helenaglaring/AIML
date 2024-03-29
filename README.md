# AI & ML 2023 - Sentiment Analysis of Drug Reviews
Exam project in Artificial Intelligence and Machine Learning (CBS, cand.merc.it, 2. semester)

Marza Mustafa & Helena Glaring

Jupyter Notebook: [AIML_drug_review_colab.ipynb](https://github.com/helenaglaring/AIML/blob/main/AIML_drug_review_colab.ipynb)

## Dataset

**Dataset:** [UCI ML Drug Review dataset](https://www.kaggle.com/datasets/jessicali9530/kuc-hackathon-winter-2018)


### General information about dataset

**Data Set Information:**

The dataset provides patient reviews on specific drugs along with related conditions and a 10 star patient rating reflecting overall patient satisfaction. The data was obtained by crawling online pharmaceutical review sites. The intention was to study 

(1) sentiment analysis of drug experience over multiple facets, i.e. sentiments learned on specific aspects such as effectiveness and side effects, 
(2) the transferability of models among domains, i.e. conditions, and 
(3) the transferability of models among different data sources (see 'Drug Review Dataset (Druglib.com)'). 

The data is split into a train (75%) a test (25%) partition (see publication) and stored in two .tsv (tab-separated-values) files, respectively

- *Source* https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29

**Attribute Information:**
1. drugName (categorical): name of drug 
2. condition (categorical): name of condition 
3. review (text): patient review 
4. rating (numerical): 10 star patient rating 
5. date (date): date of review entry 
6. usefulCount (numerical): number of users who found review useful


**Relevant Papers:**

Felix Gräßer, Surya Kallumadi, Hagen Malberg, and Sebastian Zaunseder. 2018. Aspect-Based Sentiment Analysis of Drug Reviews Applying Cross-Domain and Cross-Data Learning. In Proceedings of the 2018 International Conference on Digital Health (DH '18). ACM, New York, NY, USA, 121-125. DOI: [Web Link](https://dl.acm.org/doi/10.1145/3194658.3194677)

## Structure of the Jupyter Notebook
Following the CRISP-DM framework

1. Business Understanding
2. Data understanding
    - EDA
3. Preprocessing
4. Modeling 
5. Evaluation


## Dependencies

- Jupyter Notebook
- Python 3.9.7
- numpy
- pandas
- matplotlib
- seaborn
- pandas-profiling
- wordcloud
- plotly
- scikit-learn
- bs4
- nltk
- spacy
- imbalanced-learn
- tensorflow
- tensorflow_hub
- tensorflow_text
- transformers



