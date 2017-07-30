---
layout: lesson2
lesson: 11&mdash;Memory Networks
youtube_id: bZmJvmxfH6I
wiki_file: lesson-11-wiki
forum_thread: lesson-11-discussion
prev_url: lesson10.html
next_url: lesson12.html
---

We've covered a lot of different architectures, training algorithms, and all kinds of other CNN tricks during this course&mdash;so you might be wondering: what should I be using, when? The good news is that other folks have wondered that too, and have provided some great analyses of the pros and cons of various techniques in practice. We'll be taking a look at a few highlights of these papers today.

Then we're going to learn to GPU accelerate algorithms by taking advantage of Pytorch, which provides an interface that's so similar to numpy that often you can move your algorithm onto the GPU in just an hour or two. In particular, we're going to try to create the first (that we know of) GPU implementation of mean-shift clustering, a really useful algorithm that deserves to be more widely known.

To close out the lesson we will implement the heavily publicized "Memory Networks" algorithm, and will answer the question: does it live up to the hype?
