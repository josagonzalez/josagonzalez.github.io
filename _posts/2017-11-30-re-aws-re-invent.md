---
title: "Re: AWS Re:Invent"
excerpt: Outcome of a weeklong AWS conference
author: josagonzalez
tags: featured
background-image: reinvent-vegas.jpg
categories:
  - topics
#date/lastupdated are optional
#date: 2017-11-30 12:15:41
#lastupdated: 2017-11-30 12:15:41
---

I'm wrapping up at [AWS re:Invent](https://reinvent.awsevents.com) this week and I'm eager to get back to work on Monday and start implementing some of the stuff I learned and ideas I got from different presenters and with new products.

Just a few months ago I was a total AWS n00b. I went to BlackHat and took a cloud security course all in AWS and learned a lot of the basics, but I didn't know a lot about the tools and services that AWS offers. But this week, I was able to solidify a lot of the knowledge I've been gaining from my day-to-day and got to play with some neat tools that will hopefully aid in getting our security practice where it needs to be at VividCortex. 

At the top of my list is [GuardDuty](https://aws.amazon.com/guardduty/), a new managed Threat Detection tool that uses machine learning to detect unauthorized or malicious behavior. The amazing part of it is its completely serverless, and goes to work at the flip of a switch. No setup, no agents, no central server, no nothing!

Next up is [Macie](https://aws.amazon.com/macie/), another machine learning service that discovers, classifies, and protects sensitive data in S3. I learned about Macie a couple months ago when it was first released, but I didn't think it really fit our needs at VividCortex. After talking to some Macie engineers, I realized it can definitely fit our architecture and it will be very valuable in one of my upcoming projects. I'm super stoked to give it a try!

A couple other tools that I want to make use of is [Config](https://aws.amazon.com/config/) and [Inspector](https://aws.amazon.com/inspector/). Config will allow us to assess, audit, and evaluate configurations in AWS and Inspector will help with running security assessments.

First thing I need to do when I get back (and maybe on the flight home), will be read the AWS Security whitepaper. Don't ask why I haven't read it yet! GuardDuty and Macie should fit seamlessly into our current architecture, and I can use the suggestions from the whitepaper to move toward an environment where we can leverage Config and Inspector.

After spending a week at re:Invent almost exclusively on the security track, I am finally seeing how we can fully leverage these AWS tools in our environment. I see the value in them and how they will help us get to a useful SecDevOps practice. Wish me luck as I embark on this journey! :sailboat:

.josa