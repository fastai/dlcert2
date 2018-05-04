---
layout: lesson2
lesson: 10&mdash;NLP Classification and Translation
youtube_id: h5Tz7gZT9Fo
forum_thread: part-2-lesson-10-wiki
prev_url: lesson9.html
next_url: lesson11.html
---

After reviewing what we’ve learned about object detection, today we jump into NLP, starting with an introduction to the new *fastai.text* library. This is a replacement for *torchtext* which is faster and more flexible in many situations. A lot of today’s class will be very familiar&mdash;we’re covering a lot of the same ground as lesson 4. But today’s lesson will show you how to get much more accurate results, by using *transfer learning for NLP*.

Transfer learning has revolutionized computer vision, but until now it largely has failed to make much of an impact in NLP (and to some extent has been simply ignored). In this class we’ll show how pre-training a full language model can greatly surpass previous approaches based on simple word vectors. We’ll use this language model to show a new state of the art result in text classification.

