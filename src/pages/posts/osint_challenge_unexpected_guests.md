---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: Unexpetected guests"
pubDate: 2026-03-07
description: 'Two social media profiles appear to represent the same online personality.
At first glance, both accounts look legitimate.

However, one of these profiles is an impersonation account.

Your mission is to analyze both profiles and determine which profile is being impersonated.

This challenge focuses on SOCMINT techniques, including profile verification, branding consistency, and cross-platform correlation.'
author: 'raz'
tags: ["OSINT", "CTF"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=unexpected-guests

## Objectives
Find the location of this image: 

![](https://osintchallenges.com/wp-content/uploads/2026/01/Screenshot-2026-01-24-164236-1024x499.png)

## Solution
If we try to reverse image search via google images, one of the links returned will be this link:
https://www.gmapswidget.com/funny-google-maps-street-view/

With the following description:

`For some images, you will have to explore a little bit more in detail. In this example, if you open up The Buzz Mill bar in Texas, everything seems to be normal. Tables are ready for customers and it seems that the bar is empty. But if you follow this adventure and you and click on the next room, you might find a surprise. The bar isn’t empty and there are four “Furries” sitting in the back. Were those guys just joking around, is that part of the lost bet or maybe a movie in the making, we’ll probably never know.`

So, the location is _The Buzz Mill in Texas_.

A little bit more googling and it seems that it's quite popular: https://www.express.co.uk/travel/articles/1211251/Google-maps-street-view-US-texas-pub-animal-heads-weird-funny-viral

On Google maps, search for The Buzz Mill Bar, Texas. Then select street view and change year to 2021 and move around a bit, you will see the guys in the room.

![](./screenshots/osint_challenge_unexpected_guests.png)


## Flag
*-Austin, Texas, USA, 2018

