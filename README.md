## Description of Project
This project provides an automated assessment of translation quality of Google Translate with human experts by using sentiment and semantic analysis. We select the classic early twenties-century novel 'The True Story of Ah Q' and translate the given text from Chinese to English by Google Translate. Our aim is to exaimine the precision of Google Translare's translation in terms of sentiment and semantic analysis when compared to human expert translations.

## Description of Dataset
**SenWave dataset**: The SenWave dataset features Tweets from March 1 2020 to May 15 2020 and contains 10,000 human labelled Tweets which enabled it to be utilised in various studies, particularly for refinining pre-trained model(BERT model). We utilized the latest version of SenWave dataset https://github.com/gitdevqiang/SenWave/blob/main/labeledtweets/labeledEn.csv.

**The True Story of Ah Q**: The True Story of Ah Q is a classic short novel that depicts the real life of Chinese society in 1911. The story contains numerous expressions of emotions including empathy,
humour, hopelessness and irony. It consists of nine chapters and was firstly published in 1921.

## Models
**BERT-based model**: The BERT model is a pre-trained large language model that employs the Transformer deep learning model that incorporates an attention mechanism in an LSTM-based model. We use a BERT-based model to implement sentiment analysis of each sentence and provide a summary of the chapter-wise sentiment.

**MPNet model**: Wee employ the MPNet-based sentence embedding model to quantitatively observe the similarities between the three translations.

## Notebook Links

**Data prepricessing file(from jupyter_notebook folder)**: Data prepricessing code work.

**Sentiment analysis file(from jupyter_notebook folder)**: Sentiment analysis code work.

**Semantic analysis file(from julyter_notebook folder)**: Semanrix analysis code work.

## Results part
Here are some visualized results derived from our sentiment and semantic analysis:

plots_for_sentiment_analysis folder

plots_for_semantic_analysis folder

polarity_score folder




