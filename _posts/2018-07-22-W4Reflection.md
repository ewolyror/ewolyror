---
layout: post
comments: True
title: Frying the Bigger Fish-Week Four Reflection
---

# New Programs, New Problems

This week has been filled with beginning to learn a new program to run photometry on our images. Although our new program, dolphot, is already all coded, learning how to use it has proven almost as time consuming as writing our own code to perform aperture photometry. Dolphot is much more powerful than our aperture photometry code as it performs PSF rather than aperture photometry, so it is worth the time to be able to use the more powerful tools included in dolphot. A large part of my confusion with dolphot is that it was written in C, a program neither Thom nor I have familiarity with. Even a simple thing such as learning how to run a program written in C in the command line ended up taking a while to figure out.

A discovery that I hope will make our lives easier is the python wrapper pydolphot which is available on GitHub. It streamlines much of the command line work required to run dolphot and makes the actual running of the code a breeze. It is a fairly small program with only a few subprograms, and the whole repo has only one contributor whereas many open-source projects have many contributors. There were a few errors in pydolphot code that I had to correct, but it is difficult to correct errors in code I didn't write. Luckily the errors I found didn't require a knowledge of the program but rather just involved replacing spaces with tabs. I still have yet to get the code to work correctly though, so I think there are some errors still either in the code or in my directory structure that are keeping the code from finding the images I want for it to analyze.

# Group Progress

Marta presented her progress on adding WCS data to the DIAFI data on Friday and it was really exciting to see the progress she has made learning many new programs and getting great astrometric matches for the images with astrometry.net and comparing her matches to the GAIA catalog. When dolphot comes together for me and Thom and the DIAFI images get reduced, I am really excited to begin to get some results from our project. It is nice to be finally working towards more concrete common goals with each other.

# How It's Going

I am definitely getting more invested in the project in this stage of the process. It feels more important now that I know that dolphot will be the key to our results and not just an exercise. I have had a good week in terms of work productivity, with a few long days and also a few days that weren't as productive. It was nice to work on the project this weekend, although I hope to, in the future keep my work better compartmentalized into weekdays between 8-5 as I feel it makes for more productive time in the day and more restful break time in between.

It is wild how quickly this summer has flown by. Although only four weeks dedicated to research have gone by, only about four weeks remain. I think that the sense of time constraint has also increased my drive on this project. I hope to have some results to discuss by the time school starts again in late August.

# Next Week and more

Next week I am working normally from Monday to Wednesday and then heading home for two weeks until August 8th. Luckily, the research group has a great online collaboration set up where we can check each other's blogs, check the research group Github, and generally stay connected even when we aren't physically together. I also will ask the research group tomorrow if they feel it would be helpful to have me video chat in to the research meetings on Mondays and Thursdays. I hope to continue working a similar schedule while at home and think that it would be helpful to hear from everyone else and update the group on my progress during these research meetings while I am at home. I will be in a few different locations, some of which don't allow online work, and I also may have a few days of significant family commitments when I can't put any time towards research. Because of this, I am not going to try to make a fixed plan for hours of work/day, but I do hope to keep a normal sleep schedule and get up a few hours before my family members and get a little bit of work done each day before the distractions descend as well as during downtime throughout the day.
