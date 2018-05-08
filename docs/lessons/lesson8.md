---
layout: lesson2
lesson: 8&mdash;Object Detection 
youtube_id: Z0ssNAbe81M
forum_thread: part-2-lesson-8-wiki
prev_url: lessons2.html
next_url: lesson9.html
---

Welcome to *Cutting Edge Deep Learning for Coders*, part 2 of fast.ai’s deep learning course. This part covers lessons 8 to 14, and assumes you have already completed lessons 1 to 7 from [part 1](http://course.fast.ai). If you’re already a deep learning practitioner, feel free to try starting with this part&mdash;if you find that you’re not familiar with the topics discussed, you can always return to part 1. In particular, we assume that you’re familiar with:

* The Pytorch and fastai libraries
* CNNs and RNNs
* Modern techniques for training and regularizing neural networks.

Lesson 8 starts with a quick recap of what we’ve learned so far, and introduces the new focus of this part of the course: *cutting edge research*. We talk about how to read papers, and what you’ll need to build your own deep learning box to run your experiments. Even if you’ve never read an academic paper before, we’ll show you how to do so in a way that you don’t get overwhelmed by the notation and writing style. Another difference in this part is that we’ll be digging deeply into the source code of the fastai and Pytorch libraries: in this lesson we’ll show you how to quickly navigate and build an understanding of the code. And we’ll see how to use python’s debugger to deepen your understand of what’s going on, as well as to fix bugs.

The main topic of this lesson is *object detection*, which means getting a model to draw a box around *every* key object in an image, and label each one correctly. You may be surprised to discover that we can use transfer learning from an Imagenet classifier that was never even trained to do detection! There are two main tasks: find and localize the objects, and classify them; we’ll use a single model to do both these at the same time. Such multi-task learning generally works better than creating different models for each task&mdash;which many people find rather counter-intuitive. To create this custom network whilst leveraging a pre-trained model, we’ll use fastai’s flexible *custom head* architecture.

