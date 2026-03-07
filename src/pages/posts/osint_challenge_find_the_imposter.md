---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: Find the Imposter"
pubDate: 2026-03-07
description: 'Two social media profiles appear to represent the same online personality.
At first glance, both accounts look legitimate.

However, one of these profiles is an impersonation account.

Your mission is to analyze both profiles and determine which profile is being impersonated.

This challenge focuses on SOCMINT techniques, including profile verification, branding consistency, and cross-platform correlation.'
author: 'raz'
tags: ["OSINT", "CTF", "SOCMINT"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=find-the-imposter

## Objectives
Determine which profile is being impersonated between: https://www.facebook.com/trsamalkhatib/ and https://www.facebook.com/p/Therealkhatib-100094694995629/

![](https://osintchallenges.com/wp-content/uploads/2026/02/challenge3-1.png)

## Solution
In a normal SocMint investigation there are several clues you should look into (see: https://medium.com/@nemo14398/osint-playbook-a-step-by-step-guide-for-modern-investigators-6bbc9e897bac), but given that this is a CTF, I simply checked the first profile and noticed that:

1. It's verified
2. Has a long history of postings
3. Has a large following
4. Has multiple other social media accounts linked

## Flag
Well...it's not profile A