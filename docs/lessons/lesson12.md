---
layout: lesson2
lesson: 12&mdash; Generative Adversarial Networks (GANs)
youtube_id:UqpwXKtkgvk
forum_thread: part-2-lesson-12-wiki
prev_url: lesson11.html
next_url: lesson13.html
---

We start today with a deep dive into the DarkNet architecture used in YOLOv3, and use it to better understand all the details and choices that you can make when implementing a resnet-ish architecture. The basic approach discussed here is what we used to win the DAWNBench competition!

Then we’ll learn about Generative Adversarial Networks (GANs). This is, at its heart, a different kind of loss function. GANs have a *generator* and a *discriminator* that battle it out, and in the process combine to create a generative model that can create highly realistic outputs. We’ll be looking at the *Wasserstein GAN* variant, since it’s easier to train and more resilient to a range of hyperparameters.

