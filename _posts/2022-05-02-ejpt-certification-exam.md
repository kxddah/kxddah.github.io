---
layout: post
title:  "eJPT Exam Review"
date:   2022-05-02 0:10:00 +0530
tags: eJPT Certification
---
Last week I took my eJPT certification exam and cleared it🥳. So I thought of sharing my experience.
<br/><br/>

![cert image](/public/media/ejpt.jpg)

<br/>

First, let's cover the basic information:<br/>
**Preparation**: INE provides a <u>Penetration Testing Student (PTS)</u> course which is more than enough to have a successful attempt. The best part is that it is free of charge! It takes you through all the basics of how web and networks work before getting into the hacking. You can find it [here](https://my.ine.com/CyberSecurity/learning-paths/a223968e-3a74-45ed-884d-2d16760b8bbd/penetration-testing-student)
<br/><br/>
**Cost**: It costs 200$ for the exam voucher validity of which is for the next 180 days and you get 2 attempts.
<br/><br/>
**Exam**: One gets 72 hours to answer 20 MCQs out of which 15 should be right (i.e. 75%) to pass the exam
<br/><br/>
**Changes**: Note that the above information would soon be changing as eLearnSecurity will be coming out with eJPTv2 and discontinuing the v1. They would have a v2 of the PTS course, the exam would be browser-based, time would be decreased to 48 hours and questions to answer will be 35. More details can be found [here](https://ine.com/blog/new-ejpt-coming-soon?utm_source=linkedin&utm_medium=organic&utm_campaign=NeweJPTComingSoon&utm_content=blog)
<br/><br/>
I had been planning to take the exam for quite a while therefore took the v1. But if you have the time, then wait for the v2 as it would offer more value and update some old course material to reflect the current ways of testing.
<br/><br/>
# My experience
I followed the PTS course provided by INE, all the labs in the course are browser-based except the last few, it is recommended that one gets familiarized with any Linux distro (eg. Kali Linux) if you are taking the current eJPT exam where you would have to use OpenVPN to connect to the exam environment. 
The course is pretty good but it can get boring sometimes as it has a lot of slideshows, there are videos for most of the topics but reading the slides is necessary as the videos complement the slides and are not a replacement.
<br/><br/>
The most important part of the course are the 4 Black box labs at the end, these are pretty thorough and prepare you well for the exam, if one can solve all of these then they can easily crack the exam. I couldn't find all solutions of the black boxes and had to refer to the solutions, it is important that you take a lot of notes, I learned something new from each of the boxes and took good notes. You can refer to these notes or even the course during the exam if you're stuck somewhere.
I have very little prior experience with TryHackMe and HackTheBox, you can look up some boxes that might be helpful for eJPT but it's not necessary to pass the exam.
<br/><br/>
**The exam** wasn't very tough, out of the 20 questions few were trivial while few required you to enumerate well and get into some machines, all the questions are based on the environment and the machines provided. I was able to complete the exam in 24 hours and scored 18 out of 20.
<br/><br/>
I had read a lot of articles of people getting stuck in the beginning with the **routing** part, and as expected I got stuck on that too, this is because the PTS lab "Find the Secret server" does not prepare you well for the routing required in the exam. It took me the first 1.5 hours to figure it out and [this](https://www.reddit.com/r/eLearnSecurity/comments/jhbx2d/ejpt_routing_advice/) Reddit post gave me a spark 
<br/><br/>
I did face some issues with pivoting probably causing me to lose one of the two points, the Black box 1 has some pivoting but I faced some issues completing the lab, I have yet to figure out where I went wrong, another thing to note is that eLearnSecurity doesn't tell you what questions were wrong and their solutions regardless of you passing or failing the exam
<br/><br/>
Hope this was helpful in some way, this is my first blog post and pardon me if the site does not look complete, this is my first time building one :)