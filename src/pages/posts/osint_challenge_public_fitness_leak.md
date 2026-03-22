---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: Public fitness leak"
pubDate: 2026-03-22
description: 'During a review of public digital traces tied to a suspicious online persona, analysts identified a fitness-tracking account that may belong to the same individual operating under a different identity.

The account appeared harmless at first glance, containing several running activities with routine titles and publicly shared route maps. However, repeated activity patterns, route geometry, timestamps, and recurring landmarks may reveal more information than intended.'
author: 'raz'
tags: ["OSINT", "CTF", "GEOINT"]
---

**Challenge link**: https://osintchallenges.com/challenges/public-fitness-leak/

## Objectives
Your task is to review the recovered evidence and determine what the subject’s activity history reveals. By analyzing the routes and identifying repeated locations, determine the city most strongly associated with the account and the public landmark that appears central to the subject’s activity pattern.

## Solution
Download the archive. 

We have multiple ways of approaching this, including the review of the .gpx (a standardised xml based format for storing GPS data), the user Strava profile, which you should probably keep it private if you are deployed (see: [French aircraft carrier Charles de Gaulle tracked via Strava activity in OPSEC failure](https://securityaffairs.com/189696/intelligence/french-aircraft-carrier-charles-de-gaulle-tracked-via-strava-activity-in-opsec-failure.html) and [Fitness tracking app Strava gives away location of secret US army bases](https://www.theguardian.com/world/2018/jan/28/fitness-tracking-app-gives-away-location-of-secret-us-army-bases)) and several screenshots which, if you review them on Google maps (simply search for *Pont d'Iéna*), you will easily find the flag for this.

## Flag
(Probably) the most popular French landmark
