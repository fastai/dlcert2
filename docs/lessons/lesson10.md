---
layout: lesson2
lesson: 10&mdash;Multi-modal &amp; GANs
youtube_id: uv0gmrXSXVg
wiki_file: lesson-10-wiki
forum_thread: lesson-10-discussion
prev_url: lesson9.html
next_url: lesson11.html
---

A surprising result in deep learning is that models created from totally different types of data, such as text and images, can learn to share a consistent feature space. This means that we can create _multi-modal models_; that is, models which can combine multiple types of data. We will show how to combine text and images in a single model using a technique called _DeVISE_, and will use it to create a variety of search algorithms:

* Text to image (which will also handle multi-word text descriptions)
* Image to text (including handling types of image we didn't train with)
* And even image to image!

Doing this will require training a model using the whole imagenet competition dataset, which is a bigger dataset than we've used before. So we're going to look at some techniques that make this faster and easier than you might expect.

We're going to close our studies into generative models by looking at generative adversarial networks (GANs), a tool which has been rapidly gaining in popularity in recent months, and which may have the potential to create entirely new application areas for deep learning. We will be using them to create entirely new images from scratch.
