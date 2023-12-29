# SkimLit 📄🔥
In this project, I'm going to build an NLP model to classify abstract sentences into the role they play, which allow researchers to skim through the literature.

## Dataset
In this project, the **PubMed 20k** Dataset was used to build a model. This is a source of used dataset: https://github.com/Franck-Dernoncourt/pubmed-rct. This is a subset of PubMed 200k dataset described in Franck Dernoncourt, Ji Young Lee. [PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071) International Joint Conference on Natural Language Processing (IJCNLP). 2017.

## Model Experiments
> **Model 0:** Multinomial Naive Bayes Model

> **Model 1:** Conv1D Model with Custom Token Embeddings

> **Model 2:** Feature Extraction model with Universal Sentenve Encoder USE

> **Model 3:** Conv1D Model with Custom Character Embeddings

> **Model 4:** Pretrained Token Embeddings + Character Embeddings

> **Model 5:** Pretrained Token Embeddings + Character Embeddings + Positional Embeddings
