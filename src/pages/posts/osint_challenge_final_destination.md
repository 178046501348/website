---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: Final Destination"
pubDate: 2026-03-07
description: 'A packet capture file has been recovered from a user’s browsing session.

The capture contains several normal website visits followed by one final destination.

Your mission is to analyze the network traffic and determine which domain the user accessed last.

This challenge focuses on network analysis fundamentals, including DNS inspection and traffic interpretation using packet capture data.'
author: 'raz'
tags: ["OSINT", "CTF", "Networking"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=final-destination

## Objectives
Determine which domain the user accessed last

## Solution
Ok, so, once you download the zip file, you need to use a dedicated tool like Wireshark to open the PCAP file. A PCAP is a format for storing packet capture of network traffic. You can read more about it here: https://corelight.com/resources/glossary/packet-capture-pcap

By default it is sorted from the earliest to the latest...so just entered the last domain queried by the user:

![](/website/src/pages/posts/screenshots/osint_challenge_final_destination.png)

## Flag
Flag: *.com