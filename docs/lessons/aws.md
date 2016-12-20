---
layout: lesson
lesson: How to set up your AWS deep learning server
youtube_id: UV6WIBi9GJQ
wiki_file: AWS_install
notes_file: AWS_install
forum_thread: setup-problems-aws
prev_url: lessons.html
next_url: lesson1.html
---
Before you can start with the first full lesson, you'll need a deep learning capable machine (that is, a computer with an Nvidia GPU in it) that you can use. For this course, most of the information we provide assumes that you are using Amazon Web Services (AWS) for this. To make it as easy as possible for you to get started with AWS, we have provided scripts that automate most of the process of setting up your AWS deep learning server.

This video shows all the steps necessary to set up your deep learning server, using a recently released AWS product called "P2", which has a powerful GPU with a lot of memory. It costs $0.90 per hour to run. The linked resources on the left provide more information about how and why to set this up. Remember, if you get stuck, search the forum (using the link on the left), and ask any questions you have there if you can't find an answer.

*NB*: AWS needs to verify that new accounts are not fraudulent, so you'll need to make a special request for P2 access if you're a new AWS customer. The video shows how to make this request, but please note that there *has been a change*: you can now request P2 instances directly in the form, whereas when this video was created P2 instances were too new and were not listed. It is important that you don't try to create your P2 server until your request has been actioned; to check whether it has, visit <a href="https://us-west-2.console.aws.amazon.com/ec2/v2/home?region=us-west-2#Limits:">this link</a> and find the row for "p2.xlarge".

PS: If you have an active Azure account, you can use their new GPU servers instead. They work nearly exactly the same way, except that you'll need to run our setup script to configure them. Details are on the wiki and help is available on the forum if you want to take this route.
