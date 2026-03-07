---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Satoshi Tribute Address: Daily Received Total"
pubDate: 2022-07-01
description: 'The Bitcoin address below is widely known as a tribute address associated with Satoshi Nakamoto and continues to receive small transactions from the public.
On January 6th, 2026, a transaction was broadcast to this address and included in the Bitcoin blockchain.

Your mission is to analyze the transaction and determine exactly how much BTC was received in that specific transaction.'
author: 'raz'
tags: ["OSINT", "CTF"]
---

**Challenge link**: https://osintchallenges.com/?weekly_challenge=satoshi-tribute-address-daily-received-total

## Objectives
1. Locate the transaction using the provided transaction hash
2. Identify the recipient address
3. Determine the exact amount of BTC received in the transaction

## Solution

Since this is an _Easy_ challenge, it's quite straightforward:

1. Locate the transaction using the provided transaction hash

Get the transaction hash from the challenge description _d8773c23582a0bf0fe7f640fd1053c14c5ebf3782fed994bd9cd2aed7d19dedd_ and check any bitcoin blockchain explorer: [Blockchain explorer](https://bitaps.com/d8773c23582a0bf0fe7f640fd1053c14c5ebf3782fed994bd9cd2aed7d19dedd)

Everything is available on the page, just make sure to select the actual amount, after the fee.

![](/src/pages/posts/screenshots/osint_challenge_satoshi_tribute_address.png)

## Flag
Transaction amount: *2168BTC