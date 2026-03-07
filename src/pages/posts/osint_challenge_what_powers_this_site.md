---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: What powers this site"
pubDate: 2026-03-07
description: 'A publicly accessible website is running a specific content management system (CMS).
Your mission is to analyze the target website and determine which CMS powers the site.'
author: 'raz'
tags: ["OSINT", "CTF"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=what-powers-this-site

## Objectives
Determine which CMS powers https://www.tesla.com

## Solution
Really easy, we just need to check what runs on the website. There are various tools to do that, I simply checked it with https://builtwith.com/tesla.com then did a quick ctrl+f for _cms_

## Flag
It runs on PHP 😟 , also don't include the 9
