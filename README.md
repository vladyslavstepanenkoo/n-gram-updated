# N-Gram-Language-Model

Includes:
- [x] Index words
- [x] Store ngrams in a Trie data structure
- [x] Efficiently extract ngrams and their frequencies
- [x] Compute out-of-vocabulary (OOV) rate
- [x] Compute ngram probabilities with absolute discounting with interpolation smoothing.
- [x] Compute Perplexity

## Introduction

A statistical language model to predict the probability of a sequence of
words. It is to predict the next word in a sequence given a history context represented by the preceding words. 

## Training

Using Maximum Likelihood criteria, these probabilities can be estimated using counts.

## Perplexity

To meausre the performance of a language model, computed the perplexity of the test corpus using trained m-Grams.

## Results

Model was tested on europarl dataset (dir `data`):

Test PP with bigrams = 130.09

Test PP with trigrams = 94.82
