# IF5153 Natural Language Processing Practicals

This repository contains my work of eight practical assignments for the 2025 IF5153
Natural Language Processing course. Each assignment is presented in a Jupyter
Notebook.

## Practical assignments

| No. | Topic | Description |
| ---: | --- | --- |
| 1 | [Basic NLP processing](01-13522144.ipynb) | Introduces sentence splitting, tokenization, stemming, lemmatization, named-entity recognition and masking, part-of-speech tagging, noun-phrase chunking, and dependency parsing using spaCy and NLTK. |
| 2 | [Classical sentiment classification](02-13522144.ipynb) | Builds a text-sentiment classification pipeline with preprocessing, Bag of Words, TF-IDF, and SVD. It trains and compares Logistic Regression, Linear SVC, and Multinomial Naive Bayes, then analyzes feature choices and tunes model parameters. |
| 3 | [Word embeddings and neural networks](03-13522144.ipynb) | Compares pretrained Word2Vec, GloVe, and FastText embeddings with BoW/TF-IDF features for sentiment classification. The representations are evaluated with CNN, simple RNN, and LSTM architectures. |
| 4 | [Transformer-based sentiment classification](04-13522144.ipynb) | Fine-tunes and compares BERT, RoBERTa, and XLM-R for sentiment classification. It also examines their WordPiece, BPE, and SentencePiece tokenization strategies. |
| 5 | [Named Entity Recognition](05-13522144.ipynb) | Prepares token-level NER data, aligns labels with subword tokens, and compares shallow, deep, and transformer approaches: Logistic Regression with Word2Vec, Bi-LSTM, ALBERT, DeBERTa, XLM-R, and RoBERTa. |
| 6 | [Aspect-Based Sentiment Analysis with prompting](06-13522144.ipynb) | Uses Gemma 3 for aspect-level sentiment inference and compares prompting strategies, including zero-shot, simple instruction, few-shot, chain-of-thought, self-consistency, knowledge augmentation, and combined few-shot chain-of-thought prompting. |
| 7 | [Parameter-efficient fine-tuning for Indonesian QA](07-13522144.ipynb) | Fine-tunes a 4-bit Llama 3.2 1B Instruct model on the IndoQA dataset using LoRA and Unsloth. It covers prompt formatting, adapter training and saving, inference, and answer evaluation. |
| 8 | [Retrieval-Augmented Generation](08-13522144.ipynb) | Implements a RAG question-answering system for ITB academic regulations. It loads and chunks regulation documents, creates sentence-transformer embeddings and a FAISS index, retrieves relevant passages, and connects them to the fine-tuned QA model through a LangChain pipeline. |

## Repository structure

The notebooks follow the naming convention `NN-13522144.ipynb`, where `NN`
is the practical number from `01` to `08`.