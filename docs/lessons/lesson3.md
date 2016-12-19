---
layout: lesson
lesson: 3&mdash;Under fitting and over fitting
youtube_id: 6kwQEBMandw
wiki_file: Lesson_3
notes_file: Lesson_3_Notes
forum_thread: lesson-3-discussion
prev_url: lesson0.html
next_url: lesson4.html
---

We've now seen a number of ways to build CNNs&mdash;it's time to build a more complete understanding of how they work. In this lesson we review in more detail what a convolution does, and how they are combined with max pooling to create a CNN. We also learn about the softmax activation function, which is critical for getting good results in classification models (a *classification* model is any model that is designed to separate data items into *classes*, that is, into discrete groups). NB: If you're having trouble understanding the convolution operation, you may want to skip ahead and watch the start of [lesson 4](lesson4.html), since it opens with a spreadsheet-based explanation of convolutions.

Then we delve into the most important skill in creating an effective model: dealing with overfitting and underfitting. The key is to first of all build a model that overfits (since then we know we have enough model capacity and know that we can train it) and then gradually use a number of strategies to reduce the overfitting. In this lesson the *most important* section is where we look at the list of techniques used to address overfitting. We suggest copying this list somewhere convenient, and refer to it often; ensure you understand what each of the steps means, and how to do them.

We then look at two particularly useful techniques to avoid overfitting: dropout, and data augmentation. We also discuss the extremely handy technique of pre-computing convolutional layers. Make sure you understand this technique before you continue, and practice it yourself, since we'll be using it in every lesson and every notebook from here on!
