---
title: Creating a World Athletics Score Calculator
description: Developing a calculator for athletes to determine world athletic scores.
date: 2025-06-06
tags: []
---

Going to the Olympics or World Championships in track and field is hard. But it used to be relatively simple (at least in the US). All you have to do is run the world standard and get selected by the country you compete for. However, in 2019 World Athletics shook this up by introducing the world ranking system. The goal was to create a better system for identifying the best athletes in the world. It would assign a score to every event an athlete competed in and then use the average of their top scores to compute their world ranking. This score is partially based on the mark the athlete achieved but also has a placement component. While the score from the athlete's mark is standard across all competitions, competing in bigger, more prestegous meets results in more placement points. The goal of these placement points is to incentivise the best in the world to compete in the best meets in the world.

Overall, I think that this system is great. It is important for the sport to have the best athletes compete against each other as much as possible. My biggest issues with the system as both an athlete and a fan is that it is difficult to determine how scores are calculated.

Last year, I had an outside chance at making the US Olympic Team in the 3k Steeplechase. However, I had not run the world standard and felt like my best chance would come from improving my world ranking. The question then became what races gave me the best chance at scoring the most points. After spending several hours digging through the world ranking rules, creating spreadsheets, and researching every meet that had a 3k steeplechase within a 3 continent radius, I came up with a plan. By the US Olympic trials I was able to get a high enough world ranking to qualify for he Olympics. None of this ended up mattering because I shit the bed at the trials but it was worth a shot.

This experience convinced me that calculating world ranking scores should be much easier. I looked around for online calculators but none existed. There are a couple that will tell you the performance component of your score but none that account for the placement piece as well. Because of this, I made my own. It is running [here](https://derekjohnsonva.github.io/world_athletics_points_calculator/) and I hope that other people find it useful. The code for this project is on my [github](https://github.com/derekjohnsonva/world_athletics_points_calculator). If anyone finds errors or has suggestions for features that would improve it, let me know!
