---
title: "IndicNLP"
weight: 0
---
           
Our work is focused on building a better ecosystem for Indian languages while also keeping up with the recent advancements in NLP. To this end, we are releasing our work on the following projects:

* <b>IndicNLP Corpora:</b> A lot of NLP models require a large amount of training data, which most of the Indian languages lack. In this project, we develop a large-scale Indic corpora by intesively crawling the web. The corpora that we build has a total of 8.9 billion tokens and covers 12 major Indian languages - making it the largest public corpus for most of the Indian languages
* <b>fastText:</b> fastText is a well-suited model for Indian languages because of their rich morphological structure. We pre-train and benchmark fastText embeddings on our corpora, producing embeddings that outperform the official fastText embeddings for Indian languages.
* <b>IndicBERT:</b> To improve performance and coverage of Indian languages on a wide variety of tasks, we also develop and evaluate IndicBERT. IndicBERT is a multilingual ALBERT model (a lighter variant of BERT) pre-trained on 12 major Indian languages. It provides state-of-the-art performance on some of the tasks. We also build a benchmark, called IGLUE, to evaluate the natural language understanding capabilities of language model.