---
layout: lesson
lesson: 5&mdash;Intro to NLP and RNNs
youtube_id: qvRL74L81lg
wiki_file: Lesson_5
notes_file: Lesson_5_Notes
forum_thread: lesson-5-discussion
prev_url: lesson4.html
next_url: lesson6.html
---

We start by combining everything we've learned so far to see what that buys us; and we discover that we get a Kaggle-winning result! One important point: in this lesson we add batch normalization to VGG, and in the original classroom setting we updated the VGG16 class directly with this new implementation. However, in a MOOC setting where everyone is going at their own pace, that's not an option&mdash;so therefore we've created a separate "Vgg16BN" class for you to use if you want to use the version with batchnorm (which we highly recommend).

Next up, we return to collaborative filtering, and find that we can quickly and easily build models that dramatically surpass all benchmarks that a quick bit of Googling turns up. We then turn our attention to visualizing the *latent factors* that these models have created, and in the process learn about which particular Church of Scientology movies are best avoided...

We also take a look at the wonderful keras *functional API*, which we'll be using a lot from here on out, since it provides great power and flexibility in building architectures.

We're finally ready now to start looking at natural language processing (NLP), and we start by seeing how the *embeddings* that we developed in the previous section can help us understand natural language. The particular NLP task that we focus on in this lesson is *sentiment analysis*, however note that everything we learn here will be equally useful for any other NLP classification task (eg spam, fraud, or 'fake news' classification; finding relevant documents in legal discovery; and so forth). We also learn about the equivalent of transfer learning in NLP, which is the use of *pre-trained word vectors*. This is a critical tool that makes models faster to train, require less data, and more generalizable.

We close with a quick introduction to recurrent neural networks (RNNs), including looking at a "visual vocabulary" for neural network architectures, which we'll use for the rest of the course.
