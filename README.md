This repository contains code with task descriptions, guidelines, and baselines, for the "CoLI-Dravidian 2024: Word-level Code-Mixed Language Identification in Dravidian Languages" https://sites.google.com/view/coli-dravidian-2024/home

# CoLI-Dravidian_2024
Baseline models for Word-level Code-Mixed Language Identification in Dravidian Languages

# Task Description
Language Identification (LI) involves detecting the language(s) used in a given text, which is a preliminary step for many applications such as sentiment analysis, machine translation, information retrieval, and natural language understanding. In multilingual India, especially among the youth, social media often features code-mixed text, blending local languages with English at various levels. However, this poses significant challenges for LI, particularly when languages are mixed within a single word. Dravidian languages, extensively spoken in southern India, are under-resourced despite their rich morphological structure. These languages face technological challenges, especially in script representation on digital platforms, leading users to prefer Roman or hybrid scripts for communication. This prevalent code-mixing offers vast linguistic data for research, yet remains understudied.

To address word-level LI challenges in Dravidian languages, we are conducting a shared task by providing datasets for four languages -- Kannada, Tamil, Malayalam, and Tulu -- encouraging the development of advanced LI models.

# Guidelines
Code-mixed LI models will be evaluated using macro-averaged and weighted-averaged F1 scores.

During the training phase, each team will have 10 submission opportunities to submit their predictions on the validation set. During the testing phase, each team will have 5 submission opportunities to submit their predictions for the test set. The training set is for practice purposes only, and only the scores from the testing phase will be considered for ranking.

Submissions should follow the same structure as the Train set: a CSV file with two columns, "Word" and "Tag" named as predictions.csv for all subtasks, and then directly zip without any folder and name the zip file only TeamName_language_RunNo.zip, e.g., CIC_Kannada_Run3.zip. (Note: the csv file only predicsions.csv and zip file as mentioned)

Task related other information can also be found in https://codalab.lisn.upsaclay.fr/competitions/19357?secret_key=2a2a5128-ea6d-4b69-940a-f82b69fa0b98

# Baseline Models
Explored with various Machine Learning (ML) models and Conditional Random Field (CRF) model with ** Malayalam dataset**. These models can be utilized for provided datasets namely: Kannada, Tamil, and Tulu datasets respectively.
