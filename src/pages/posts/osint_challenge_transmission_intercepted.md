---
layout: ../../layouts/MarkdownPostLayout.astro
title: "OSINT CTF: Transmission Intercepted"
pubDate: 2026-03-08
description: 'An intercepted radio transmission was captured during routine monitoring operations.The signal appears structured and repetitive, suggesting a deliberate encoded message.Your mission is to analyze the audio transmission, decode the signal, and determine the real-world location being referenced.'
author: 'raz'
tags: ["OSINT", "CTF"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=transmission-intercepted

## Objectives
Decode the and find the location.

## Solution
When we open the file, we immediately hear some regular beeps, so my first thought was that I am dealing with some Morse code.

I then uploaded the file to an audio decoder (you can also do it by pen and paper, but...I think we are past that point with modern technology), like: https://themorsecodetranslator.net/morse-code-audio-decoder/ and it detected the following sequence

` --. --- .-.. -.. . -. / -... .-. .. -.. --. . / ...- .. . - -. .- -- `

The tool I've linked above will do the translation for you, alternatively, you can also use CyberChef with the _From Morse Code_ operation.

## Flag
Make sure to write the name of the location proper (you can use excel =PROPER() function) and not with ALL CAPS 