# POS-tagging

## Overview
This project involves parts-of-speech (POS) tagging using a Hidden Markov Model (HMM) and the Viterbi algorithm. The goal is to assign POS tags to words in a given corpus, which is a fundamental task in natural language processing (NLP).

## Project Structure
POS_code.ipynb: Main notebook containing the implementation of the POS tagging process.

## Methodology
Data Preprocessing: The corpus is tokenized and preprocessed to create a list of sentences with words and their corresponding POS tags.
Emission Matrix Creation: The emission probabilities are calculated.
Transition Matrix Creation: The transition probabilities are calculated for the POS tags.
Viterbi Algorithm: The Viterbi algorithm is used to predict the POS tags for each word in the sentences.
Accuracy Calculation: The accuracy of the POS tagging is computed by comparing the predicted tags with the actual tags.

## Results
Emission Matrix: The emission matrix B is created, showing the probabilities of each word given a POS tag.
Viterbi Algorithm Accuracy: The accuracy of the Viterbi algorithm is reported as 95.31%.
