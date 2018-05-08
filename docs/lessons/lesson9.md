---
layout: lesson2
lesson: 9&mdash;Object Detection 
youtube_id: 0frKXR-2PBY
forum_thread: part-2-lesson-9-wiki
prev_url: lesson8.html
next_url: lesson10.html
---

In today’s lesson we’ll move from single object to multi-object detection. It turns out that this slight difference makes things much more challenging. In fact, most students found this the most challenging lesson in the whole course. Not because any one piece is highly complex, but because there’s a lot of pieces, so it really tests your understanding of the foundations we’ve learnt so far. So don’t worry if a lot of details are unclear on first viewing – come back to this lesson from time to time as you complete the rest of the course, and you should find more and more of it making sense!

Today’s focus is on the *single shot multibox detector* (SSD). This is a way to handle multi-object detection by using a loss function that can combine losses from multiple objects, across both localization and classification. It also uses a custom architecture that takes advantage of the difference receptive fields of different layers of a CNN. And we’ll see how to handle data augmentation in situations like this one where the dependent variable requires augmentation too. Finally, we’ll discuss and simple but powerful trick called *focal loss* which is used to get state of the art results in this field.

