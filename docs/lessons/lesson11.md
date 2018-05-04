---
layout: lesson2
lesson: 11&mdash;Neural Translation
youtube_id:NFVKDa5W35I
forum_thread: part-2-lesson-11-wiki
prev_url: lesson10.html
next_url: lesson12.html
---

Today we’re going to learn to translate French into English! To do so, we’ll learn how to add *attention* to an LSTM in order to build a *sequence to sequence (seq2seq) model*. But before we do, we’ll do a review of some key RNN foundations, since a solid understanding of those will be critical to understanding the rest of this lesson.

A seq2seq model is one where both the input *and* the output are sequences, and can be of difference lengths. Translation is a good example of a seq2seq task. Because each translated word can correspond to one or more words that could be anywhere in the source sentence, we learn an attention mechanism to figure out which words to focus on at each time step. We’ll also learn about some other tricks to improve seq2seq results, including *teacher forcing* and *bidirectional models*.

We finish the lesson by discussing the amazing DeVISE paper, which shows how we can bridge the divide between text and images, using them both in the same model!

