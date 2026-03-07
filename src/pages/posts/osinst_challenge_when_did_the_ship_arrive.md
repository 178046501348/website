---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: When did the ship arrive"
pubDate: 2026-03-07
description: 'A publicly accessible website is running a specific content management system (CMS).
Your mission is to analyze the target website and determine which CMS powers the site.'
author: 'raz'
tags: ["OSINT", "CTF"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=when-did-the-ship-arrive

## Objectives
1. Identify the vessel shown in the image
2. Analyze maritime tracking data for the vessel
3. Determine the arrival date at Port Houston, United States

## Solution
![](https://osintchallenges.com/wp-content/uploads/2026/02/1000020072-1-1024x636.jpg)

The name of the ship is easily readable: _Conti Cortesia_

A quick google search for `conti cortesia vessel schedule`

https://ecomm.one-line.com/one-ecom/schedule/vessel-schedule?vslCdParam=CIKT&vslEngNmParam=CONTI+CORTESIA+%28CIKT%29&f_cmd=

Do a quick ctrl+f for _Houston_ and keep in mind that the format there is Month-Year-Day

## Flag
*, 2026

Bonus: Check Rae Baker on social media, she is an SME when it comes to maritime intelligence