---
layout: lesson
lesson: 1&mdash;Recognizing cats and dogs
youtube_id: Th_ckFbc6bI
overview_id: kzt3-FHdAeM
wiki_file: Lesson_1
notes_file: Lesson_1_Notes
timeline: Lesson_1_Timeline
forum_thread: lesson-1-discussion
prev_url: aws.html
next_url: lesson2.html
---
**Important note**: All files in the course are now available from [files.fast.ai](http://files.fast.ai), rather than platform.ai, as shown in the videos. We have attempted to update all mentions of platform.ai to files.fast.ai on the wiki, forums, etc, but youtube does not allow us to change the videos themselves.

Welcome to the first full lesson of Practical Deep Learning For Coders! Before you start this lesson, be sure to have completed setup of your deep learning server. See the [AWS Lesson](aws.html) to learn how to do this, if you haven't already.

Each lesson page includes links to course notes, forum discussion, and (most importantly) a wiki page. Nearly all the participants in the original in-person course said that they found these resources very important for successfully completing the course. So be sure to make the most of them! And be sure to carefully read the [Getting Started](../start.html) page to find out how this course is designed and how to get the most out of it. (Also, apologies that the questions from the audience are hard to hear - we get a special audience mic from lesson 3 onwards which resolves that problem.)

### Synopsis

The 30 minute overview video introduces you to the course and explains how to get the most out of each lesson. We also pass on some tips from previous students.

The lesson video starts with a very brief overview of what deep learning is, and why it matters, and then discusses how to access the files for this lesson. However, note that for this MOOC you will probably find it easier to *use git instead*. The [Getting Started](../start.html) page explains how. Then we show how to start, stop, and manage your AWS instance, how to copy data to it, and so forth (if you're already familiar with AWS you can probably go through this part fairly quickly).

The next point discussed is how to the data for this lesson (and indeed all the computer vision projects we'll tackle) needs to be structured. This is the most important step for you to complete&mdash;if your data is not structured correctly you will not be able to train any models.

Then we get into our first deep learning model (click 'Timeline' on the left to jump straight to any part of the video). We learn how to classify dogs from cats. Rather than understanding the mathematical details of how this works, we start by learning the nuts and bolts of how to get the computer to complete the task, using 'fine-tuning', perhaps the most important skill for any deep learning practitioner. Once we've built a model that can classify dogs from cats, we then take a step back and learn about the original "pre-trained" model that we started with, and examine what it can do without any fine-tuning. Next lesson, we'll learn about how fine-tuning actually works "behind the scenes".
