# Day 8: Binary Basics

## 📖 Topic
IP addressing and subnetting are built on binary math. Being fast at
converting between binary and decimal makes subnetting much easier.

## 🧠 Key Concepts

- Each IPv4 octet is 8 bits, with place values (left to right):
  `128 64 32 16 8 4 2 1`

- To convert decimal → binary: figure out which place values sum to your
  number.
  *Example: 192 = 128 + 64 → binary `11000000`*
  *Example: 45 = 32 + 8 + 4 + 1 → binary `00101101`*

- To convert binary → decimal: add up the place values where there's a 1.
  *Example: `11010000` = 128 + 64 + 16 = 208*

- Common ones worth memorizing (they show up constantly in subnetting):
  - `255` = `11111111`
  - `254` = `11111110`
  - `252` = `11111100`
  - `248` = `11111000`
  - `240` = `11110000`
  - `224` = `11100000`
  - `192` = `11000000`
  - `128` = `10000000`
  - `0`   = `00000000`

## 💻 Practice Log
- [ ] Did 20 binary ↔ decimal conversions on paper (mix of both directions)

## 📝 My Notes (in my own words)
> Write the trick/process you use to convert quickly. List any conversions
> that took you a long time.

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
