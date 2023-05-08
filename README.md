# Multilateration Powered Classification

We introduce a new embedding for numerically encoding and classifying sen- tences, or, as we like to call it, bags of words. I will explain how we treat our bags of words as a set of landmarks, find unique distances between these landmarks, and associate positive, nega- tive, and neutral words around similar distant landmarks.

## Dataset

https://github.com/cjhutto/vaderSentiment

Our problem space is Twitter posts and we uti- lized the Valence Aware Dictionary and Sen- timent Reasoner (VADER) dataset. VADER is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media (Hutto and Gilbert, 2014). We use the VADER Sentiment Analy- sis dataset to synthetically test our embedding. The VADER dataset is fully open-sourced un- der the MIT License.

## Morales_Lladser_Paper.pdf

Contains the full paper about this project

## Morales_Lladser_Presentation.pdf

Contains the research presentation presented at CU Boulder and SIAM
