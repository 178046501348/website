---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: Unknown Host"
pubDate: 2026-03-015
description: 'During an investigation, analysts recovered a connection log from a remote server.The log contains a source IP address and a message written in a foreign language.Your mission is to analyze the IP address, determine the origin of the message, translate the text, and identify the real-world location being referenced.'
author: 'raz'
tags: ["OSINT", "CTF", "Forensics"]
---

**Challenge link**: https://osintchallenges.com/challenges/unknown-host/

## Objectives
Your mission is to analyze the image file and determine the real-world location referenced in the hidden message.

## Solution
It's clearly something related to Korea, but first, let's check the ip address: https://ipinfo.io/223.130.192.2?lookup_source=search-bar. Seems that the IP is from Seoul, South Korea.

Then, I used Google Images to extract the text and translate it from Korean to *Gyeongdeokgung is the most famous palace in Seoul.*

A quick google search for the phrase above we get a bit more info about the location: https://excursionmania.com/ttd/8063/gyeongbokgung-palace-blg-8063#:~:text=Gyeongbokgung%20Palace%20is%20the%20largest,of%20Korean%20kings%20for%20centuries.

## Flag
*** Palace, Seoul, South Korea
