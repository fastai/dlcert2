---
layout: lesson2
lesson: 13&mdash;Neural Translation
youtube_id: -lx2shfA-5s
wiki_file: lesson-13-wiki
forum_thread: lesson-13-discussion
prev_url: lesson12.html
next_url: lesson14.html
---

One application of deep learning that has progressed perhaps more than any other in the last couple of years is Neural Machine Translation. In late 2016 it was implemented by Google in what the New York Times called [The Great A.I. Awakening](https://www.nytimes.com/2016/12/14/magazine/the-great-ai-awakening.html). There's a lot of tricks needed to reach Google's level of translation capability, so we'll be doing a deep dive in this lesson to learn nearly all the tricks used by state of the art systems.

Next up, we'll learn about _Densenets_, which in July 2017 were awarded the CVPR Best Paper award, and have been shown to provide state of the art results in computer vision, particularly with small datasets. They are very similar to resnets, but with one key difference: the branches in each section are combined through concatenation, rather than addition. This apparently minor change makes a big difference in how they learn. We'll also be using this technique in the next lesson to create a state of the art system for image segmentation.

