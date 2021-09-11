# Unsupervised Machine Learning algorithms with NLP

# National Science Foundation (NSF) Research Awards Abstracts

Author: Francisco Genaro Cerna Fukuzaki

The dataset used in this Jupyter Notebook (Unsupervised_Machine_Learning_algorithms_with_NLP.ipynb) was downloaded from https://www.nsf.gov/awardsearch/download?DownloadFileName=2020&All=true. Its contains a ZIP file with more than 13,121 XML files.

The goal of this Notebook is to group abstracts of the NSF based on their semantic similarity developing an unsupervised model which classifies abstracts into a topic. The list of topics is not defined yet, it will be after training the model.

## **List of contents:**

1. [Download the dataset](#download-dataset)
2. [Extract the content of the raw dataset](#extract-content)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Text Preprocessing](#text-preprocessing)
    1. [Natural Language Toolkit (NLTK)](#nltk)
    2. [Stanza](#stanza)
    3. [Transformers](#transformers)
5. [Word Embedding](#word-embedding)
6. [Unsupervised clustering](#unsupervised-clustering)
    1. [K-Means](#k-means)
    2. [Hieralchical Clustering with Transformers](#hieralchical-clustering-transfomers)
7. [Saving the model](#save-model)
8. [Conclusions and Future works](#future-works)
9. [References](#references)

<a name="references"></a>
# References

1. Universal POS tags. Contains the name of each POS tags. https://universaldependencies.org/u/pos/
2. Part of Speech Tags. Contains the abreviations and meanings of the part of speech. https://cs.nyu.edu/~grishman/jet/guide/PennPOS.html