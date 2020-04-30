# Part-o-Speech Tagger

In this work we provide 3 different PoS_taggers: **Perceptron**, **Hidden Markov model** and **Decision Tree** based on the French treebanks of the corpora of the *Universal Dependencies* project.

- Perceptron is designed and implemented by ourselves.
- Hidden Markov model is built by using Pomegranate library.
- Decision Tree is imported from sklearn library.

# Backgruond

In corpus linguistics, a Part-of-Speech (PoS) is a category of words which have similar grammatical properties as nouns, verbs, adjectives, adverbs, etc. Part-of-Speech tagging, which can be considered as a multi-class classification problem, is the process of determining the syntactic category (PoS) of a word from the words in its surrounding context.

PoS tagging is a relatively easy task: as long as there are enough training data of the same domain, a simple multi-class classifier with very simple features achieve human-comparable performance. However, PoS taggers performance degrades significantly when they are applied to sentences that depart from training data. In this work, We aim to evaluate and characterize the impact of changes in domain and develop the features and models that makes our PoS taggers robust to the different combination of train and test sets.

For details, click [HERE](https://github.com/JiangnanH/PoS_Classifier/blob/master/Rapport_de_Projet_final_de_Machine_Learning.pdf).
