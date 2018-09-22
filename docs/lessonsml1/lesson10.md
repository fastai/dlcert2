---
layout: lessonml1
lesson: 10&mdash; More NLP and Columnar Data
youtube_id: 37sFIak42Sc 
forum_thread: wiki-lesson-thread-lesson-10
notes_url: http://forums.fast.ai/t/unofficial-lecture-10-notes/8538
prev_url: lesson9.html
next_url: lesson11.html
---
In today's lesson we'll further develop our NLP model by combining the strengths of naive bayes and logistic regression together, creating the hybrid "NB-SVM" model, which is a very strong baseline for text classification.

To do this, we'll create a new `nn.Module` class in pytorch, and look at what it's doing behind the scenes.

In the second half of the lesson we'll start our study of tabular and relational data using deep learning, by looking at the "Rossmann" Kaggle competition dataset. Today, we'll start down the feature engineering path on this interesting dataset.

We'll look at continuous vs categorical variables, and what kinds of feature engineering can be done for each, with a particular focus on using embedding matrices for categorical variables.