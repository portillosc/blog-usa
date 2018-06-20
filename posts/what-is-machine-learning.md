---
authors:
- Jeannine Stark
tags:
- Culture
- Language
date: 2018-04-30T21:05:05.000Z
title: "What is Machine Learning?"
image: 
---

Machine Learning is another aspect of the Big Data ecosystem as well as a type of Artificial Intelligence. More about what Big Data is can be found [in a previous blog entry](https://blog.ippon.tech/what-is-big-data/). Artificial Intelligence is capabilities where computers act or perform human like tasks. One primitive version of Artificial Intelligence that has been around for decades are computer card games. In this case a computer is programmed to behave like a human, making decisions on the card to play based on the situation. As machines got more powerful Machine Learning became a subcategory of Artificial Intelligence. In the card game the program had explicit rules for what to do in a situation whereas Machine Learning is where the program determines what to do based on prior data. The program determines what to do based on its training to produce a model. The training aspect of the machine learning is giving the computer enough data to make determinations. There is no magic amount of data that will provide the correct answer. In the card example the training would be done off data about what moves the prior player made. The output of the training is called the model. The model tells the computer what moves to make based on the situation in the game being played. There are two different ways to train a machine learning model, supervised and unsupervised learning.

In supervised learning the Machine Learning model is trained based on previously captured data and the known output. One of the most basic use cases I have seen for this is document classification. The training data would be a set of documents with the classification. In the data set, Document A would be the input and "medical document" would be the classification, Document B would be the input and the classification would be a "Credit Card statement" and so on. The model would be trained based on this information so when a new document is received the type of document can be determined.

In unsupervised learning the machine learning model determines the output based on the data that is given. Then future data can be placed into the appropriate output. A common use case for this would be clustering of like information. The clusters are not predetermined but decided by the machine learning algorithm. One use case for a clustering algorithm is to group similar movies together. A movie database would provide details about the movie and then cluster similar movies together. By allowing the model to be created without dictating what the clusters should be will allow the machine to determine what features cause movies to be similar to one another. This will allow different suggestions that typically might not have been thought of before.

Both supervised and unsupervised learning need to be programmed to get an output model using an algorithm. So what is this algorithm and how do you determine which one to use? The algorithms are mathematical equations used to build the model. Since they are mathematical equations any text needs to be converted to numbers. Converting the text to number is called feature extraction. There are different ways of doing this but one of the most popular ones for blobs of text is the TF-IDF which stands for “term frequency-inverse document frequency”. For textual categories those can simply be translated to numbers. In simple terms TF-IDF means in a collection of documents we determine how important a word is by calculating how many times that word appears in the documents and how many documents the word appears in. For example in machine learning algorithms for determining if an email is spam a word can be identified as a “spam word”. If a word appears in the majority of the emails that were marked as spam and appears infrequently in the emails that were marked as not spam, the word can be used to identify emails that are spam. Now that the features have been extracted, the correct algorithm needs to be picked. There are multiple different algorithms that can fulfill a specific purpose so multiple models should be tested to get the best model for your data. First, to choose the correct algorithm, you must know if you are going to use supervised or unsupervised learning. There are different algorithms for each one. Next, with supervised learning based on your use case you need to decide between classification and regression algorithms. Classification algorithms as previously discussed are for labelling data in a specific way such as type of document or spam emails. Regression algorithms are used when the output of the data are continuous values. A simple use case for regression would be predicting salaries based on years of experience.

Machine Learning can help companies by making things more efficient with predictions. These predictions can help either improve customer relationships by predicting behavior or what a person might find convenient or using predictions to help reduce manual tasks that a person needs to do. The cost of machine learning is getting enough upfront data so that a model can be produced.