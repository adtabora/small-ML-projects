# Small Machine Learning Projects
This a collection of small Machine Learning projects that I made to test libraries, algorithms, and new models.

You can use these notebooks as a tutorials to learn how to use some models and libraries.

## Natural Language Processing (NLP)
There are a lot of applications for NLP one of which is Information Extraction. Information Extraction is the task of 
extracting structured data from an unstructured data source. This involves a series of tasks which will be demonstrated 
on the following collection.

### Named Entity Recognition (NER)

For Information Extraction it is important to recognize named entities and their type (e.g. Location, Organization, Person etc). 
In the following mini-projects I test some of the most popular models.

- [Hidden Markov Models (HMM)](https://github.com/adtabora/small-ML-projects/blob/master/HMM.ipynb): Train a NLTK HMM tagger and use it for NER.
- [Conditional Random Field (CRF)](https://github.com/adtabora/small-ML-projects/blob/master/CRF%20.ipynb): Train a CRF a more general model than HMM that is discriminative.
The library used is sklearn-crfsuite.

### Relation Extraction
- String Subsequence Kernel + SVM. ** In Progress ** : Use the SSK with a SVM from the shogun-toolbox library.
- Distant Supervision ** Planned **
