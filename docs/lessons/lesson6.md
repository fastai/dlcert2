---
layout: lesson
lesson: 6&mdash;Building RNNs
youtube_id: ll9y1U0SoVY
wiki_file: Lesson_6
notes_file: Lesson_6_Notes
forum_thread: lesson-6-discussion
prev_url: lesson5.html
next_url: lesson7.html
---

This lesson starts by introducing a new tool, the *MixIterator*, which will (finally!) allow us to fully implement the pseudo-labeling technique we learnt a couple of lessons ago. This tool allows us to improve our best MNIST model even further, well into the top 5 on the 'academic leaderboard'.

We then look again at embeddings, using a spreadsheet to show how they really work "behind the scenes". We look both at embeddings for collaborative filterings, as well as embeddings for NLP.

After these shorter topics, we're ready to get to today's main event: building RNNs. We look at a variety of different models for RNNs, and create each one from scratch using basic keras building blocks.

Finally, we look at Theano for the first time, the library that keras is using to actually implement computation. In order to better understand how theano and RNNs work, we create our own RNN implementation in pure theano. Learning theano isn't necessary for everyone, but it can be critical when you discover that you need to implement something that doesn't yet exist in keras, or modify something for your particular project. It also helps building a deeper understanding of how deep learning really works.
