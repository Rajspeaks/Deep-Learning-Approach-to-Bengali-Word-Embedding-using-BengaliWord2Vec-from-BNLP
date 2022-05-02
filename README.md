# Bengali Word Embedding using BengaliWord2Vec

This is a mini project on Bengali Word Embedding using BengaliWord2Vec Model from BNLP (Bengali Natural Language Processing) Toolkit under the mentorship of Prof. Sandipan Ganguly, Heritage Institute of Technology, Kolkata-India.

### What is BNLP?

BNLP is a natural language processing toolkit for Bengali Language. This tool will help you to tokenize Bengali text, Embedding Bengali words, Bengali POS Tagging, Construct Neural Model for Bengali NLP purposes. Developed by [Prof. Sagor Sarker](https://github.com/sagorbrur) from Bangladesh. 

_**Source Link: https://bnlp.readthedocs.io/en/latest/#word-embedding**___

_**BNLP GitHub : https://github.com/sagorbrur/bnlp**___

## Installation:

* 
  pypi package installer(python 3.6, 3.7, 3.8 tested okay)

  ``pip install bnlp_toolkit``

  or Upgrade

  ``pip install -U bnlp_toolkit``

## What is Word Embedding?

A word embedding is a learned representation for text where words that have the same meaning have a similar representation.
It is this approach to representing words and documents that may be considered one of the key breakthroughs of deep learning on challenging natural language processing problems.

### What is Word2Vec?

Word2Vec is a statistical method for efficiently learning a standalone word embedding from a text corpus.

### What is CBOW & Skip-Gram?

The CBOW model learns the embedding by predicting the current word based on its context. 
The continuous skip-gram model learns by predicting the surrounding words given a current word.

_(Information Source: https://machinelearningmastery.com/what-are-word-embeddings/)_

### BengaliWord2Vec:

BengaliWord2Vec is a Library function from BNLP Toolkit. It helps in embedding words to find similar meaning of words and  also generating vectors of those words.

### Methodology:

- At first I have imported BengaliWord2Vec function from BNLP.
- Then I took a pre-trained model bnwiki_word2vec.model.
- Took a bengali word and got the generate both the vector-shape and vector-values of that bengali word.
- Repeated the above step by taking another bengali word.
- In the next step I have taken a bengali word along with the pre-trained model (bnwiki_word2vec.model) and then applied BengaliWord2Vec function. Also, I have limited the range of output to max 10 words of similar meaning in that code. Hence, I got the output of 10 bengali words along with their vector values, carrying approximately similar/relevant/nearest meaning of that bengali word mentioned in the code. 
- Repeated the previous step 9 times more but took different bengali sample words & took different no. of word limits to continue testing & got the output of approximately similar/relevant/nearest bengali words of that sample word mentioned in the code.

### Tools:

1. Jupyter Notebook (You can use Google Colab also)
2. Language: Python
3. BNLP; Link: https://bnlp.readthedocs.io/en/latest/#word-embedding

### Developer:

- [Rajdeep Das](https://github.com/Rajspeaks)

LinkedIn Profile: https://www.linkedin.com/in/itsrajdeepdas/ 

#### Note:

All bengali words in the output are not similar meaning of thee word I took in code but many of them are close to the meaning. 

## Thank you

