# BPE-Forge
Built a custom BPE tokenizer using Hugging Face’s Tokenizers on WikiText-103. Designed for transformer models with subword segmentation, vocab tuning, and special token support. Enabled JSON export and validation. Highlights my NLP infrastructure skills in optimizing tokenization for speed, accuracy, and seamless integration.

In this project, I designed and trained a Byte-Pair Encoding (BPE) tokenizer optimized for transformer architectures using Hugging Face’s Tokenizers library. Working with the WikiText-103 dataset, I implemented subword segmentation with fine-grained vocabulary tuning and special token support to maximize efficiency and accuracy in NLP pipelines. The tokenizer supports seamless JSON export and rigorous token validation, making it ready for integration with downstream transformer models. This repository highlights my deep expertise in NLP infrastructure—building tools foundational to modern language understanding systems. It demonstrates not only technical precision but also strategic foresight in optimizing tokenization, a critical yet often overlooked component that significantly impacts model performance and training speed.   

## Features

 Trained on WikiText-103 corpus
 Vocabulary tuning and subword segmentation
 JSON export for seamless integration

##  Tech Stack

 Python, Hugging Face Tokenizers
 NumPy, JSON
 CLI-based training and evaluation

## Add-ons

 Special token handling ([PAD], [CLS], [SEP])
 Visual comparison of token frequencies
 Length distribution analysis

##  Structure

  `tokenizer.py` — Training script  
  `vocab.json` — Trained vocabulary  
  `stats/` — Token usage plots

##  Status

 BPE model finalized  
 Plug-and-play ready for transformer models  

