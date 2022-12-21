# Ind_Study

## RDX Independent Study Project

- The Responses file contains 23 instances of entrepreneurs writing a summary of their background and a list of their problems. These two text inputs have been tagged with a proposed labeling.

- The Responses_GPT file contains 23 new very realistic instances that were created using ChatGPT to give inspiration through a prompt, and then a generated number corresponding to an existing real data instance for further inspiration in order to match the distribution of the real data.

- The RDX EDA file contains some initial EDA as well as various different embeddings of the text features which are used in multilabel KNN to predict the corresponding tags for the text summary

- The RDX Data Expansion file contains code that will make a train and test split and create new files with synthetic data based on the train split only. This synthetic data is generated through a few different techniques such as synonym replacement, and random insertion, swapping, and deletion

- The RDX Models file contains a variety of models trained on the synthetic data and tested on the real data. Each of these models is performing multilabel text classification. The models include SVM, Logistic Regression, Naive Bayes, Decision Trees, and KNN, with SVM achieving the best performance.
