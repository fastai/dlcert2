---
layout: lesson
lesson: 1&mdash;Recognizing cats and dogs
youtube_id: IPBSB1HLNLo
forum_thread: wiki-lesson-1
prev_url: lessons.html
next_url: lesson2.html
---
Welcome to the start of your fast.ai journey! In today’s lesson you’ll set up your deep learning server, and train your first image classification model (a convolutional neural network, or CNN), which will learn to distinguish dogs from cats nearly perfectly. If you need help at any time, head over to [forums.fast.ai](http://forums.fast.ai) where over a thousand students are discussing the course and have provided lots of tips and tricks for you.

Each lesson page includes a link to a forum topic that includes a hyperlinked timeline, links to further resources, and a discussion of the lesson. Nearly all the participants in the original in-person course said that they found these resources very important for successfully completing the course. So be sure to make the most of them! And be sure to carefully read the [Getting Started](../start.html) page to find out how this course is designed and how to get the most out of it.

### Important notes!

- You need an Nvidia GPU to complete this course, and this video shows how to set up a GPU server on a system called [Paperspace](http://www.paperspace.com). Note that the setup steps **have been simplified** since this video was created. You no longer need to set up the server from scratch. Instead, when prompted for a template, don't choose 'Ubuntu' as shown in the video, but instead choose 'Public Templates' and then 'fast.ai'. Reshama Shaikh has kindly provided [written step by step instructions](https://github.com/reshamas/fastai_deeplearn_part1/blob/master/tools/paperspace.md) on the whole process
- You are not expected to understand all the code in today's lesson yet! Don't worry, by the end of the course, not only will every line be explained, but you'll also be able to write the underlying network and training routines yourself from scratch. But for now, just focus on being able to *run the code* and *understand the inputs and outputs* to each step. We teach top-down, which means we first show how to create world-class models in practice, then we gradually drill down into the details of how the model works, and then build it back up again.

### Lesson notes

We learn today how to classify dogs from cats. Rather than understanding the mathematical details of how this works, we start by learning the nuts and bolts of how to get the computer to complete the task, using 'fine-tuning', perhaps the most important skill for any deep learning practitioner. In a later lesson we'll learn about how fine-tuning actually works "behind the scenes".

An important point discussed is how the data for this lesson needs to be structured. This is the most important step for you to complete&mdash;if your data is not structured correctly you will not be able to train any models.

