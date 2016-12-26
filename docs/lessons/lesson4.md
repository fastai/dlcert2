---
layout: lesson
lesson: 4&mdash;Collaborative filtering, embeddings, and more
youtube_id: V2h3IOBDvrA
wiki_file: Lesson_4
notes_file: Lesson_4_Notes
timeline: Lesson_4_Timeline
forum_thread: lesson-4-discussion
prev_url: lesson3.html
next_url: lesson5.html
---

When we ran this class at the Data Institute, we asked what students were having the most trouble understanding, and one of the answers that kept coming up was "convolutions". So, we start with a detailed look at the convolution operation, by implementing a couple of convolutional layers and filters in a spreadsheet. Next up, we give SGD (and modern accelerated variants) the same treatment. Once you've seen how easy accelerated SGD methods are, try reading the [original](https://arxiv.org/pdf/1412.6980.pdf) [papers](http://www.magicbroom.info/Papers/DuchiHaSi10.pdf)&mdash;notice how even the most complex deep learning papers tend to look simple once you've digested and implemented them?

Then we look further into avoiding over-fitting, and learn a clever trick for datasets where you have a lot more unlabeled data than labeled data (that is, *semi-supervized learning* scenarios): "pseudo-labeling" and "knowledge distillation".

Finally, we move away from computer vision for the first time, to discussion recommendation systems, and in particular, collaborative filtering techniques. This is both a useful technique of itself, and will also be a great introduction to *embeddings*, which is going to be critical when we learn about natural language processing in the next lesson.
