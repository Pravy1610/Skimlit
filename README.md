# Skimlit
Project Outline:  
The SkimLit project aims to build a deep-learning model capable of sequential sentence classification. The goal is to create an abstractive
text summarization system that can take lengthy research articles and produce shorter, informative summaries easy to skimmable. In this project, I try to replicate the deep learning model 
behind the 2017 paper  PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts( https://arxiv.org/abs/1710.06071). PubMed 200k RCT is a 
dataset based on PubMed for sequential sentence classification. The dataset consists of approximately 200,000 abstracts of randomized controlled trials, totalling 2.3 million
sentences. Each sentence of each abstract is labelled with its role in the abstract using one of the following classes: background, objective, method, result, or conclusion. 
The goal of the dataset was to explore the ability of NLP models to classify sentences which appear in sequential order.    

Project Structure:
1. Data Collection --> Download the dataset from GitHub (https://github.com/Franck-Dernoncourt/pubmed-rct).   
2. Data Preprocessing --> Preprocessing dataset to prepare the data for modelling. Preprocess the text data by removing any irrelevant information, special characters,
    or unwanted elements. Tokenize the text into words or subwords and convert them into numerical representations.
3. Exploratory Data Analysis(EDA) --> Performing data exploration to understand the characteristics of the dataset. Analyzing the distribution of paper lengths, summary lengths, and other relevant statistics. Making numerical labels since Machine Learning models require numeric labels.To numerically encode labels  Scikit-Learn's OneHotEncoder and LabelEncoder class is used.
4. 
