---
title: My SAA Certification Journey.
description: This is a post on how I passed the SAA exam with very minimal cloud experience.
date: 2024-11-15
tags: []
---

In September of this year, I decided to tackle the **AWS Certified Solutions Architect Associate (SAA)** exam. Spoiler alert: I passed! 🎉 While studying, I often thought, _"If I could start this process over, what would I do differently?". This post is my attempt to answer that question. I'll share how I studied, what worked, and what I'd change if I had a redo.

## Studying

My studying journey was a bit of a rollercoaster 🎢—some weeks I was highly motivated, while others I could barely bring myself to glance at my notes. Here's a rough breakdown of my timeline:

- **Weeks 1–4**: Worked through Adrian Cantrill's SAA-C03 course.
- **Weeks 4–6**: Reviewed notes and took random practice tests I found online.
- **Weeks 7–8**: Dug into TutorialDojo practice tests and started using Anki.
- **End of Week 8**: Passed the test! 🏆

### Course Review

Adrian Cantrill’s course provided an excellent overview of AWS services and how they interact. However, I have a confession: I quit doing the demo lessons after about 25% of the course. The whole "click-this-button-then-that-button" routine didn’t feel like it was sticking. If the demos had been more self-guided, I think they might have reinforced the concepts better.

I took detailed notes on all the services as I went through the course, which you can find [here](https://github.com/derekjohnsonva/AWS-Certified-Solutions-Architext-Notes/tree/main). To take these notes I use [Obsidian](https://obsidian.md/), which is one of my all time favorite apps. Honestly, my only issue with Obsidian is the people who evangelize it online. It isn't great at everything but it crushes taking notes for a class.

### Where I Went Off Track

The time between finishing the Cantrill course and starting TutorialDojo practice tests was where I wasted the most time. This period was mostly me spinning my wheels trying to gather test-related info. I quickly realized I hadn’t retained as much as I’d hoped—especially around networking—and my recall was foggy at best.

Thankfully, this detour led me to discover [Anki](https://apps.ankiweb.net/), the best flashcard system I’ve used. Like Obsidian, its fans hype it up a bit too much, but for this exam, it was a game-changer. AWS exams often test your ability to differentiate between services, and Anki helped me commit those details to memory.

I started by downloading a [shared deck](https://ankiweb.net/shared/info/1917956996) and worked through it. I also eventually caved and paid $10 for access to TutorialDojo practice tests—money well spent.

### Practice Makes... Passing

At first, I failed every practice test. 😭 Demoralizing? Absolutely. But by the sixth test, my scores had climbed into the 70s. The biggest factor in my improvement was reviewing missed questions and turning them into flashcards. Anki's [guide on good flashcard design](https://docs.ankiweb.net/getting-started.html#key-concepts) helped me create cards that didn't suck.

I learned that quickly scanning missed questions wasn’t enough; without flashcards, I’d miss the same questions again. Flashcards kept me honest. Reflecting on this, I wish I’d been this rigorous in college. I spent a lot of time _thinking_ I knew things when, in reality, I was just good at peeking at the answer key.

By the end of Week 8, after a week of daily practice tests and reviews, I scheduled my exam. 

---
## The Exam

The exam itself went as well as I could have hoped. I scored 847/1000, which was higher than my practice test averages. 🎉

### Topics I Thought Were Overrepresented

- VPCs and how to connect them.
- RDS (especially Proxies).
- Load Balancers (ALB vs. NLB).
- Billing.
- Organizational Units.
- Web Application Firewalls.

### Topics I Was Surprised to See Missing

- CloudHSM.
- FSx.
- Machine Learning.
- SQS vs. SNS.

---

## Reflection

Looking back, I realize I wasted a lot of time transcribing detailed notes on every service. While taking notes helped me stay engaged, **TutorialDojo’s service summaries** were far more comprehensive than mine. If I could do it again, I’d take brief notes and focus more on flashcards for reviewing service details.

The notes I _did_ find useful were those comparing related services, like...
- RDS vs. Aurora.
- SQS vs. SNS.
- VPC Peering vs. Transit Gateway.
- NACLs vs. Security Groups.

Anything that helps build context for when to use different services is invaluable.

I’m not sure if I’ll pursue more AWS certifications, but if I do, I feel confident I’ll study more efficiently next time. For now, I’m just happy I passed.
