---
layout: lesson
lesson: How to set up your AWS deep learning server
youtube_id: 8rjRfW4JM2I
wiki_file: AWS_install
notes_file: AWS_install
forum_thread: setup-problems-aws
prev_url: lessons.html
next_url: lesson1.html
---
Before you can start with the first full lesson, you'll need a deep learning capable machine (that is, a computer with an Nvidia GPU in it) that you can use. For this course, most of the information we provide assumes that you are using Amazon Web Services (AWS) for this. To make it as easy as possible for you to get started with AWS, we have provided scripts that automate most of the process of setting up your AWS deep learning server.

This video shows all the steps necessary to set up your deep learning server, using a recently released AWS product called "P2", which has a powerful GPU with a lot of memory. It costs $0.90 per hour to run. The linked resources on the left provide more information about how and why to set this up. Remember, if you get stuck, search the forum (using the link on the left), and ask any questions you have there if you can't find an answer.

This video, and most of our documentation, use the AWS region us-west-2 (Oregon) as the default.  If you are based in Europe, you will want to use eu-west-1 (Ireland) instead and to use <a href="https://github.com/fastai/courses/blob/master/setup/setup_p2_ireland.sh">setup_p2_ireland.sh</a> instead of <a href="https://github.com/fastai/courses/blob/master/setup/setup_p2.sh">setup_p2.sh</a>.  Currently, the AWS p2 is only offered in 3 regions.  If you are living outside of the US or Europe, you can still use an AMI in one of these regions but may experience higher latency.

*NB*: AWS needs to verify that new accounts are not fraudulent, so you'll need to make a special request for P2 access if you're a new AWS customer. The video shows how to make this request, but please note that there *has been a change*: you can now request P2 instances directly in the form, whereas when this video was created P2 instances were too new and were not listed; also, be sure to use the 'use case description' listed in the video. It is important that you don't try to create your P2 server until your request has been actioned; to check whether it has, visit <a href="https://us-west-2.console.aws.amazon.com/ec2/v2/home?region=us-west-2#Limits:">this link</a> and find the row for "p2.xlarge".

PS: We've just learned that Azure now allows new users to access GPU machines without requiring a special request, and will provide $200 of free credits! They work nearly exactly the same way as Azure, except that you'll need to run our setup script to configure them. With many thanks to Abhik Mitra, one of our MOOC participants, we now have a [setup guide](https://medium.com/@abhikprince/setting-up-an-azure-vm-for-deep-learning-bb76b453272b#.lozevofv6) showing how to do this.
