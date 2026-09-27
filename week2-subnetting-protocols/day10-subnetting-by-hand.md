# Day 10: Subnetting by Hand — Network, Broadcast, Host Range

## 📖 Topic
Given an IP + CIDR, calculate: subnet mask, network address, broadcast
address, first/last usable host, and total usable hosts.

## 🧠 Key Concepts

- **The block size trick**: subtract the interesting octet's mask value
  from 256 to get the "block size" (how far apart network addresses are).
  *Example: `/27` → mask `255.255.255.224` → 256 − 224 = 32 → subnets are
  32 addresses apart: `.0, .32, .64, .96...`*

- **Steps to solve `192.168.1.50/27`:**
  1. Mask: `/27` = `255.255.255.224`
  2. Block size = 256 − 224 = 32
  3. Find which block `50` falls in: `32 ≤ 50 < 64` → network = `192.168.1.32`
  4. Broadcast = next block start − 1 = `64 − 1` = `192.168.1.63`
  5. First host = network + 1 = `192.168.1.33`
  6. Last host = broadcast − 1 = `192.168.1.62`
  7. Usable hosts = 2^5 − 2 = 30 (5 host bits since /27 leaves 5 bits)

## 💻 Practice Log
- [ ] Solved 5 subnetting problems by hand (show full working, not just answers)

## 📝 My Notes (in my own words)
> Write out your 5 worked problems here, or link to where you did them.
> Note which step trips you up most.

(fill in here)

## ✅ Quiz Results
- Score: __ / __
- Date:
